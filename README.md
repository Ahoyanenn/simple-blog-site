# 現場道具ラボ

建設業・職人向けの現場道具レビューサイトです。HTML/CSS/JavaScriptのみで構成しているため、Netlifyの無料プランで静的サイトとして公開できます。

## ファイル構成

```text
.
├── index.html              # トップページ
├── categories.html         # カテゴリ一覧ページ
├── safety-shoes.html       # 安全靴おすすめページ
├── airwear.html            # 空調服おすすめページ
├── waist-tools.html        # 腰道具おすすめページ
├── heat-goods.html         # 暑さ対策グッズページ
├── cleaning-tools.html     # 新築美装・清掃道具ページ
├── assets/
│   ├── css/style.css       # 共通デザイン
│   └── js/main.js          # スマホメニュー・トップへ戻るボタン
└── README.md
```

## Netlifyにアップロードするファイル

Netlifyで公開するときは、リポジトリ直下の以下をまとめてアップロードしてください。

- `index.html`
- `categories.html`
- `safety-shoes.html`
- `airwear.html`
- `waist-tools.html`
- `heat-goods.html`
- `cleaning-tools.html`
- `assets/` フォルダ一式

ドラッグ＆ドロップで公開する場合は、このプロジェクトフォルダ全体をZIP化するか、上記ファイルと `assets` フォルダを同じ階層のままアップロードしてください。`README.md` は公開に必須ではありません。

## アフィリエイトリンクの差し替え

各ページにある「Amazonで見る」「楽天で見る」ボタンの `href="#"` を、Amazonアソシエイトや楽天アフィリエイトで発行したURLに差し替えてください。
