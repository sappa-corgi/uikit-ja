# コンポーネント: カバー（Cover）

背景画像や要素をコンテナいっぱいにカバーさせるためのユーティリティです。レスポンシブな背景表示に便利です。

例:

```html
<div class="uk-cover-container">
  <img src="path/to/image.jpg" alt="" uk-cover>
  <canvas width="600" height="400"></canvas>
</div>
```

ポイント:
- `uk-cover` 属性で画像を親要素に合わせてトリミング・拡大して表示する。
- レスポンシブで高さを維持するために `canvas` や `picture` を併用することが多い。