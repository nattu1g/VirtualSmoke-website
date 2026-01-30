# VirtualSmoke Website

VirtualSmokeアプリのランディングページです。

## ローカルで確認

```bash
# Python 3
python3 -m http.server 8000

# または npx
npx serve .
```

ブラウザで http://localhost:8000 を開く

## デプロイ

### Netlify
1. [Netlify](https://netlify.com) にログイン
2. 「Add new site」→「Import an existing project」
3. GitHubリポジトリを選択
4. デプロイ設定はデフォルトでOK

### Vercel
1. [Vercel](https://vercel.com) にログイン
2. 「New Project」→ GitHubリポジトリを選択
3. フレームワークは「Other」を選択
4. デプロイ

## ディレクトリ構成

```
website/
├── index.html      # メインページ
├── privacy.html    # プライバシーポリシー
├── terms.html      # 利用規約
├── css/
│   └── style.css   # スタイル
├── js/
│   └── main.js     # JavaScript
└── images/
    ├── app-mockup.png      # アプリ画像
    └── app-store-badge.svg # App Storeバッジ
```
