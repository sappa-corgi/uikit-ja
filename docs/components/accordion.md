# コンポーネント: アコーディオン（Accordion）

複数の折りたたみ可能なパネルを作るためのコンポーネントです。1つのパネルのみを開く設定や、複数同時に開ける設定が可能です。

例:

```html
<ul uk-accordion>
  <li class="uk-open">
    <a class="uk-accordion-title" href="#">タイトル1</a>
    <div class="uk-accordion-content">内容1</div>
  </li>
  <li>
    <a class="uk-accordion-title" href="#">タイトル2</a>
    <div class="uk-accordion-content">内容2</div>
  </li>
</ul>
```

ポイント:
- `uk-accordion` にオプションを渡して複数開放可/不可を切り替えられる。
- キーボード操作やアクセシビリティに配慮されている。