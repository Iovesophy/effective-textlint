# effective-textlint

textlint に関してよく使うルールをまとめる、個人的なメモ

## Rules

- 日本語と English の間にスペースを入れる

[textlint-rule-ja-space-between-half-and-full-width](https://github.com/textlint-ja/textlint-rule-preset-ja-spacing/tree/master/packages/textlint-rule-ja-space-between-half-and-full-width)

```ルール
  "rules": {
    "ja-space-between-half-and-full-width": {
      "space": "always"
    }
  }
```

- 自動修正

```bash
textlint --fix README.md
```

