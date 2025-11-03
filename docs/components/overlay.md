# コンポーネント: オーバーレイ（Overlay）

要素上に半透明レイヤーやインタラクティブなオーバーレイを置くためのユーティリティ。画像の上にテキストやボタンを重ねる用途など。

例:

```html
<div class="uk-inline-clip uk-transition-toggle" tabindex="0">
  <img src="image.jpg" alt="">
  <div class="uk-overlay uk-overlay-primary uk-position-center">
    <p>中央のテキスト</p>
  </div>
</div>
```

ポイント:
- `uk-overlay` と `uk-transition-*` 系でフェードやスライド効果を付けられる。