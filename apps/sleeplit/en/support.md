---
layout: app
app: sleeplit
lang: en
title: Sleeplit Support
permalink: /apps/sleeplit/en/support/
icon: /apps/sleeplit/icon.png
---
<!-- このファイルは Sleeplit のリポジトリの scripts/sync_support_site.py が書き出す。直接編集しない -->
{% assign app = site.data.apps | where: "slug", page.app | first %}

# Support

Sleeplit is an alarm and a way to look back on your sleep in Apple Health (for iPhone with iOS 26 or later).

<div class="card" markdown="1">

### Contact Us

To report a problem or send a request, please use the form. If you’d like a reply, include your email address in the form.

<a class="btn" href="{{ app.support_form_url }}">Open the Contact Form</a>

</div>

## FAQ

### My alarm doesn’t ring

Tap “Allow” when you’re asked to allow alarms on first launch. To change it later, go to iPhone Settings > Apps > Sleeplit. The alarm volume follows your iPhone’s alarm volume.

### My sleep records don’t show up

Sleeplit reads Sleep from Apple Health. In the app, open the Settings tab and check Apple Health to make sure access is allowed. Apple Watch sleep records may take a while to appear in Health after you wake up.

### I changed iPhones and Premium is gone

Tap “Restore Purchases” in the app’s Settings tab. You need to be signed in with the Apple Account you used to subscribe.

### How do I cancel my subscription?

Go to iPhone Settings > your name > Subscriptions. If you cancel at least 24 hours before the end of the period, it won’t renew.

### How do I change whether ads are personalized?

Go to iPhone Settings > Privacy & Security > Tracking and change the setting for Sleeplit. If you don’t allow tracking, you’ll see non-personalized ads.
