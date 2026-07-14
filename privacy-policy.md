# Privacy Policy — Clavex

> Last updated: July 2026

---

## Overview

Clavex is a local password manager developed by Manuel Arroyo.
This policy explains what data we collect, how we use it, and how we 
protect it.

**Your passwords never leave your device. We collect no personal data.**

---

## What data we collect

Clavex does not collect any personal information.

- ❌ No name
- ❌ No email address
- ❌ No phone number
- ❌ No account credentials
- ❌ No passwords or sensitive data

### Anonymous diagnostic data
We use Firebase Crashlytics to collect anonymous crash reports to 
improve app stability. This data contains only technical information 
about the device and app state at the time of a crash — never any 
passwords or personal information.

### Advertising identifier
Clavex displays ads via Google AdMob. AdMob may collect your 
device's advertising identifier to show relevant ads. You can reset 
or disable this identifier in your device settings.

---

## How your data is stored

All your passwords are stored **exclusively on your device**, 
encrypted with AES-256. Clavex uses a double encryption layer:
Your password (plain text)
↓
AES-256-CBC encryption
↓
SQLCipher (entire database encrypted with AES-256)
↓
.db file stored locally on your device

No data is ever transmitted to our servers or any third party, 
except for the anonymous diagnostic and advertising data described above.

---

## Your PIN

Your 6-digit PIN is stored locally on your device using 
Android's EncryptedSharedPreferences (AES-256-GCM). 
It is never transmitted, stored remotely, or recoverable 
by the developer.

**If you lose your PIN, there is no recovery option.** 
We strongly recommend exporting a backup of your passwords 
and storing your PIN in a safe place.

---

## Third-party services

| Service | Purpose | Privacy Policy |
|---------|---------|----------------|
| Firebase Crashlytics | Anonymous crash reports | [Firebase Privacy](https://firebase.google.com/support/privacy) |
| Google AdMob | In-app advertising | [Google Privacy](https://policies.google.com/privacy) |

---

## Data retention

| Data | Where stored | Retention |
|------|-------------|-----------|
| Passwords | Your device only | Until you delete them |
| PIN | Your device only | Until you reset it |
| Crash reports | Firebase (anonymous) | 90 days |
| Advertising ID | Device / AdMob | Per AdMob policy |

---

## Your rights

- **Access**: all your data is on your device
- **Delete**: uninstall the app — all local data is permanently deleted
- **Export**: use the built-in export feature to back up your passwords
- **Opt out of ads**: disable the advertising identifier in your device settings
- **Opt out of crash reports**: we do not currently offer an in-app opt-out, 
  but you can contact us to request exclusion

---

## Children's privacy

Clavex is not directed at children under 13 years of age. 
We do not knowingly collect data from children under 13.

---

## Changes to this policy

We may update this policy from time to time. We will notify you 
by publishing the new policy on this page and updating the 
"Last updated" date above.

---

## Contact

📧 **Email:** [clavex.help@gmail.com]
🌐 **GitHub:** [https://github.com/ManuelArroyo](https://github.com/ManuelArroyo)

---

<div align="center">

**Clavex** — Your passwords, secured locally.

*No accounts. No cloud. No tracking.*

</div>