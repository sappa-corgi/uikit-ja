# コンポーネント: ドロップ（Drop）

ターゲット要素に対して小さなポップアップ（ツールティップに似たもの）を表示するための低レベルコンポーネントです。ドロップはメニューや小さなアクションパネルに使われます。

例:

```html
<button uk-toggle="target: #drop">Open</button>
<div id="drop" uk-drop="mode: click">
  <div class="uk-card uk-card-body">ドロップ内容</div>
</div>
```

ポイント:
- `uk-drop` は位置やトリガー（hover/click）をオプションで制御できる。
- `uk-drop` はポップアップのレイアウトに柔軟性がある。