# findbusstop

5つ星オープンデータとGoogleマップを利用して、近くのバス停を検索するウェブアプリです。

## デモ
~~https://codeforfukui.github.io/findbusstop/~~ *(unavailable)*

## 機能
- デバイスの位置情報を使用して近くのバス停を検索します。
- SPARQLを通じて5つ星オープンデータからバス停およびルート情報を取得します。
- 検索結果をインタラクティブなGoogleマップに表示します。
- 英語、日本語、スペイン語など複数言語をサポートしています。

## 使い方
このプロジェクトをローカルで実行するには、Google Maps APIキーが必要です。

1.  **APIキーの取得**: [Google Cloud Console](https://console.developers.google.com/) からGoogle Maps APIキーを取得してください。
2.  **APIキーの設定**: `lib/gmap.js` を開き、`API_KEY` のプレースホルダー値を自身のキーに置き換えてください。
3.  **アプリの実行**: `index.html` をウェブブラウザで開きます。
4.  **バス停の検索**: 「最短」ボタンをクリックして周囲のバス停を検索します。
5.  **ナビゲーション**: 「前へ」および「次へ」ボタンを使用して検索結果を切り替えます。マップ上のアイコンをクリックして詳細を表示します。

## データソース
- **バス停データ**: [Open Data Portal (ODP)](https://odp.jig.jp/) およびその [SPARQLエンドポイント](https://sparql.odp.jig.jp/)。
- **マッピングおよびジオロケーション**: [Google Maps API](https://developers.google.com/maps)。

## クレジット
このプロジェクトは、[Code for Fukui](https://github.com/codeforfukui) のために Taisuke Fukuno ([@taisukef](https://github.com/taisukef)) によって作成されました。

## ライセンス
MIT License — [LICENSE](LICENSE) を参照してください。
