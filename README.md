# WEB_SIMPLE
- html: raw
- css: stylus
- js: babel
- Javascript Standard Style 準拠

## 構造
- debug : 開発用ディレクトリ
- releae : 納品用ディレクトリ
- src : 実コード
  - assets : アセット置き場所
  - babel : babel置き場所
  - html : html置き場所
  - stylus : stylus置き場所

## init
1. npm install
2. gulp でスタート

## gulpコマンド
- gulp
  - ローカルホストでリアルタイム更新しながら開発するためのもの
- gulp assets
  - debugフォルダとreleaseフォルダのassetsフォルダの中身を更新する
- gulp release
  - releaseフォルダに納品用のファイル群をエクスポートする
- gulp clear
  - debugとreleaseフォルダの中身を全消し

## reset.css
http://html5doctor.com/html-5-reset-stylesheet/