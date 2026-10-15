# Zennの記事原稿

ソフトウェア設計についての考え方をまとめる、Zennの記事管理用リポジトリです。

## 原稿

- [設計とは何か：処理をまとめ、変更を局所化する](articles/design-change-locality.md)
- [投稿前の確認メモ](投稿前メモ.md)

現在の記事は編集中の下書きです。`published: false` に設定しています。ZennとのGitHub連携や記事の公開は、内容を確認してから行います。

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
- `投稿前メモ.md`：構成と公開前後に確認すること

## 参考

- [Zenn CLIの導入](https://zenn.dev/zenn/articles/install-zenn-cli)
- [Zenn CLIで記事・本を管理する](https://zenn.dev/zenn/articles/zenn-cli-guide)
