#　GeoHex
## 特徴
広く使われているGoogle Mapでは特定の位置を緯度と経度を表現されて、たとえば東京都心は（lat: 35.68, lng: 139.75）といった表され方をします。
一方、GeoHexでは、ピンポイントで示すわけでないので、ある座標をコード化したり、整数値のXY座標にしたりなど柔軟な方法で位置の特定や測定ができる。
また、ゲームで使用されるデザインが四角形よりも六角形のほうがかっこよく見ることができるため、GeoHEXが使用される。
また、六角形の場合だと、四角形と比べて線の距離を等距離にすることが容易い。
Hexによって全ての緯度経度の地点を表現するためのもの。
GOOGLE MAP と組み合わせるようにできている。

## 精度
六角形で位置を指定することができる

![2017-12-14 16 40 47](https://user-images.githubusercontent.com/34299469/33980758-95f75e3e-e0ed-11e7-8d6c-732f849c3cd0.png)

## 文字数
４〜７桁の短いコードに変換

## 利点
・以下の画像からもわかるように四角形の中に円を含む場合余分な面積が生まれる。六角形は円に近いため無駄な空間を作らなくて済む
・六角形は見た目がクールなことからゲームに用いられることがある

## 欠点
大きさの違う六角形同士の組み合わせが困難
勝手に指定したい位置が決まってしまう
