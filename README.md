# Portfolio

下田謙成の個人ポートフォリオサイト。GitHub Pages でホスティング。

## 公開URL

`https://kensei-shimoda.github.io/portfolio/`

## ページ構成

- **index.html** — トップページ
  - About / Skills / Experience
  - Contact（メール・GitHub）
- **projects.html** — プロジェクト一覧
  - Blog（ゼミ活動の記事）
  - Web App（Flet 製アプリ）
  - Wandervogel（Coming soon）

## ファイル構成

```
portfolio/
├── index.html
├── projects.html
├── style.css
└── README.md
```

## 主な機能

- ドロップダウンナビゲーション（TOP / Projects / Contact）
- プロジェクトカードのホバー拡大アニメーション
- ページ右下の「トップへ戻る」ボタン
- 各ページ・記事カードの公開日／最終更新日表示

## デプロイ手順

1. このリポジトリを GitHub に push する
2. リポジトリの **Settings → Pages** を開く
3. Source を `Deploy from a branch` に設定
4. Branch を `main` / `(root)` に設定して Save
5. 数分後に公開URLで反映される

## カスタマイズ

- プロフィール情報: `index.html` の About / Skills / Experience を編集
- 連絡先: `index.html` / `projects.html` のフッター（メール・GitHub）を編集
- プロジェクト: `projects.html` の各カテゴリ・カードを追加／編集
- デザイン: `style.css` を編集
- 公開日・最終更新日: 各ページフッターの `.site-dates` を更新
