# コンポーネント: ボタン（Button）

UIkit のボタンはシンプルに `uk-button` クラスを付けるだけで基本スタイルが適用されます。用途に応じて色やサイズ、形を変えるユーティリティクラスがあります。

## 基本クラス
- `uk-button` — ベース
- `uk-button-primary` — 強調（主要）ボタン
- `uk-button-default` — 標準ボタン
- `uk-button-text` — テキストボタン（背景なし）

例:
```html
<button class="uk-button uk-button-primary">主要</button>
<button class="uk-button uk-button-default">通常</button>
<button class="uk-button uk-button-text">テキスト</button>
```

## サイズ
- `uk-button-small`、`uk-button-large` でサイズを調整できます。

例:
```html
<button class="uk-button uk-button-primary uk-button-small">小さい</button>
<button class="uk-button uk-button-primary uk-button-large">大きい</button>
```

## アイコンとの組み合わせ
アイコンを入れる場合は HTML 内に `<span uk-icon="icon: star"></span>` のように書きます（`uikit-icons` を読み込む必要あり）。

例:
```html
<button class="uk-button uk-button-primary">
  <span uk-icon="icon: check"></span> 保存
</button>
```

## 状態とアクセシビリティ
- `disabled` 属性を使って無効化できます。
- スクリーンリーダー向けに `aria-*` 属性を適切に追加してください。

