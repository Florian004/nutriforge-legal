---
layout: default
title: privacy-policy-en
---

<!--
DRAFT — not legal advice. Please have it reviewed by a lawyer (or a service
such as eRecht24/iubenda) before going live. This is an English translation
of the German privacy policy; the German version at
https://florian004.github.io/nutriforge-legal/privacy-policy.html is the
authoritative one.
-->

# Privacy Policy — NutriForge

Last updated: 12 July 2026

## 1. Controller

Florian Selinger
Stavenhagenstr. 5A
07973 Greiz
Germany
Email: florianselinger82@gmail.com

## 2. What data we process

### 2.1 Account and profile data
When you use NutriForge, you create a user account (anonymously or via Google/
Apple Sign-In). During onboarding we collect: age, gender, height, body
weight, activity level, training experience and your goal (lose/maintain/gain).
This data is stored locally on your device and — if you are signed in —
additionally backed up in our cloud database (Google Firebase/Firestore) so
you don't lose it when you change devices.

### 2.2 Nutrition and training data
Logged meals, calorie and macronutrient values, water intake, training plans,
workout history, weight history, and — if you use the intermittent fasting
feature — your fasting periods (start, end, chosen fasting window; these are
stored exclusively locally on your device). This data qualifies as health data
under the GDPR (Art. 9) and is protected accordingly; it is processed on the
basis of your consent (Art. 9(2)(a) GDPR).

### 2.3 Photos for AI analysis
When you use the food scan feature, the captured or selected photo is sent to
our servers (Firebase Cloud Functions) and from there to the Google Gemini API
for image recognition. The photo is processed solely for the analysis and is
not permanently stored on our servers.

### 2.3a Messages to the nutrition coach
When you use the AI nutrition coach (chat), your messages and the previous
chat history are sent to our servers (Firebase Cloud Functions) and from there
to the Google Gemini API to generate a response. The messages are processed
solely to answer you and are not permanently stored on our servers.

### 2.3b Apple Health / Google Health Connect
If you enable the Health integration in the profile settings, we write your
weight, your logged meals (name, calories, macronutrients) and completed
workouts to Apple Health or Google Health Connect on your device. This data
remains in the device-local health database provided by Apple/Google and is
not additionally stored on our servers. You can revoke access at any time in
the iOS Health or Android Health Connect settings, or directly in the app.

### 2.4 Sign-in data
When you sign in with Google or Apple, we receive your email address and
possibly your name from these services to uniquely identify your account. With
"Sign in with Apple" you can optionally use an email address relayed/hidden by
Apple.

### 2.5 Purchase data
Subscription purchases are handled via RevenueCat. This processes purchase
receipts and a pseudonymous user ID, but no payment data (credit card, etc.) —
that remains with Apple/Google.

### 2.6 Technical data / crash reports
We use Firebase Crashlytics to detect and fix app crashes. This transmits
device information, the app version and crash logs.

### 2.7 Food database
For the barcode search we query the open Open Food Facts database. Only the
scanned barcode is transmitted, no personal data.

## 3. Purpose and legal basis of processing

- Providing the app's features (performance of a contract, Art. 6(1)(b) GDPR)
- Health-related data (nutrition/training/weight) on the basis of your explicit
  consent (Art. 9(2)(a) GDPR)
- Error analysis and improvement of the app (legitimate interest,
  Art. 6(1)(f) GDPR)
- Handling of subscriptions (performance of a contract)

## 4. Recipients / processors

- Google Firebase (Authentication, Firestore, Cloud Functions, Crashlytics)
  — Google Ireland Ltd. / Google LLC
- Google Gemini API — for image analysis of food photos
- RevenueCat Inc. — subscription management
- Open Food Facts — product database queries
- Apple Inc. / Google LLC — when using "Sign in with Apple/Google"

Where required, data processing agreements pursuant to Art. 28 GDPR are in
place with the providers named above.

## 5. Transfers to third countries

Some providers (in particular Google/Firebase, Apple) also process data
outside the EU/EEA, e.g. in the USA. We ensure that appropriate safeguards are
in place for this (e.g. EU standard contractual clauses).

## 6. Retention period

Your data is stored for as long as your account exists. You can delete your
account and all associated data at any time directly in the app under
"Profile → Permanently delete all data". Crash reports and billing data may be
retained longer for legal/technical reasons.

## 7. Your rights

You have the right to:
- Access the data stored about you (Art. 15 GDPR)
- Rectification of inaccurate data (Art. 16 GDPR)
- Erasure ("right to be forgotten", Art. 17 GDPR) — available directly in the app
- Restriction of processing (Art. 18 GDPR)
- Data portability (Art. 20 GDPR)
- Object to processing (Art. 21 GDPR)
- Withdraw consent given, with effect for the future
- Lodge a complaint with a data protection supervisory authority

Contact for all requests: florianselinger82@gmail.com

## 8. Children

NutriForge is not directed at children under the age of 16. We do not
knowingly collect data from children under 16.

## 9. Changes to this privacy policy

We may adjust this privacy policy to reflect changes in the legal situation or
new features. You can always find the current version at
https://florian004.github.io/nutriforge-legal/privacy-policy-en.html.
