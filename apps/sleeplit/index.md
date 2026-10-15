---
layout: app
app: sleeplit
title: Sleeplit
permalink: /apps/sleeplit/
icon: /apps/sleeplit/icon.png
---
<!-- このファイルは Sleeplit のリポジトリの scripts/sync_support_site.py が書き出す。直接編集しない -->
{% assign app = site.data.apps | where: "slug", page.app | first %}

# Sleeplit

止めても広告が出ない目覚ましと、ヘルスケアの睡眠を見やすく振り返るグラフのアプリです。

- 昨夜の睡眠時間と段階（覚醒・レム・浅い・深い）、睡眠中のバイタルを1つの画面で
- iOS 26 の目覚まし機能（AlarmKit）で、サイレントモードや集中モードの間も鳴る
- 週・月・年の推移、平日と休日の就寝・起床のズレ
- ホーム画面とロック画面のウィジェット
- アカウント登録なし。睡眠のデータは iPhone の外に送りません

iOS 26 以降の iPhone に対応しています。

{% if app.app_store_url %}<a class="btn" href="{{ app.app_store_url }}">App Store で見る</a>{% endif %}
