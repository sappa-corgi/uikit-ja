# 導入方法（Installation）

この章では UIkit をプロジェクトに追加する基本的な方法を説明します。CDN を使う方法とローカルにダウンロードして使う方法、必要に応じたビルドの概略を示します。

## CDN を使う（最短手順）
まずは手早く試すために CDN を使う方法です。`<head>` に CSS を、`<body>` の最後に JavaScript を読み込みます。例：

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/uikit@3/dist/css/uikit.min.css" />
<script src="https://cdn.jsdelivr.net/npm/uikit@3/dist/js/uikit.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/uikit@3/dist/js/uikit-icons.min.js"></script>
```

この方法はプロトタイプや小規模なページに便利です。

## ローカルにダウンロードして使う
公式のダウンロードページからアーカイブを取得し、`css/` と `js/` のファイルをプロジェクトに置いて読み込みます。利点はオフラインで使えることと、バージョン固定やカスタムビルドが容易になることです。

基本ファイル（例）:
- `css/uikit.min.css`
- `js/uikit.min.js`
- `js/uikit-icons.min.js`

## ソースからビルド（カスタムテーマ）
UIkit はソース（LESS 等）からカスタムビルドできます。テーマや変数を変更して再コンパイルしたい場合は公式のビルド手順に従ってください。

- Node.js とビルドツール（npm 等）が必要になることが多い。
- 開発中は unminified なファイルを読み、公開時に minified にするのが一般的。

## エディタ補助
開発効率を上げるためにエディタ用の補完・スニペットプラグインを導入すると便利です（例: VS Code のスニペットパッケージ）。

