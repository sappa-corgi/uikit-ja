# コンポーネント: スライドショー（Slideshow）

画像やスライドを順番に切り替えるコンポーネント。自動再生やナビゲーション、アニメーションをサポートします。

例:

```html
<div uk-slideshow>
  <ul class="uk-slideshow-items">
    <li><img src="a.jpg" alt=""></li>
    <li><img src="b.jpg" alt=""></li>
  </ul>
  <a class="uk-position-center-left uk-slidenav-large" href="#" uk-slideshow-item="previous"></a>
  <a class="uk-position-center-right uk-slidenav-large" href="#" uk-slideshow-item="next"></a>
</div>
```

ポイント:
- `uk-slideshow` はスライド遷移や自動再生の設定が可能。
- レスポンシブ画像を組み合わせると見栄えが良い。