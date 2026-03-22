# self_introduction

Notion の自己紹介ページをもとに作り直した、ビルド不要の静的サイトです。

## Files

- `index.html`: ページ本体
- `style.css`: レイアウトとデザイン
- `script.js`: モバイルメニューとスクロール時の表示アニメーション
- `assets/profile.png`: プロフィール画像

## Preview

ローカル確認:

```bash
python3 -m http.server 8000
```

その後、`http://localhost:8000` を開きます。

## GitHub Pages

1. GitHub で新しいリポジトリを作る
2. このディレクトリで以下を実行する

```bash
git init
git add .
git commit -m "Initial profile site"
git branch -M main
git remote add origin <YOUR_REPOSITORY_URL>
git push -u origin main
```

3. GitHub の `Settings > Pages` を開く
4. `Build and deployment` の `Source` で `Deploy from a branch` を選ぶ
5. `main` ブランチの `/ (root)` を選んで保存する

数分後に GitHub Pages の URL で公開されます。
