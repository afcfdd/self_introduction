# self_introduction

Notion の自己紹介ページをもとに作り直した、Hugo ベースのシンプルなプロフィールサイトです。

## Structure

- `hugo.toml`: Hugo 設定
- `content/_index.md`: プロフィール本文データ
- `layouts/_default/baseof.html`: ベースレイアウト
- `layouts/index.html`: トップページテンプレート
- `static/css/main.css`: スタイル
- `static/js/main.js`: モバイルメニューと表示アニメーション
- `static/images/profile.png`: プロフィール画像
- `.github/workflows/hugo.yml`: GitHub Pages デプロイ

## Local preview

Hugo が入っていれば以下で確認できます。

```bash
hugo server
```

## Deployment

`main` へ push すると GitHub Actions が `public/` を生成し、GitHub Pages にデプロイします。
