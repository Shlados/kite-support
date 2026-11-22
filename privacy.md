---
layout: default
title: Kite — Privacy Policy
permalink: /privacy/
---

# Kite — Privacy Policy

_Last updated: 21 November 2026_

Kite has accounts. You sign in with Apple or Google so your budget opens on any
phone. Kite does not ask for your bank logins, has no advertising, collects
usage analytics only if you agree, and never sells your data or shares it for
advertising or tracking.

## What Kite stores, and where

**On your phone.** Everything you enter — your pay schedule, bills, expenses,
debts and payment history — is kept in a database file inside Kite's own app
container, so Kite works without a signal.

**In your account.** So the same budget opens on any phone you sign in on, Kite
saves a copy of it to a private database hosted by Supabase, in Canada. A few
seconds after each change, the whole budget is sent over an encrypted
connection. What is stored for your account:

- a sign-in ID (a random identifier) and which provider you used, Apple or
  Google;
- your email address, if your provider shares one. Apple's Hide My Email gives
  Kite a relay address instead of your own;
- your budget: pay schedule, income, bills, expenses, debts, payments, your
  period goals and your preferences (currency, language, reminder times). Your
  app lock setting and your widget privacy setting stay on each phone and are
  not saved to the account;
- if you signed in with Apple, a token Apple issues for the sign-in, kept only
  so Kite can end the Sign in with Apple link when you delete your account (see
  below). It cannot be used to sign in.

**Who can read it.** Your budget is protected by rules in the database that let
each signed-in person read and change only their own row. Kite is not built to
read anyone's budget. I run the service, so I can technically reach the database
as its administrator; I use it to keep the service working and to answer
questions you send me, not to look through people's budgets.

## Signing in

Sign in with Apple and Sign in with Google are run by Apple and Google, who
learn that you signed in to Kite and handle that under their own privacy terms.
Kite receives a sign-in token from them and, if you allow it, your email address.
It never sees your Apple or Google password.

Your session is kept in the phone's secure storage (the iPhone Keychain, the
Android Keystore) so you stay signed in. If it ever ends without you signing
out, Kite tells you; anything you add until you sign in again stays on that
phone only.

Apple and Google accounts are separate: signing in with one does not open the
budget saved under the other.

## What leaves your device

- **Sync with your account**, as described above, whenever you are signed in
  and online.
- The **backup file**. When you tap **Save a backup**, Kite writes a JSON file
  and hands it to the phone's share sheet. Where it goes from there is your
  choice — Files or Drive, iCloud, AirDrop or Nearby Share, email. It holds your
  finances in readable form, so keep it somewhere private. Kite never sends it
  anywhere on its own.
- A **safety copy**. When a different account signs in on a phone that still
  holds another account's budget, Kite clears the phone so the two never mix. It
  first saves a copy of what was there to a file in Kite's own folder on that
  phone, so a change that never reached the old account is not lost. You can
  restore it from My account, Your data. It is kept for 30 days and removed
  sooner if you delete your account or erase all data. It never leaves the
  phone.
- **A question to Ask Kite**, only if you turn it on and ask: your question and the parts of your budget needed to answer go to Anthropic through Kite's server, as described under Ask Kite below.
- An **email you send**. **Email support** in the app opens your own mail app
  with the message started, addressed to kakodjenou@gmail.com. What you write
  reaches me, along with two lines naming the app version and your operating
  system version — nothing from your budget. Kite does not send it; your mail
  app does, when you tap send. Please do not attach a backup file.

- **Usage analytics**, only if you agree (see Usage analytics below).
- **Anonymous counts** that carry no account and no device identifier (see
  Anonymous counts below).
- **Your answer about email news**, if you are signed in (see Email news below).

Kite has no crash reporter and no advertising identifier.

**Rate Kite** opens Kite's page in the App Store or Play Store. After you have
closed a couple of end-of-period recaps, Kite may also show a short card in the
app, never less than two weeks apart: showing you how to add the widget, asking
you to share Kite, rate it, tell me how you budget with someone, or try the
purchase planner, or, if you used Kite before accounts existed and have not
signed in, asking you to sign in (once a week until you do). When you have
closed your 3rd, 6th or 12th pay period, one more card says so and offers to
share Kite; the message it prepares says how many periods you have closed and
nothing from your budget. Each card has a button and a close (×). The store
page and any rating you leave belong to Apple or Google, under their own privacy
terms. Kite never learns whether you left a rating. If you allowed usage
analytics, Kite records that you tapped Share, and nothing about where it went.

