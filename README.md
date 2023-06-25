# ゴミ箱まっぷ！プロジェクト

これは、現在地を取得してゴミ箱の場所を地図上に表示するWebアプリケーションです。

## HTML構造

Webアプリケーションの基本的なHTML構造は以下の通りです。

- `<!DOCTYPE html>`：ドキュメントタイプ宣言
- `<html>`：HTML文書のルート要素
- `<head>`：HTML文書のメタデータを格納するコンテナ
- `<meta charset="UTF-8">`：ファイルの文字コードをUTF-8に指定
- `<title>`：ブラウザのタブや履歴に表示されるページタイトル
- `<link rel="icon">`：ページアイコン
- `<body>`：HTML文書のコンテンツ部分

## ページ要素

このWebアプリケーションには、以下の要素が含まれています。

- `<h2>`：アプリケーションのタイトル
- `<img>`：QRロゴ画像
- `<p>`：説明文
- `<a>`：開発ページへのリンク
- `<dl id="result">`：現在地情報を表示する要素
- `<div id="map">`：地図を表示する要素
- `<table id="csv-table">`：CSVデータを表示するテーブル

## スタイルとスクリプト

このWebアプリケーションでは、以下の外部リソースを利用しています。

- [Leaflet](https://leafletjs.com)：オープンソースの地図ライブラリ
- [jQuery](https://jquery.com)：JavaScriptライブラリ

## JavaScriptコード

JavaScriptコードは、以下の処理を行うために用意されています。

1. Leafletを使った地図の表示
2. カラーマーカーの作成
3. CSVファイルの読み込みとマーカーの表示
4. 現在地情報の取得とレッドマーカーの表示
5. マーカーとテーブルの操作

## 実行方法

HTMLファイルをブラウザで開くことで、Webアプリケーションが起動します。現在地情報が取得され、地図上に現在位置とゴミ箱の場所が表示されます。ゴミ箱のマーカーをクリックすると、その場所にあるゴミ箱の情報がポップアップで表示されます。テーブルの行をクリックすると、それに関連するマーカーが黄色く変わります。

注意：位置情報が取得できない場合は、ブラウザを変更してみてください。
