# コンポーネント: ナビゲーション（Navbar）

`uk-navbar` を使うとレスポンシブなナビゲーションバーを構築できます。左側や右側、ドロップダウンとの組み合わせなど典型的なナビのパターンを簡単に作れます。

## シンプルなナビ例
```html
<nav class="uk-navbar-container" uk-navbar>
  <div class="uk-navbar-left">
    <a class="uk-navbar-item uk-logo" href="#">サイト名</a>
  </div>
  <div class="uk-navbar-right">
    <ul class="uk-navbar-nav">
      <li><a href="#">リンク1</a></li>
      <li><a href="#">リンク2</a></li>
    </ul>
  </div>
</nav>
```

## ドロップダウン
ナビ内のリストにドロップダウンを組み合わせると、子メニューを簡単に作れます。公式ドキュメントでは `uk-navbar-dropdown` などでフォーマットされます。

## レスポンシブ考慮
モバイル時にハンバーガーメニューにするなどのパターンは、`uk-offcanvas` 等の別コンポーネントと組み合わせて実装することが多いです。

## カスタマイズ
背景色や間隔、ロゴサイズなどはユーティリティクラスで調整できます。より高度な変更は CSS を上書きしてください。
