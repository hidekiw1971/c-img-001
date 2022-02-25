# module（共通部品）

## img:画像の表示を高画質ディスプレイに対応させる。

- https://creative.eccom.jp/922/
- Retina ディスプレイに代表されるような高画質ディスプレイに対応。
- srcset 属性を使う（高画質ディスプレイ対応）させる。
- srcset 属性を設定すると、デバイスの解像度によって最適な画像を表示してくれます。
- <img src="mameta@2x.png"
  srcset="mameta@2x.png 1x, mameta@3x.png.jpg 2x"
  width="200" height=""
  alt="">

## イメージ画像
<img width="1172" alt="image" src="https://user-images.githubusercontent.com/99580997/155713295-444040ea-c483-4fb9-997d-7b0e237acdc5.png">

## portfolio url:

- https://css-md-0009.wtb.cfbx.jp/

## module(共通部品)使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> b-name\_\_img をコピペ。

## 更新履歴

- 20yy/mm/dd 初版 ｘｘｘ

## 環境・使い方

- ダウンロードしたフォルダを開く
- ターミナルを開き、 npm i とコマンドを入力
- node_modules と package-lock.json が生成されるのを確認する
- 「 npx gulp 」とコマンドを入力すると動き出します
  å
