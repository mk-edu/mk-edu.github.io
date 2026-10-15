# mk-edu.github.io

GitHub Pages（Jekyll）のサイト。アプリのサポートページとプライバシーポリシーを置く。

```
/                          ホーム（_data/apps.yml からアプリを並べる）
/apps/<slug>/              アプリの概要
/apps/<slug>/support/      サポート（お問い合わせ・よくある質問）
/apps/<slug>/privacy/      プライバシーポリシー
/app-ads.txt               AdMob の認定販売者（ルートに置く決まり）
```

- 見た目は `_layouts/` と `assets/css/site.css`。アプリのページは `layout: app` と `app: <slug>` を書く
- アプリを足す：`_data/apps.yml` に1件足し、`apps/<slug>/` に `index.md`・`support.md`・`privacy.md`・`icon.png` を置く
- Sleeplit の `support.md`・`privacy.md`・`icon.png` は、アプリのリポジトリの `scripts/sync_support_site.py` で書き出す（原稿はアプリのリポジトリの `docs/store/`）
- 一度公開した URL（とくに privacy/）は、アプリと App Store Connect に登録されるので変えない
