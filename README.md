# 『設計を数える』記事原稿

ソフトウェア設計についての考え方をまとめる、Zennの記事管理用リポジトリです。

## 原稿

| 章 | 原稿 | 役割 |
| --- | --- | --- |
| 1 | [設計とは何か：変更を局所化し、どこまでやるかを決める](articles/design-change-locality.md) | 期待できる効果と投資から、今はやらない範囲も決める |
| 2 | [設計品質を、速さで見る](articles/taguchi-toc-design-view.md) | 速さを物差しにし、式で条件や見積もりを共有する |
| 3 | [設計案は、捨てた理由まで比べる](articles/design-alternatives-and-weights.md) | 同じ条件で案を比べ、重みと採否の理由を残す |

第1章は本文完成済み、第2・3章は初稿を作成済みです。全記事を `published: false` にしています。ZennとのGitHub連携や記事の公開は、ご本人の原稿確認後に進めます。

- [全7章の制作TODO](TODO.md)
- [投稿前の確認メモ](投稿前メモ.md)

原稿内の記事間リンクは、このリポジトリで読むための相対リンクです。公開時に実際のZenn記事URLへ置き換えます。

## プレビュー

Node.js 22.12.0以上を使用します。初回は依存パッケージをインストールします。

```sh
npm ci
```

次のコマンドでプレビューを起動し、表示されるURLをブラウザーで開きます。

```sh
npm run preview
```

記事を追加する場合：

```sh
npm run new:article
```

## ファイルの配置

- `articles/`：記事のMarkdown原稿
- `books/`：今後、本を作成する場合の原稿
- `TODO.md`：連載の章立てと制作状況
- `投稿前メモ.md`：原稿の意図と公開前後に確認すること

## 参考

- [Zenn CLIの導入](https://zenn.dev/zenn/articles/install-zenn-cli)
- [Zenn CLIで記事・本を管理する](https://zenn.dev/zenn/articles/zenn-cli-guide)
