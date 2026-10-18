# 『設計を数える』記事原稿

ソフトウェア設計についての考え方をまとめる、Zennの記事管理用リポジトリです。

## 原稿

| 章 | 原稿 | Zenn | 役割 |
| --- | --- | --- | --- |
| 1 | [どこまでやるかを決めるまでが設計](articles/design-change-locality.md) | [記事を読む](https://zenn.dev/thousandsofties/articles/design-change-locality) | 期待できる効果と投資から、今はやらない範囲も決める |
| 2 | [コストを、速さで見る](articles/design-cost-and-time.md) | [記事を読む](https://zenn.dev/thousandsofties/articles/design-cost-and-time) | コストを、測って比較できる処理時間・作業時間で捉える |
| 3 | [設計案は、捨てた理由まで比べる](articles/design-alternatives-and-weights.md) | [記事を読む](https://zenn.dev/thousandsofties/articles/design-alternatives-and-weights) | 同じ条件で案を比べ、重みと採否の理由を残す |

まずは第1〜3章で一区切りとします。３記事の本文は確認済みで、Zennへの公開設定を有効にしています（`published: true`）。第4章以降は続編候補として素材を残しています。

- [制作TODOと続編候補](TODO.md)
- [投稿前の確認メモ](投稿前メモ.md)
- [別稿の素材：設計観の背景](drafts/design-thinking-background.md)

原稿内の記事間リンクには、Zennの公開URLを使用しています。

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
- `drafts/`：現在の3章には含めない、別稿用の素材
- `TODO.md`：連載の章立てと制作状況
- `投稿前メモ.md`：原稿の意図と公開前後に確認すること

## 参考

- [Zenn CLIの導入](https://zenn.dev/zenn/articles/install-zenn-cli)
- [Zenn CLIで記事・本を管理する](https://zenn.dev/zenn/articles/zenn-cli-guide)
