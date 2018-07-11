# eslint-plugin-import-order-alphabetical

[eslint-plugin-import/order](https://github.com/benmosher/eslint-plugin-import/blob/37554fe98/docs/rules/order.md), but with alphabetical sorting. Based on [this PR](https://github.com/benmosher/eslint-plugin-import/pull/1105). Because [this one](https://github.com/benmosher/eslint-plugin-import/pull/629) seems to be going nowhere and doesn't even have autofixing.

Note: the autofixing doesn't always work. But it's better than nothing! :)

PRs very welcome. And even better if we could get this back into [eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import), of course.


## Usage

```sh
$ npm install --save-dev eslint-plugin-import-order-alphabetical
or
$ yarn add --dev eslint-plugin-import-order-alphabetical
```

Then in your `.eslintrc.js`:

```js
plugins: ["eslint-plugin-import-order-alphabetical"],
rules: {
  "import-order-alphabetical/order": "error",
},
```

For more detailed options, see [eslint-plugin-import/order](https://github.com/benmosher/eslint-plugin-import/blob/37554fe98/docs/rules/order.md).
