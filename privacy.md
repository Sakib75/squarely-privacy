# Squarely Privacy Policy

**Last updated: 13 August 2026**

Squarely ("the app") helps you record shared expenses with friends, roommates and
groups, and shows who owes whom. This policy explains what the app collects, why,
and what control you have.

The app is operated by **Nazmus Sakib**. Contact:
**sakibkuet16@gmail.com**.

## 1. What we collect

We only collect what the app needs to work. There is no advertising SDK, no
analytics SDK and no third-party tracker in the app.

### Information you give us

| Data | Why we need it |
| --- | --- |
| Email address | Identifies your account, used to sign in, reset your password, and let friends add you |
| Password | Authentication. Stored only as a salted hash — never in readable form, and never visible to us |
| Display name | Shown to people you share expenses with |
| Profile photo (optional) | Shown next to your name in groups |
| Default currency | Preselects the currency when you add an expense |

### Information you create by using the app

| Data | Why we need it |
| --- | --- |
| Expenses: description, amount, currency, date, category, optional notes | The core function of the app |
| Receipt photos (optional) | Attached to an expense so group members can check it |
| Settlements: amount, date, method, optional notes | Records that a debt was paid |
| Comments on expenses | Lets group members discuss a charge |
| Groups and group membership | Determines who can see which expenses |
| Friend connections | Lets you split with people without creating a group |
| Activity history | Powers the activity feed and notifications |

### Information collected automatically

| Data | Why we need it |
| --- | --- |
| Push notification token | Delivers notifications about new expenses, settlements and comments. Only created if you grant notification permission |
| Device platform (`ios` / `android`) | Routes each notification to the right push service |

We do **not** collect your location, contacts, calendar, advertising identifier,
browsing history, or any biometric data.

## 2. Who can see your data

**Other users.** Shared-expense data is shared by design. People in a group can
see expenses in that group, who paid, how it was split, comments, and any receipt
attached. People you split with directly can see those shared expenses. Your
display name, profile photo and email address are visible to people you are
connected to, because that is how they add and identify you.

**Service providers.** We use these processors to run the app:

- **Supabase** — database, authentication and file storage hosting.
- **Expo push notification service** — relays notifications to Apple's and
  Google's push networks. The notification text and your push token pass through it.

**Nobody else.** We do not sell your data, share it with advertisers, or use it to
build advertising profiles.

**Legal requests.** We may disclose data if required by law.

## 3. Your rights and controls

**You can delete your account at any time**, in the app: **Account → Danger zone →
Delete account**.

Deletion permanently removes your name, email address, profile photo, friend
connections, group memberships, notifications and registered devices, and your
sign-in credentials. You will no longer be able to log in.

**One important limit.** Expenses and settlements you shared with other people
remain in *their* history, attributed to "Deleted user". Those records are how
other people's balances are calculated — erasing them would silently change what
your friends believe they owe each other. For this reason the app asks you to
settle any outstanding balance before deleting your account. This retention is
limited to the shared financial records themselves and contains no personal
identifiers after deletion.

Other rights, depending on where you live: you may request a copy of your data,
ask us to correct it, or ask us to restrict processing. Email
**sakibkuet16@gmail.com** and we will respond within 30 days. You can export a
group's expenses to CSV at any time from the app.

**Notifications** can be turned off at any time in your device settings.

## 4. Security

Data is transmitted over encrypted connections (HTTPS/TLS) and stored on
Supabase's managed infrastructure with encryption at rest. Passwords are stored
only as salted hashes. Row-level security rules in the database restrict every
query to the groups and friendships you actually belong to. Profile photos and
receipts are kept in private storage buckets reachable only through short-lived
signed links.

No system is perfectly secure, and we cannot guarantee absolute security.

## 5. Data retention

Your data is kept while your account is active. When you delete your account,
personal data is removed immediately, with the shared-records exception described
in section 3. Backups may retain data for up to 30 days before rotating out.

## 6. Children

The app is not directed to children under 13 (or the minimum age in your
country), and we do not knowingly collect their data. If you believe a child has
created an account, contact us and we will delete it.

## 7. International transfers

Data is processed on servers in the region selected for the Supabase project,
which may be outside **Bangladesh**. Where required, transfers rely on
standard contractual clauses.

## 8. Changes

If this policy changes materially we will update the "Last updated" date and, for
significant changes, notify you in the app.

## 9. Contact

Questions or requests: **sakibkuet16@gmail.com**.
