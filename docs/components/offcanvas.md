# コンポーネント: オフキャンバス（Offcanvas）

画面外からスライドインするメニューやパネルを作るコンポーネントです。モバイルのメニュー実装によく使われます。

例:

```html
<button class="uk-button uk-button-default" uk-toggle="target: #offcanvas">Menu</button>

<div id="offcanvas" uk-offcanvas>
  <div class="uk-offcanvas-bar">
    <button class="uk-offcanvas-close" type="button" uk-close></button>
    <ul class="uk-nav uk-nav-default">
      <li><a href="#">リンク</a></li>
    </ul>
  </div>
</div>
```

ポイント:
- `uk-offcanvas` は位置（left/right）やモードを指定できる。
- フォーカス管理やスクロール制御が組み込まれている。