# 福祉でつながる加茂 試用版

## ローカル試用
`index.html`をブラウザで開きます。

- ID: `demo`
- パスワード: `kamo2026`

## Azure Static Web Apps 公開
1. このフォルダー一式をGitHubのprivateリポジトリのmainブランチへ配置します。
2. Azure PortalでStatic Web Appsを作成し、そのリポジトリとmainブランチを指定します。
3. Azureが作成したデプロイトークンをGitHub Actions secret `AZURE_STATIC_WEB_APPS_API_TOKEN` に登録します。
4. GitHub Actions実行後、Azure画面に表示されるURLを共有します。

## 注意
この版は静的デモです。簡易ログインは本格認証ではなく、データは各ブラウザのlocalStorageに保存されます。利用者個人情報は入力しないでください。
