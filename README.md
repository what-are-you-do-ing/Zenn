# Zenn — Whatcha 公式

[Whatcha](https://whatareyoudo.ing/?utm_source=github&utm_medium=readme&utm_campaign=web100)（夫婦・家族で書く共有日記）の技術記事置き場。
zenn.dev の GitHub 連携でこのリポジトリを公開している。

- `articles/<slug>.md` が1記事。slug は `a-z0-9_-` の12〜50文字。
- frontmatter の `published: true` で公開、`false` で下書き。
- 記事の原稿は `memo` リポジトリの `API/notes-whatcha/` 側で書き、ここへ出力する。

```bash
npx zenn preview   # ローカルプレビュー
```
