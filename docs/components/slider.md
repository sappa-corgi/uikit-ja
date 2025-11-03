# コンポーネント: スライダー（Slider）

連続スクロール可能なカルーセルのようなレイアウトを実現するコンポーネント。複数アイテムの表示やスナップ等をサポートします。

例:

```html
<div uk-slider>
  <div class="uk-position-relative">
    <ul class="uk-slider-items uk-child-width-1-3@s">
      <li>Item1</li>
      <li>Item2</li>
    </ul>
    <a class="uk-position-center-left" href="#" uk-slidenav-previous uk-slider-item="previous"></a>
    <a class="uk-position-center-right" href="#" uk-slidenav-next uk-slider-item="next"></a>
  </div>
</div>
```

ポイント:
- アイテム幅や間隔を調整して多様なカルーセルを作れる。