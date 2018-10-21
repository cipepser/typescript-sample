# typescript-sample

TypeScriptの勉強用。

## [初心者が学ぶ TypeScript 入門 Ver.1.0](https://qiita.com/ikkitang/items/9acaf6a166f771e5ce6f)

この記事のとおりに触ってみる。

* コンパイル: `node_modules/.bin/tsc`
* 実行: `node src/app.js`

### packages

途中で[AtomでTypeScriptの環境を構築する](https://qiita.com/Sugima/items/113eb16f14ca1e9a6d0f)をもとに以下パッケージを導入。

* atom-typescript
* linter-tslint

※記事とは異なり、AtomのSettings - Installから検索してインストールした。

### if文

`if`は`bool`じゃなくてもコンパイルできる。

```ts
let value: number = 0;
if (value) {
  console.log("defined")
} else {
  console.log("undefined")
}
```

実行結果。

```sh
❯ node src/app.js
undefined
```

ちなみに、`value = 1`も試したら`defined`になったので、Cっぽい感じみたい。


## References
* [初心者が学ぶ TypeScript 入門 Ver.1.0](https://qiita.com/ikkitang/items/9acaf6a166f771e5ce6f)