# コンポーネント: ライトボックス（Lightbox）

画像やギャラリーをモーダル表示で拡大表示するためのコンポーネントです。スライドやキャプションにも対応します。

例:

```html
<a href="large.jpg" data-caption="説明" uk-lightbox>
  <img src="thumb.jpg" alt="">
</a>
```

ポイント:
- ギャラリーは `data-caption` 属性やグループ化でページ内複数画像を連結できる。
- キーボード操作や自動スライドオプションがある。