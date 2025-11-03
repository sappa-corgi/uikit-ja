# コンポーネント: フォーム（Form）

フォーム要素と入力補助に関するスタイルとユーティリティを提供します。テキスト入力、チェックボックス、ラジオ、セレクトなどのスタイルが含まれます。

例:

```html
<form>
  <div class="uk-margin">
    <input class="uk-input" type="text" placeholder="名前">
  </div>
  <div class="uk-margin">
    <select class="uk-select">
      <option>選択肢1</option>
    </select>
  </div>
</form>
```

ポイント:
- `uk-form-*` 系クラスや `uk-input` / `uk-select` を使用。
- バリデーションや拡張コンポーネント（ファイル、パスワードトグルなど）と組み合わせられる。