# @fandhe-ai/shared-config-typedoc

TypeDoc（API ドキュメント生成）の共有設定。

## エクスポート

| パス | 説明 |
|------|------|
| `@fandhe-ai/shared-config-typedoc/base` | packages strategy ベースの TypeDoc 設定 |

## 使用方法

`typedoc.json` で `extends` に指定する:

```json
{
  "$schema": "https://typedoc.org/schema.json",
  "extends": ["@fandhe-ai/shared-config-typedoc/base"]
}
```

## 開発

### セットアップ

```bash
pnpm install
```

### コミット規約

[Conventional Commits](https://www.conventionalcommits.org/ja/) を採用。
[commitlint](https://commitlint.js.org/) + [lefthook](https://github.com/evilmartians/lefthook) により自動検証。

```
<type>: <description>

# 例
feat: 新しいルールを追加
fix: 設定の不具合を修正
chore: 依存関係を更新
```

## ライセンス

Copyright © Fandhe Inc.
