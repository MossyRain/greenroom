# GREENROOM

Safariで使える、観葉植物の管理アプリです。植物ごとの日照・水やり・植え替え・置き場所・写真・お世話履歴を管理します。

## GitHub Pagesで公開

1. GitHubで `greenroom` というリポジトリを新規作成します。
2. このフォルダの `index.html` と `README.md` をリポジトリのルートへアップロードし、コミットします。
3. リポジトリの **Settings → Pages** で、**Build and deployment → Deploy from a branch** を選びます。
4. **Branch: main / Folder: /(root)** を選んで **Save** します。
5. 公開後、`https://<GitHubユーザー名>.github.io/greenroom/` にアクセスします。

公開リポジトリの GitHub Pages は誰でも閲覧可能です。秘密の個人情報をリポジトリに置かないでください。

## データについて

- 登録情報・写真・お世話履歴は、アクセスしているブラウザの `localStorage` に保存されます。
- GitHubには自動で保存されず、端末間で自動同期もしません。
- HTMLファイルを直接開いていたときのデータは、GitHub PagesのURLには自動で移行しません。以前の画面でJSONバックアップを書き出し、公開サイト上で読み込んでください。
- サイトのURLやGitHubのリポジトリ名を変更すると、ブラウザ保存領域が変わる可能性があります。バックアップを定期的に取ってください。
- 写真が多いとブラウザ保存容量の制限に達する場合があります。

## ファイル構成

- `index.html`: アプリ全体（HTML/CSS/JavaScript）。インストールやビルドは不要です。
- `README.md`: 設置と運用の説明。