## Your period goal

At the start of a pay period Kite may ask whether you want to aim to keep a
certain amount, and shows how the period ended against it in the recap. The
amount is saved with your other preferences, on your phone and in your account,
and travels in a backup file with them.

## Checking for updates

Once a day at most, Kite asks this website for a small file that lists the
latest version number for iOS and Android. If it says a newer version exists
than the one installed, Kite shows a card offering to take you to the store page.

That request carries nothing about you or your budget: no account, no device
identifier, no location, nothing you have entered. It is the same kind of
request your browser makes loading any web page. This site is hosted on GitHub
Pages, so GitHub, like any web host, can see the IP address of the request and
may keep ordinary server logs under its own privacy statement. Kite does not
store that address, and I do not collect or see it. If the request fails, Kite
behaves exactly as if no update were available.

If you turn on **Tell me about new versions** (My account › Reminders, off by
default), the phone also runs this same check in the background, about once a
day when the operating system allows it, and shows one notification per new
version. The request is the same and carries nothing about you.

Besides signing in, syncing, Ask Kite, usage analytics if you agreed and the
anonymous counts below, this is the only network request Kite's own code
makes.

## What Kite asks permission for

- **Unlocking** — Face ID or Touch ID on iPhone, fingerprint, face or screen
  lock on Android, used only to unlock the app on your device. The result is a
  yes or no from the operating system; Kite never receives your biometric data,
  and neither does anyone else. Optional, and off by default.
- **Notifications** — used only for local reminders about bills you have
  entered and, if you turn them on, an evening nudge to log spending and a
  weekly "money minute" that says nothing about your figures, and, if you turn
  it on, one notification when a new version of Kite is out. A bill reminder
  has an **I paid it** button: it opens Kite and marks that bill paid, with an
  Undo. They are scheduled on the device by the operating system. No push server
  is involved: Kite never asks for a push token, and the iPhone build has the
  push entitlement removed.

## Sharing Kite

**Share Kite** in My account opens the phone's share sheet with a line of text
and the store link, and no figures from your budget. The link carries a tag
("share" or "milestone") so the App Store and Play Store can count installs that
came from sharing; it says nothing about you. Where it goes is your choice; Kite
learns nothing about it. **Budget with someone? Tell me** opens your mail app
with a few questions and no figures, addressed to kakodjenou@gmail.com.

## Ask Kite

**Ask Kite** is optional. It stays off until you agree the first time you open
it, and you can turn it off in My account, Privacy, which removes it from the app.
It needs you to be signed in, because it reads your budget from your account.

When you ask a question, Kite's server reads your budget from your account (your
pay schedule, bills, amounts and dates, and bill names unless you turn on **Hide
bill names**) and sends the parts it needs, with your question, to **Anthropic**,
the company that makes Claude. Claude writes the reply. The figures in a reply
come from Kite's own calculations, not from Claude, and Kite discards a reply
that states a figure its calculations did not produce. Ask Kite can still be
wrong, and it can only suggest: it never changes your budget unless you tap
**Apply**, and then Undo is there.

- Kite does not store your questions or Claude's answers on its server. The last
  conversation is kept on your phone, outside your synced budget; **New chat**
  clears it.
- Kite's server keeps a daily count of how many questions you asked and how much
  text they used, to enforce a daily limit. It holds no question text. The count
  is deleted with your account.
- Anthropic handles what it receives under its own API terms, as a service
  provider to Kite. It may process it outside Canada, including in the United
  States. Those terms say Anthropic does not use data sent through its
  API to train its models without permission. They also allow Anthropic to keep
  requests for a limited time (up to 30 days under its standard terms), and
  longer where its safety systems flag content or the law requires. Anthropic's
  current terms govern; they can change.
- Nothing is sent to Anthropic unless you ask a question.

## Usage analytics

Off until you agree. After you have used Kite a little, it asks once whether
you want to help improve it; you can change your answer any time in My account,
Privacy (**Share usage with Kite**).

