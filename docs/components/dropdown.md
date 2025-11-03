# コンポーネント: ドロップダウン（Dropdown）

メニュー項目や操作一覧を表示するドロップダウンです。ナビゲーション内やボタンに組み合わせて使えます。

例:

```html
<div class="uk-inline">
  <button class="uk-button">Menu</button>
  <div uk-dropdown>
    <ul class="uk-nav uk-dropdown-nav">
      <li class="uk-active"><a href="#">Active</a></li>
      <li><a href="#">Item</a></li>
    </ul>
  </div>
</div>
```

ポイント:
- `uk-dropdown` は位置やアニメーションのオプションがある。
- キーボード操作にも対応しておりアクセシビリティに配慮されている。