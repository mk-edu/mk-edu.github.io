---
layout: app
app: sleeplit
lang: en
title: Sleeplit
permalink: /apps/sleeplit/en/
icon: /apps/sleeplit/icon.png
---
<!-- このファイルは Sleeplit のリポジトリの scripts/sync_support_site.py が書き出す。直接編集しない -->
{% assign app = site.data.apps | where: "slug", page.app | first %}

# Sleeplit

An alarm that never shows an ad when you stop it, and a clean way to look back on your sleep in Apple Health.

- Last night’s sleep time, stages (awake, REM, core, deep) and vitals during sleep on one screen
- Built on the iOS 26 alarm system (AlarmKit), so it rings even in Silent mode or with a Focus on
- Weekly, monthly and yearly trends, and how your bedtime and wake-up differ on weekdays and days off
- Widgets for the Home Screen and Lock Screen
- No account needed. Your sleep data never leaves your iPhone

Requires iOS 26 or later on iPhone. Available in English and Japanese.

{% if app.app_store_url %}<a class="btn" href="{{ app.app_store_url }}">View on the App Store</a>{% endif %}
