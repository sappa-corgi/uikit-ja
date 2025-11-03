# コンポーネント: グリッド（Grid）

UIkit のグリッドはレスポンシブレイアウトを簡単に作るための仕組みです。`uk-grid` 属性と `uk-child-width-*` 系のクラスを主に使います。

## 基本
- `uk-grid` を持つ要素がグリッドコンテナになります。内部の直接の子要素がグリッドの列になります。
- `uk-child-width-1-2@s` のようなクラスで、特定のブレークポイント以上でのカラム幅を指定できます（`s`, `m`, `l` など）。

例（2列）:

```html
<div class="uk-grid-small uk-child-width-1-2@s" uk-grid>
  <div>
    <div class="uk-card uk-card-default uk-card-body">左</div>
  </div>
  <div>
    <div class="uk-card uk-card-default uk-card-body">右</div>
  </div>
</div>
```

### 属性のポイント
- `uk-grid-small`、`uk-grid-medium` などでギャップ（余白）の大きさを変えられます。
- 子要素の幅を明示的に設定したい場合は `uk-width-*` クラス（例: `uk-width-1-3@s`）を使うこともできます。

### レスポンシブ調整
`uk-child-width-1-3@s uk-child-width-1-4@l` のように複数のブレークポイントを組み合わせれば、小さい画面では3分割、より大きな画面では4分割、のような指定ができます。

### 列の高さを揃える
カード等の高さを揃える必要がある場合、カード内部のコンテンツに `uk-flex` 系のユーティリティクラスを使うと調整しやすくなります。


