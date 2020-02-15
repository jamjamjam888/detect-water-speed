# detect-water-speed

背景差分法によるモーショントラッキングで水流を推定する。

全体像としては、

①背景差分法を用いて、水路上を流れる物体を検知
②フレーム毎に画像上の座標を取得する。
③水流を推定

を繰り返す。
今回は
Raspberry Pi3 Model Bとラズパイ対応のカメラを使用した。