If you agree, Kite sends **PostHog** (a product analytics service, hosted in the
United States) which screens and buttons you use, for example that you logged an
expense, marked a bill paid, opened or used Ask Kite, saved or restored a
backup, finished setup, tapped Share, or opened Kite that day. Each event can
carry a short label such as which tab or what kind of item, never a number.

- Events are linked to your Kite account's random ID, not to your name or email.
- They never include amounts, bill or income names, dates from your budget,
  your questions to Ask Kite, or anything you typed.
- No session recording, no automatic capture of what you tap, and no location
  from your IP address.
- Turning it off stops it at once. Signing out or deleting your account also
  forgets the link on the phone. To have the records already sent deleted,
  write to me at the address below.

## Email news

At sign-in, or later in My account, Privacy, you can tick **Email me when Kite
gets something new**. It is unticked unless you tick it. Kite saves your answer,
the time you gave it and where (sign-in or settings) with your account, and
keeps a history of changes, as Canada's anti-spam law asks. Your email address
is the one your provider shared at sign-in. **No email is sent yet.** When Kite
starts sending them, each will say who sent it and have a link to unsubscribe.
Your answer is deleted with your account.

## Anonymous counts

To know whether Kite works for people, Kite's server keeps a few counts that
are not linked to any account or device:

- each step of the sign-in screen (shown, tapped Apple or Google, succeeded,
  failed or cancelled), with the platform and the day;
- for signed-in people, one mark a day that Kite was opened and one that
  something was done in it (an expense logged or a bill paid), with the
  platform and the day;
- if you delete your account and choose to say why, the reason you picked.

They hold no ID, no amounts and nothing you entered, so they cannot be traced
back to you, and they are not deleted with an account because nothing ties them
to one.

## Planning a purchase

**Plan a purchase** works out, from the figures already in Kite, whether
something you want to buy fits: paying now, setting money aside, or paying over
time. It is arithmetic on your device. It looks nothing up, checks no prices or
rates, and makes no network request. Nothing is saved unless you choose one of
the options, and then only as a debt or a savings item in your own budget.

## The Home Screen widget

If you add Kite's widget to your Home Screen, Kite writes a small summary into a
folder that only Kite and its widget on your phone can read (an iOS App Group):
the money left this period, the day of the period and your next few bills. The
widget draws that summary and nothing else. It makes no network requests. On
Android the same summary is kept in Kite's own private storage, which only Kite
and its widget can read. With Kite's app lock on, the summary carries bill names
and dates but no amounts. Signing out or erasing your data empties it.

## Your data, and deleting it

- **Export it** at any time: My account → Your data → Save a backup.
- **Sign out**: My account → Sign out. Your budget is removed from that
  phone and stays in your account. Sign in again to bring it back.
- **Delete your account**: My account → Privacy → Delete account. This deletes
  your budget, your sign-in record, your email-news answer and its history,
  your Ask Kite daily counts and, for Apple accounts, the stored Apple
  token from Kite's database, tells Apple to end the Sign in with Apple link
  for Kite, and clears the phone, for good. Routine database backups kept by the
  hosting provider can hold a deleted account's data for a short while, days not
  months, before they expire.
- **Erase all data** (the bottom of My account, shown when you are signed out)
  clears the budget on this phone. When you are signed in, use Sign out to clear
  the phone, or Delete account to remove your budget from the account as well.
- Deleting the app removes Kite's files from the phone, including the saved
  copy. It does not delete your account; use Delete account first.

Because your budget is yours to export and delete yourself, there is little for
me to hand over or correct on your behalf. If you need something else, write to
me at the address below.

## Phone backups

Android's automatic backup to Google Drive is switched off for Kite
(`allowBackup=false`), so the phone's copy of the database is never copied to
Google's servers. On iPhone, Kite's data is included when you back up the phone
to iCloud or a computer, as with any app; that backup is Apple's feature and
stays under your control. On iPhone the app's files are encrypted while the
phone is locked.

## Children

Kite is not directed at children and does not knowingly collect information from
them.

## Changes

If a future version collects or shares anything new, this policy will be updated
before that version ships, and the change will be described in the release
notes.

## Contact

Questions about this policy: **kakodjenou@gmail.com**
