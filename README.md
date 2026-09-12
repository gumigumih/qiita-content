# Qiita content

このレポジトリは、親レポジトリ`gumigumih/articles`からサブモジュールとして利用するQiita用コンテンツです。

- 記事: `public/`
- 設定: `qiita.config.json`
- 公開ワークフロー: `.github/workflows/publish.yml`

```bash
npm install
npm run preview
npm run new -- <記事のファイル名>
npm run publish -- <記事のファイル名>
```
