# Privacy Policy — My Gratitude Jar

**Last updated:** March 4, 2026  
**Effective date:** March 4, 2026

My Gratitude Jar ("the App", "we", "us", or "our") is a personal gratitude journaling application for Android developed by an independent developer. This Privacy Policy explains how we collect, use, store, and protect your information when you use the App.

By installing or using the App you agree to this Privacy Policy. If you do not agree, please uninstall the App and discontinue use.

---

## 1. Information We Collect

### 1.1 Information You Provide

| Data | Description |
|---|---|
| **Gratitude entries** | Text you write, mood selections, and the date of each entry |
| **Photos** | Images you optionally attach to entries (compressed and stored as JPEG) |
| **Display name** | A name you choose to personalise the App |
| **Memory capsules** | Titles and personal messages you write when sealing a memory capsule |
| **Bug reports** | Title, description, and device information you submit through the in-app bug report form |
| **Liked quotes** | Daily quotes you mark as favourites |

### 1.2 Information Collected Automatically

| Data | Description |
|---|---|
| **Firebase User ID** | A unique, anonymous identifier assigned when you first open the App |
| **Analytics events** | Non-personal usage events such as app opens, entry counts, and feature interactions (e.g. jar shaken, affirmation completed). No entry text is included. |
| **Crash & error reports** | Stack traces, device model, OS version, and app state at the time of a crash or error |
| **Device information** | Browser/device user-agent string (collected only when you submit a bug report) |
| **Subscription status** | Your subscription tier (free or premium) as managed by Google Play |

### 1.3 Information from Third-Party Sign-In

If you choose to sign in with **Google** or **email/password**, we receive:

- Your email address
- Your display name (Google sign-in only)
- Your profile photo URL (Google sign-in only)

Signing in is **optional**. You can use the App fully without creating an account (anonymous mode).

---

## 2. How We Use Your Information

We use the information we collect to:

- **Provide core functionality** — store, display, and organise your gratitude entries, streaks, and memory capsules
- **Sync your data** — if you sign in, we sync your entries, streaks, profile, and liked quotes to the cloud so you can access them across devices
- **Improve the App** — anonymous usage analytics help us understand which features are used and identify areas for improvement
- **Fix bugs and crashes** — crash reports help us diagnose and resolve technical issues
- **Send reminders** — deliver local notifications at your chosen time (never push marketing messages)
- **Process subscriptions** — manage your premium subscription through Google Play

We **never** use your gratitude entry text, photos, or mood data for advertising, marketing, profiling, or training AI/ML models.

---

## 3. Data Storage & Security

### 3.1 Local Storage (On-Device)

All your data is stored locally on your device first. The App works fully offline. Local data includes entries, streaks, capsules, preferences, and cached content.

### 3.2 Cloud Storage (Firebase)

If you are signed in (including anonymously), the following data is synced to Google Cloud Firestore:

- Gratitude entries (text, mood, photos, dates)
- Streaks
- User profile (display name, preferences)
- Liked quotes
- Bug reports

Data is stored under your unique user ID at the path `users/{your_id}/...` in Firestore. Photos are stored inline as compressed image data — we do not use a separate file storage service.

Cloud data is protected by Firebase Security Rules that restrict access to your own data only. Data is encrypted in transit (TLS) and at rest by Google Cloud.

### 3.3 Data Residency

Our Firebase project and Cloud Functions are hosted in the United States (us-central1). Your data may be processed and stored in the United States.

---

## 4. Third-Party Services

The App uses the following third-party services, each with their own privacy policies:

| Service | Provider | Purpose | Privacy Policy |
|---|---|---|---|
| **Firebase Authentication** | Google | User sign-in & identity | [Firebase Privacy](https://firebase.google.com/support/privacy) |
| **Cloud Firestore** | Google | Cloud database for data sync | [Firebase Privacy](https://firebase.google.com/support/privacy) |
| **Firebase Analytics** | Google | Anonymous usage analytics | [Firebase Privacy](https://firebase.google.com/support/privacy) |
| **Firebase Crashlytics** | Google | Crash & error reporting | [Firebase Privacy](https://firebase.google.com/support/privacy) |
| **Google Play Billing** | Google | Subscription payments | [Google Privacy Policy](https://policies.google.com/privacy) |
| **RevenueCat** | RevenueCat Inc. | Subscription management | [RevenueCat Privacy](https://www.revenuecat.com/privacy/) |

We do not sell, rent, or share your personal data with any third parties for advertising or marketing purposes.

---

## 5. Permissions

The App requests the following Android permissions:

| Permission | Why It's Needed |
|---|---|
| **Internet** | Connect to Firebase and Google Play for sync, analytics, and subscriptions |
| **Camera** | Take photos to attach to gratitude entries (only when you choose to) |
| **Photo/media access** | Select photos from your gallery to attach to entries |
| **Microphone** | Speech recognition for the daily affirmation feature (only when you choose to) |
| **Notifications** | Send your daily gratitude reminder at your chosen time |
| **Exact alarm** | Ensure your reminder fires at the exact time you set |
| **Boot completed** | Restore your reminder alarm after a device restart |
| **Billing** | Process in-app subscriptions through Google Play |

All permissions are requested at the time of use — the App does not access your camera, microphone, or photos unless you initiate the relevant feature.

---

## 6. Data Retention

- **Your data is retained as long as your account exists.** We do not automatically delete your entries or profile data.
- **Crash reports and analytics** are retained according to Firebase's standard retention periods (typically 90 days for Crashlytics, 14 months for Analytics).
- **Bug reports** are retained in Firestore until manually deleted by the developer.

---

## 7. Your Rights & Choices

### 7.1 Access & Control

- **View your data**: All your entries, streaks, and profile data are visible within the App at any time.
- **Delete individual entries**: You can delete any gratitude entry from within the App. Deleted entries are removed from both local storage and the cloud.
- **Sign out**: You can sign out at any time from Settings. Signing out disconnects cloud sync.
- **Disable analytics**: You can disable Firebase Analytics through your device's Google settings (Ads → Opt out of Ads Personalization).
- **Disable reminders**: You can turn off daily reminders in Settings at any time.

### 7.2 Account Deletion

To request complete deletion of your account and all associated data, please contact us at the email address listed below. We will delete your Firestore data, authentication record, and any bug reports within 30 days of your request.

---

## 8. Children's Privacy

The App is **not directed at children under the age of 13**. We do not knowingly collect personal information from children under 13. If you are a parent or guardian and believe your child has provided us with personal data, please contact us so we can delete it.

---

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will update the "Last updated" date at the top of this page. We encourage you to review this policy periodically. Continued use of the App after changes constitutes acceptance of the updated policy.

---

## 10. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your data, please contact us at:

**Email:** devyprabs@gmail.com

---

*This privacy policy applies to the My Gratitude Jar Android application (package: com.mygratitudejar.app) distributed on Google Play.*
