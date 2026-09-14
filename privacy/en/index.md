---
layout: default
lang: en
title: DueStuff Privacy Policy
description: What DueStuff keeps on your device, what goes to Google and when, and how to delete your account.
---

# DueStuff Privacy Policy

**Last updated:** 14 September 2026  
**Developer:** md7developgroup  
**Contact:** support@duestuff.com  
**Русская версия:** [duestuff.com/privacy/](/privacy/)

## 1. In short

- DueStuff keeps your items, warranties, receipts, documents and subscriptions **on your
  device**. We run no servers of our own and hold no copy of your catalogue.
- **An account is required.** Sign-in is provided by Google (Firebase Authentication).
  We receive your email address and a technical account ID from it. We never see your
  password.
- **A picture goes to Google only when you ask** — when you ask the app to recognise an
  item, a receipt or a screenshot of your subscriptions.
- **DueStuff Pro is sold by Google Play.** Card details never reach us.
- The app has no ads, no analytics, no tracking and does not sell data.

By using the app you confirm that you have read this policy. If you do not agree with it,
do not use the app and delete your account (section 10).

## 2. Who we are and what this policy covers

"We" means the developer of the app, **md7developgroup**. This policy covers the DueStuff
app for Android (`com.md7developgroup.duestuff`) and the pages at `duestuff.com`.

For account data we are the controller: we decide why it is needed. Google processes it
on our behalf as a service provider. We are not the controller of the catalogue on your
device: we never receive it and cannot read, change or restore it.

## 3. What data exists and where it lives

### 3.1. What you enter — on the device only

- items: name, manufacturer, model, serial number, notes, room, category;
- purchase dates, warranty periods, prices and currency;
- item photos, receipt pictures, warranty cards, PDF documents;
- maintenance tasks;
- subscriptions: service, amount, period, billing date, management page link, payment
  method and a short label for it ("Kapital, salary card").

This data is not sent to us or anyone else. It can leave the device only through your own
action: exporting a backup, sending a claim or inventory file through "Share", or sending
a picture for recognition (section 3.3).

**Card numbers are never stored, and there is no field for them.** The payment method is
picked from a list. Its label is checked: a string with twelve digits in a row is not saved,
neither on input nor when restoring a backup. The app does not connect to banks and cannot
see your accounts.

### 3.2. Your account — with Google (Firebase Authentication)

Sign-in with email and password, or with a Google account.

What the sign-in service receives:
- **your email address**;
- **your password** — when you sign in with email. Google stores it in protected form;
  we cannot see it and it is never passed to us;
- **a technical account ID** (user ID) assigned by Firebase;
- with Google sign-in — the details Google passes at sign-in: your email address, and it
  may also pass your name and profile photo link. The app does not use or display the name
  or photo;
- **IP address and app and system details** (SDK version, user agent string) — Google
  collects these itself to protect sign-in from abuse. Google's protection against
  automated sign-ups is built into the sign-in service for the same purpose.

What is **not** sent with the account: items, receipts, documents, subscriptions, backups.
There is no sync between devices. On another phone with the same email the catalogue will
be empty.

The first sign-in needs the internet. After that the app remembers you and works offline.

### 3.3. Picture recognition — Google Gemini via Firebase AI Logic

A picture goes online **only when you** tap "recognise" or pick a screenshot in "Import
subscriptions from a screenshot". What is sent:

- **a reduced copy of the picture** — about 1000 pixels on the long side. The full-size
  image stays on the phone;
- the request text, your list of categories, the language and the default currency;
- technical details added by Google's SDK: app installation ID, app authenticity token
  (App Check), model name, app and SDK versions.

Your name, email address and the rest of your catalogue are not included in the request.

The model works out what the picture shows: an item (name, make, model), a receipt (shop,
date, total, text) or a list of subscriptions (services, amounts, periods, dates). You see
the result, and only what you save goes into the catalogue.

