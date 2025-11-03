# コンポーネント: スイッチャー（Switcher）

タブ的にコンテンツを切り替える仕組み。ボタンやナビから該当するパネルを切り替える用途に使います。

例:

```html
<ul class="uk-subnav" uk-switcher>
  <li><a href="#">Tab1</a></li>
  <li><a href="#">Tab2</a></li>
</ul>
<ul class="uk-switcher">
  <li>Content1</li>
  <li>Content2</li>
</ul>
```

ポイント:
- アニメーションや初期表示インデックスを指定できる。