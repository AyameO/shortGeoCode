# LPadressの特徴
## 特徴
LP-Adressは12文字の’IP-Adress-like’フォーマットを使って世界中の場所を点で表したlocation pointer codeである。
目的は、少ない文字列で人間の脳裏に焼き付けること。

## 精度
場所を点で表している。
上限１２文字の中で文字を増やせば増やすほど、より詳細な位置情報を入手できる。
また、最初の文字がアルファベット２７字、次の２６文字、次の数字９文字の組み合わせによって、文字の種類が増えるため、精度がより向上する。

## 文字数
１２文字
XYN.XYN.XYN
[X]: A-Xまでのアルファベット
[Y]: A-Yまでのアルファベット
[N]: 0-9までの数字
で構成される。

## 利点
1. 検索しやすさ
→そもそもの緯度経度をコードパターン化しただけなので検索が一発

2. 人の手による間違いが最小限になる
→０とOなどの間違いがない

3. 反復リズムがあるため、覚えやすいこと

文字文字数字、文字文字数字、、、の繰り返しである。

## 欠点
→コード自体の入力方法がわかりにくい。

参考資料:http://lpaddress.com/