**What Google does with the picture after receiving it is determined by Google** — the
[Gemini API terms](https://ai.google.dev/gemini-api/terms) and the
[Firebase data processing terms](https://firebase.google.com/terms/data-processing-terms).
Depending on the terms of service, Google may retain requests, use them to improve its
products and show them to human reviewers. We do not control processing on Google's side
and are not responsible for it.

**Do not send for recognition anything you are not prepared to share with Google:** people's
faces, identity documents, card numbers, medical or other sensitive information, other
people's personal data. If a screenshot shows more than needed, crop it before sending.
Recognition is optional: any card can be filled in by hand.

Recognition does not work offline, after the daily allowance is used up, or when the
service is unavailable. The fiscal QR code on a receipt is read on the device itself
(the ZXing library), and no picture is sent for that.

### 3.4. DueStuff Pro subscription — Google Play

The subscription is sold by **Google Play**. Payment, receipts, renewal, refunds and
cancellation are handled by Google under [its own terms](https://play.google.com/about/play-terms/).
Card details never reach the app in any form.

The device keeps only what the plan needs to work: whether a subscription is active, its
type (monthly or yearly), whether it is a trial and will renew, and the expected billing
date. These records are never sent anywhere.

### 3.5. Notifications

Reminders are scheduled and shown on the device. Their text — the item or service name
and a date — is never sent anywhere.

### 3.6. What is not there

The app has no ads, analytics, crash reporting, cross-app tracking or third-party trackers.
We do not request location, contacts, microphone, calls, SMS, calendar, files outside the
app or the list of installed apps. We do not sell or rent out data.

## 4. Why and on what legal basis

| Data | Why | Legal basis |
|---|---|---|
| Email, password, account ID | sign-in, password reset, account deletion | performance of a contract with you — the app does not work without an account |
| IP address, app and system details | protecting sign-in and recognition from abuse | legitimate interest — security of the service |
| Picture and request details | recognition at your request | your request (performance of a contract); sending is optional |
| Installation ID, App Check token | confirming that the request came from the genuine app | legitimate interest — preventing others from using up the quota |
| Pro subscription details | unlocking paid features | performance of a contract |

We make no automated decisions with legal effects for you. A recognition result is a
suggestion that you check and save yourself.

## 5. Who receives the data

Only **Google**, as the provider of the services listed above: Firebase Authentication,
Firebase App Check, Firebase AI Logic and the Gemini API, Google Play. Google may use its
own subprocessors under its own terms.

In addition, we may disclose account data where required by law, a court order or a request
from a competent authority, or to protect our rights and the safety of users and the
service. All we hold is what Google's sign-in service stores: there is no catalogue on our
servers, so we cannot disclose it.

A file that you sent through "Share", saved to a cloud or gave to a seller or an insurer is
then governed by the recipient's rules, not by this policy.

## 6. International transfers

Google's servers are located in various countries, including the United States. By sending
a picture for recognition and using an account, you understand that data may be processed
outside your country. Google applies its own safeguards for this, such as standard
contractual clauses.

## 7. Retention

- **The catalogue on the device** — until you delete it, the account or the app.
- **The account** — until you delete it. After deletion the record is erased from the
  sign-in service.
- **Google's service logs** (IP addresses, requests) — for the periods set by Google.
  We have no influence over them.
- **Pictures sent for recognition** are not stored by us: we never have them. Retention on
  Google's side is governed by its terms (section 3.3).

## 8. Security

Data is sent to Google over a secure connection (HTTPS). Android automatic backup is turned
off for the app: data snapshots do not go to Google Drive without your knowledge. Documents
open inside the app and are not handed to other apps until you send them yourself.

**No method gives complete protection.** The catalogue lives on the phone, so its safety
also depends on you: screen lock, a strong password, system updates and who holds the
phone. We are not responsible for access to data through your unlocked or compromised
device, someone else's access to your email, a weak or reused password, or backups and
files you have taken out of the app.

## 9. Your rights

You can:

- **access and obtain** the account data we hold (email address and account ID);
- **rectify** it — you can use a different email by creating a new account;
- **delete** your account and data (section 10);
- **object to** and **restrict** processing — in practice this means deleting the account,
  because the app does not work without one;
- **withdraw consent** to recognition — simply do not send pictures;
- **lodge a complaint** with the data protection authority of your country.

You view, edit, export and delete the catalogue on your device yourself — we have no access
to it, so requests about it are not directed to us.

Send requests to **support@duestuff.com** from the address the account is registered with.
We reply within 30 days. To protect the account from requests by others, we may ask you to
confirm that the address is yours and may refuse if this cannot be confirmed.

## 10. Deleting your account and data

### From the app

"Settings → Profile → Delete account". The app asks you to confirm it is you: with your
password if you sign in with email, or by choosing the account in the system sheet if you
sign in with Google.

After confirmation:

- the account record is deleted from Google's sign-in service together with the email
  address and password;
- items, warranties, pictures, documents, subscriptions, maintenance tasks, rooms and
  categories are erased from the phone; settings return to first launch.

**Deletion is irreversible, and there is nowhere to restore data from** — we have no copy.
If you need the catalogue, export a backup first: "Settings → Backup → Save a backup".

**Deleting the account does not cancel DueStuff Pro.** Cancel it in Google Play: "Profile →
Payments & subscriptions → Subscriptions". Otherwise Google will keep charging you.

### Without the app

If you cannot sign in — for example, the phone is lost — open
**https://duestuff.com/delete-account/** or write to **support@duestuff.com** from the account
address. We will delete the account record within 30 days. The data on the phone itself will
remain: we have no access to it. Uninstalling the app removes it.

### Uninstalling the app

Uninstalling erases all app data from the device but **does not delete the account** and
**does not cancel the subscription**. Use the methods above for that.

## 11. Permissions

| Permission | Why |
|---|---|
| Camera | photograph an item or a receipt; asked when you take a picture |
| Notifications | warranty, maintenance and billing reminders; asked when you set up reminders |
| Internet | sign-in, picture recognition, talking to Google Play about the subscription |
| In-app purchases | buy and check the subscription through Google Play |
| Run at startup and prevent sleep | restore reminders after the phone restarts; never asked from the user and give no access to data |

Camera and notifications are optional. Without them the app works, losing the matching
feature.

## 12. Children

The app is not intended for children under 13, and we do not knowingly collect their data.
Where the law sets a higher age of consent to data processing (for example, up to 16 in some
EU countries), the app may be used only with the consent of a parent or legal guardian.
If you learn that a child has created an account, write to us and we will delete it.

## 13. What you are responsible for

- **Pictures and files you upload.** You must have the right to use them. Do not send other
  people's personal data for recognition without a legal basis.
- **Accuracy of the catalogue.** Recognition makes mistakes: check names, dates, amounts and
  periods before saving. What you save, you confirm yourself.
- **Keeping your data safe.** The catalogue is stored only on the phone. A lost, reset or
  broken phone, or a deleted app or account, means a lost catalogue unless you have a backup.
  Export backups yourself and keep them somewhere safe.
- **Deadlines and money.** The app is an assistant, not a guarantor. Warranty and billing
  dates that you missed, cancelled or did not check remain your responsibility.

## 14. Limitation of liability

To the extent permitted by applicable law:

1. The app is provided **"as is"** and **"as available"**. We do not promise that it will
   work without interruptions or errors, suit a particular purpose, or that recognition
   results will be accurate and complete.
2. **Reminders are not guaranteed.** Android may delay or not show a notification: battery
   saving, blocked notifications, a restart, a settings reset, uninstalling the app. We are
   not liable for a missed warranty, return, maintenance or billing deadline.
3. **Documents are for reference.** The warranty claim file and the home inventory are built
   from what you entered. We do not promise that a seller, manufacturer, insurer, court or
   any other body will accept them. The app does not provide legal, financial, tax or
   insurance advice.
4. **Third-party services.** The owners of Google services (Firebase, Gemini, Google Play),
   and of apps and websites you go to or send files to, are responsible for their operation,
   availability, terms and data processing. You enter subscription management links yourself,
   and we do not check their content.
5. **Loss of data.** We are not liable for loss of the catalogue, attachments or backups —
   the data is stored on your device and we have no copy.
6. **Indirect damages.** We are not liable for lost profits or for indirect, incidental or
   punitive damages related to using or being unable to use the app.
7. **Cap.** If liability nevertheless arises, it is limited to the amount you paid for
   DueStuff Pro in the 12 months before the event, or zero if you paid nothing.
8. **Features and limits change.** We may change features, free limits and the daily
   recognition allowance, and suspend or discontinue individual features or the app. The
   terms of a paid subscription period stay in force until it ends; prices for the next
   period change under Google Play rules.
9. Nothing in this policy limits rights that, under the law of your country, cannot be
   limited or waived by contract.

## 15. Changes to this policy

We may change this policy. A new version is published at this address with a new date at the
top and applies from publication. We will announce material changes — new types of data or
new recipients — in the app or in the Google Play release notes. By continuing to use the app
after changes, you accept the new version; if you do not agree, delete your account
(section 10).

If the Russian and English versions differ, the Russian version prevails.

## 16. Contact

Questions about the app, this policy and your data — **support@duestuff.com**.
