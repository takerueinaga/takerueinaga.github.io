# GitHub Pages Starter

これは `github.io` で公開しやすい、ビルド不要の静的サイトです。

## いちばん短い公開手順

1. GitHubで `<あなたのGitHubユーザー名>.github.io` という名前のリポジトリを作る
2. このフォルダの中身をそのリポジトリへpushする
3. GitHubのリポジトリで `Settings` -> `Pages` を開く
4. `Build and deployment` の `Source` を `Deploy from a branch` にする
5. `Branch` で `main` または `master`、フォルダは `/root` を選ぶ
6. 少し待って `https://<あなたのGitHubユーザー名>.github.io/` を開く

GitHub公式ドキュメントによると、GitHub Pagesは `index.html`、`index.md`、`README.md` のいずれかを入口ファイルとして探します。このスターターでは `index.html` を使っています。

## よく差し替える場所

- `index.html` の `Your Name`
- `index.html` の自己紹介文
- `index.html` の `GitHub`、`X`、`Email` リンク
- `assets/hero.png`

## メモ

`.nojekyll` を置いているので、GitHub Pages上でJekyllの処理を避け、静的ファイルを素直に配信できます。
