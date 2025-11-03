# コンポーネント: モーダル（Modal / Dialog）

UIkit のモーダルは `uk-modal` 属性と `uk-toggle` を組み合わせることで実装します。構造はシンプルで、モーダル本体をページ内に置き、トリガーで表示します。

## 使い方（基本）
```html
<button class="uk-button uk-button-default" uk-toggle="target: #modal-example">モーダルを開く</button>

<div id="modal-example" uk-modal>
  <div class="uk-modal-dialog uk-modal-body">
    <h2 class="uk-modal-title">モーダルタイトル</h2>
    <p>モーダルの本文テキスト。</p>
    <p class="uk-text-right">
      <button class="uk-button uk-button-default uk-modal-close">閉じる</button>
    </p>
  </div>
</div>
```

## ポイント
- `uk-toggle` の `target:` で表示対象の要素を指定する。
- `.uk-modal-close` を持つ要素は自動的にモーダルを閉じるトリガーになる。
- モーダル内部は任意のコンテンツ（フォームや画像など）を置ける。

## アクセシビリティ
フォーカストラップやキーボード操作が標準でサポートされていることを確認し、必要に応じてラベル（`aria-*`）を付与してください。

