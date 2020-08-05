# detect-water-speed
背景差分法によるモーショントラッキングで水流を推定する。

全体像としては、
```
1. 背景差分法を用いて、水路上を流れる物体を検知
2.フレーム毎に画像上の座標を取得する。
3. 水流を推定
```
を繰り返す。
今回はRaspberry Pi3 Model Bとラズパイ対応のカメラ(Picamera)を使用した。
