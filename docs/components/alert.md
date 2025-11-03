# コンポーネント: アラート（Alert）

重要なメッセージや通知を表示するためのシンプルなボックスです。閉じるボタンを付けられます。

例:

```html
<div class="uk-alert-primary" uk-alert>
  <a class="uk-alert-close" uk-close></a>
  <p>情報メッセージ。</p>
</div>
```

ポイント:
- `uk-alert-primary` / `uk-alert-danger` などで色を切り替えられる。
- `uk-alert` により閉じ動作等が提供される。