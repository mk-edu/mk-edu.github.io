---
layout: app
app: sleeplit
lang: en
title: Sleeplit Privacy Policy
permalink: /apps/sleeplit/en/privacy/
icon: /apps/sleeplit/icon.png
---
<!-- このファイルは Sleeplit のリポジトリの scripts/sync_support_site.py が書き出す。直接編集しない -->
{% assign app = site.data.apps | where: "slug", page.app | first %}

# Sleeplit Privacy Policy

Effective date: October 15, 2026

Sleeplit (“the app”) is an iOS app for reviewing your sleep and waking you up. The app has no servers, databases or sign-in. The developer never receives your data. This policy explains what information the app handles and where it goes.

This is an English translation of the Japanese policy. If there is any difference between them, the Japanese version prevails.

## 1. Summary

- Sleep data in Apple Health is read only. The app never writes to Health and never sends this data to the developer or to advertisers.
- Alarms and settings are stored only on your device and in your own iCloud.
- Your subscription status is checked on your device using the App Store (StoreKit).
- The free version shows ads (Google AdMob). Ads are personalized to your interests only if you allow tracking (ATT). To deliver and measure ads, Google handles information about your device (Section 4). Your sleep and health data are never used for ads.

## 2. Sleep data and vitals during sleep from Apple Health

- Only if you allow it, the app reads Sleep data from the Health app (sleep time, sleep stages, bedtime and wake-up time) and vitals during sleep (heart rate, respiratory rate, wrist temperature and breathing disturbances). This includes sleep recorded by an Apple Watch or similar, your iPhone sleep schedule, and sleep recorded by other apps.
- The app only reads this data and never writes to Health.
- The data is used to calculate the charts and trends shown on screen. These calculations happen on your device each time they are shown.
- Sleep data and vitals are never sent to the developer’s servers or to any third party, and never passed to the ad SDK. Ad requests contain no sleep data, vitals or Health information.
- To show last night’s sleep in widgets (a Premium feature), some calculated results are shared between the app and its widgets on the same device (App Group). This information never leaves your device.
- You can change access at any time in the Settings app or the Health app. The alarm works even if you don’t allow access.

## 3. Alarms, settings and manual records

- The following information is stored on your device:
  - Alarms: time, label, repeat, snooze, sound, on/off, and “skip tomorrow only” status
  - Settings: theme and alarm defaults (snooze and sound)
  - Sleep records you enter manually (for when you don’t have an Apple Watch or similar)
  - A copy of your subscription status, the number of rewarded ads you have watched, and whether you have completed onboarding
- Of these, alarms and settings are also synced to your own iCloud (iCloud key-value storage) so you can keep them when you change or add devices. If you are not signed in to iCloud, they are not synced and stay only on your device.
- Data stored in iCloud is linked to your Apple Account and managed by Apple. The developer cannot see or access it.
- Sleep data read from Health and sleep records you enter manually are not synced to iCloud.
- Deleting the app deletes the data on your device. You can delete the alarms and settings stored in iCloud by managing iCloud storage in the Settings app on your iPhone.

## 4. Ads (Google AdMob)

The free version shows banner, native and rewarded ads, delivered with Google LLC’s ad SDK (Google Mobile Ads SDK).

- If you use the free version, you are asked whether to allow tracking (App Tracking Transparency) after initial setup.
- If you allow it, Google uses your advertising identifier (IDFA) and similar information to show ads based on your activity in other companies’ apps and websites.
- If you don’t allow it, only non-personalized ads are shown and your advertising identifier is not used.
- You can change this at any time in iPhone Settings > Privacy & Security > Tracking.
- Premium subscribers are not asked to allow tracking.
- In the European Economic Area (EEA), the UK and Switzerland, before showing ads the app asks for your consent to the use of information for ads, using Google’s consent management screen. You can use the app even if you don’t consent. You can change your choice at any time in the app under Settings > Ad Privacy Settings.
- The app never passes your sleep data, alarms, settings, purchase information, keywords or content URLs to the ad SDK.
- However, as part of showing ads, Google collects and uses information about your device through the ad SDK, such as your IP address, device and OS information, ad impressions and clicks (ad measurement), fraud detection, and crash and performance information. Google uses this to deliver and measure ads, prevent fraud and improve its services.
- Google’s handling of information is governed by Google’s policies:
  - Google Privacy Policy: <https://policies.google.com/privacy>
  - How Google uses information in ads: <https://policies.google.com/technologies/ads>
  - Google AdMob and data in apps: <https://support.google.com/admob/answer/6128543>
- While you have Premium, no ads are shown and the ad SDK is not started.

## 5. Purchases

- Purchases and management of Premium (monthly and yearly subscriptions) are handled by Apple. Neither the app nor the developer receives your payment details.
- Whether you have Premium is checked on your device using StoreKit, from purchase information (transactions) provided by Apple. No developer server is used.
- You can view and cancel subscriptions in iPhone Settings > your name > Subscriptions.

## 6. Information the developer collects

The app has no way for the developer to collect your information. There is no account, no analytics tool and no usage tracking of our own. The only information the developer receives is what you send through the contact form (Section 11). In App Store Connect, the developer can see aggregate figures provided by Apple (such as downloads and sales) that do not identify individuals.

## 7. Sharing with third parties

Except as required by law, the developer does not share your information with third parties. In fact, the developer does not hold your information. Apple and Google handle information for purchases and ads under their own terms (Sections 4 and 5).

## 8. Children

The app is not intended for children under 13.

## 9. Medical notice

The app is for recording and reviewing the sleep data in Apple Health. It is not intended to diagnose, treat or prevent any disease, or to improve sleep. If you have concerns about your sleep, please consult a doctor.

## 10. Changes to this policy

When this policy changes, we will update this page and add the revision date below the effective date. For significant changes, we will also let you know in the app’s update notes.

## 11. Contact

For questions about the app or this policy, including requests about your information, please use this form:

<https://docs.google.com/forms/d/e/1FAIpQLSeLV4CmdWpjvarc5icV1P8Pl4UqVVJmBF2Le1CJ7SiUtS2rWQ/viewform>

The form uses Google Forms. What you send (the type and content of your inquiry, and your email address and device information if you choose to provide them) is stored on Google’s services and used by the developer only to respond to your inquiry.

---

Effective date: October 15, 2026
