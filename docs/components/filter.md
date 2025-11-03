# コンポーネント: フィルター（Filter）

リストやグリッドの要素をフィルタリングして表示切替する機能を提供します。アニメーションと組み合わせて使うと見栄えが良くなります。

例:

```html
<ul class="uk-subnav" uk-sort="true">
  <li uk-filter-control="filter: .cat-a"><a href="#">A</a></li>
  <li uk-filter-control="filter: .cat-b"><a href="#">B</a></li>
</ul>

<div uk-filter="target: .js-filter">
  <div class="js-filter">
    <div class="cat-a">Item A1</div>
    <div class="cat-b">Item B1</div>
  </div>
</div>
```

ポイント:
- `uk-filter` は `uk-filter-control` と組み合わせて使う。
- アニメーションやソートと併用できる。