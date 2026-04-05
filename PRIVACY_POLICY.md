# Privacy Policy for BoxMyDay

**Last Updated: April 5, 2026**

## Introduction

BoxMyDay ("we," "our," or "us") is a privacy-first productivity app. This Privacy Policy explains how the BoxMyDay mobile application (the "App") handles your information.

**Key point:** BoxMyDay stores your tasks and settings on your device. The free version of the app may also display Google AdMob ads.

---

## 1. Information handled by the app

When you use BoxMyDay, you may create and store:

- Tasks and task descriptions
- Scheduled task times, durations, and reminder settings
- App preferences, such as lock settings and wake-time preferences

This information is used only to provide the app's on-device functionality.

## 2. Information we do not collect

BoxMyDay does not ask you to create an account and does not collect or send the following to us directly:

- Name, email address, phone number, or account credentials
- Location data
- Contacts
- Photos, files, or media from your device
- Usage analytics or behavioral tracking data
- Crash reports sent to third-party services

---

## 3. How your data is stored

### 3.1 On-device storage

Your task data and app settings are stored locally on your device. We do not operate a cloud backend for BoxMyDay's task data in the current release.

### 3.2 Encryption and secure storage

BoxMyDay uses local protection mechanisms, including:

- SQLCipher-backed encrypted local database storage
- Platform secure storage for sensitive keys and secrets

### 3.3 Biometric authentication

If you enable app lock:

- biometric or device credential checks are handled by your device operating system
- BoxMyDay does not receive, store, or transmit your fingerprint, face data, PIN, or password

---

## 4. Permissions we request

BoxMyDay requests only permissions related to app functionality:

| Permission | Purpose |
|------------|---------|
| **Biometric** | Lets you optionally protect the app with biometrics or device credentials |
| **Notifications** | Lets the app remind you about scheduled tasks |
| **Schedule exact alarms** | Helps deliver task reminders at the intended time when Android allows it |
| **Vibrate** | Lets reminders use vibration |
| **Boot completed** | Lets reminders be restored after a device restart |
| **Wake lock** | Helps Android complete scheduled reminder work reliably |

If you deny optional permissions such as notifications, the app remains usable, but related features may be limited.

---

## 5. Third-party services

### 5.1 Google AdMob

The free version of BoxMyDay may use the Google Mobile Ads SDK (AdMob) to display ads.

According to Google's Google Mobile Ads SDK disclosure guidance, the SDK may automatically collect and share data such as:

- IP address
- device and account identifiers, including advertising-related identifiers where available
- diagnostic information
- user product interaction information related to ad serving

This data is collected and processed by Google and its partners for purposes such as advertising, analytics, and fraud prevention. BoxMyDay uses Google's User Messaging Platform (UMP) to present consent and privacy options where required.

BoxMyDay's task content, schedules, and notes are not used by us for ad targeting.

For more information, see:

- [Google Play's data disclosure requirements for the Google Mobile Ads SDK](https://developers.google.com/admob/android/privacy/play-data-disclosure)
- [Google Privacy Policy](https://policies.google.com/privacy)
- [Google EU User Consent / UMP guidance](https://developers.google.com/admob/flutter/privacy/gdpr)

### 5.2 Other SDKs

The current release does **not** include:

- Firebase Analytics
- third-party crash reporting SDKs
- social SDKs
- cloud sync services

---

## 6. Data security

We take reasonable steps to protect local app data, including:

- encrypted local storage for primary task data
- minimal Android permissions
- release build shrinking and obfuscation

Because BoxMyDay's current release does not send your task data to our servers, we do not build a server-side task profile from your use of the app. However, ad-related data may be processed by Google through AdMob as described above.

---

## 7. Your choices and control

You control your BoxMyDay data on your device. You can:

- edit or delete tasks in the app
- clear app data from Android settings
- uninstall the app to remove locally stored app data
- review or change ad privacy choices through the in-app privacy options entry point when required

## 8. Data retention

Your data remains on your device until you delete it, clear app data, or uninstall the app.

---

## 9. Children's privacy

BoxMyDay is not directed to children under 13. We do not knowingly collect personal information from children.

---

## 10. International users

BoxMyDay stores task data locally on your device and does not operate a cloud backend for that task data. However, if ads are shown, Google and its partners may process ad-related data according to their own infrastructure and policies, which can involve international data transfers.

---

## 11. Changes to this policy

We may update this Privacy Policy from time to time. If we do, we will update the date at the top of this page.

---

## 12. Contact

If you have questions about this Privacy Policy, contact:

**Email:** info@nvisust.com

**Developer:** Nvisust
**App:** BoxMyDay
**Package:** com.nvisust.boxmyday

---

By using BoxMyDay, you agree to this Privacy Policy.
