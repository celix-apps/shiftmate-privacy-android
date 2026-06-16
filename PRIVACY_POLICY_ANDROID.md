# ShiftMate Privacy Policy (Android)

**Effective Date:** June 16, 2026
**Last Updated:** June 16, 2026
**Developer:** Celix Apps
**Contact:** support.shiftmate@icloud.com

---

## 1. Introduction

This Privacy Policy ("Policy") describes how Celix Apps ("we," "our," or "us") handles information in connection with the ShiftMate mobile application ("App") available on the Google Play Store for Android. By downloading, installing, or using the App, you acknowledge that you have read, understood, and agree to be bound by this Policy.

If you do not agree with any part of this Policy, you must immediately stop using the App.

This Policy applies solely to the ShiftMate Android application and does not apply to any third-party services, websites, or applications that may be linked to or integrated with the App, including but not limited to Google LLC, Google Play, Google Drive, or Health Connect. We expressly disclaim any responsibility for the privacy practices of such third parties.

---

## 2. Information We Collect and How It Is Stored

### 2.1 Shift and Schedule Data

You may enter shift schedules, work patterns, notes, and related calendar information into the App. This data:

- Is stored **locally on your device** in the App's private database (Room) and preferences storage (DataStore).
- Is **never transmitted to our servers** — we do not operate any backend server that receives your shift data.
- Is **optionally backed up** to your personal Google Drive account if you enable Google Drive Backup (see Section 2.2).

You are solely responsible for the accuracy, completeness, and legality of the shift data you enter into the App.

### 2.2 Google Drive Backup (Optional)

If you choose to enable Google Drive Backup, the App will:

- Request authorization to access only the **App Data folder** of your Google Drive account (scope: `drive.appdata`), a hidden, app-private storage area that is **not visible or accessible** to you or any other app through your regular Drive interface.
- Store an encrypted-at-rest backup file of your shift data in that private App Data folder, created either manually or automatically (daily background backup).
- Store your associated Google account **email address locally on your device** solely to display which account is connected and to manage the backup. This email address is never transmitted to us.
- Retain at most 5 backup versions in your App Data folder; older backups are automatically deleted.

We do not have access to, and cannot retrieve, the contents of your Google Drive App Data folder. You may disconnect this feature at any time within the App's Backup & Restore settings, or by revoking the App's access via your Google Account permissions page (myaccount.google.com/permissions).

### 2.3 Health Connect Data

With your explicit permission, the App may request read-only access to sleep and step data through Android's Health Connect framework. Regarding this data:

- It is accessed solely to display personalized insights within the App (e.g., fatigue score, sleep overview).
- It is **processed entirely on your device** and is **never transmitted** to our servers or any external server.
- It is **never shared** with third parties, advertisers, or data brokers.
- You may revoke Health Connect access at any time through the Health Connect app or Android Settings → Privacy → Health Connect → App permissions → ShiftMate.
- We do not store, retain, or cache Health Connect data outside of what is temporarily held in device memory for display purposes.

We do not use Health Connect data for advertising, marketing, or any purpose other than the in-app features you explicitly enable.

### 2.4 Calendar Data

With your explicit permission, the App may read and write to your device's calendar provider to create reminder events for your scheduled shifts (e.g., alarm events). Regarding this data:

- Calendar events created by the App are stored **only in your device's local calendar provider**.
- This data is **never transmitted** to our servers or any third party.
- You may revoke Calendar access at any time through Android Settings → Apps → ShiftMate → Permissions → Calendar.

### 2.5 Public Holiday Data

To display public holidays relevant to your selected country, the App sends your selected **country code and calendar year** (no personal identifiers) to the third-party service Nager.Date (date.nager.at) over the internet. No shift data, device identifiers, or personal information is included in this request. This exchange is governed by Nager.Date's own terms; we have no control over their data practices.

### 2.6 Diagnostic and Usage Logs

The App may use Android's standard logging system (Logcat) to record diagnostic events during development and debugging. These logs:

- Are stored **only in your device's local system log** and are cleared on reboot.
- Are **never transmitted** to our servers or any external analytics platform.
- Do not contain personal identifiers, health data, or shift content beyond what is necessary for local debugging.

We do not use any third-party analytics SDK (such as Firebase Analytics, Mixpanel, or Amplitude) and we do not use any advertising SDK. No behavioral tracking, cross-app tracking, or user profiling is performed.

### 2.7 Subscription and Payment Data

The App offers optional Pro subscriptions processed entirely through Google Play's billing system (Play Billing Library). Regarding payment data:

- We do **not** collect, process, store, or have access to your payment card details, billing address, or Google account credentials.
- Subscription status (active/inactive) is verified locally via Play Billing and/or Google Play's servers.
- All billing, refunds, and subscription management are governed exclusively by Google Play's Terms of Service and Google's privacy policy.
- You may manage or cancel your subscription at any time through the Google Play Store app → Profile → Payments & subscriptions.

### 2.8 Backup and Export Data (Manual Export)

The App may allow you to manually export your shift or earnings data (e.g., as a file) to share or save outside the App. Exported files:

- Are stored or shared to a location you choose (e.g., Files app, email, another app via Android's share sheet).
- Are your sole responsibility once exported.
- Are not transmitted to us.

### 2.9 Notifications and Alarms

The App schedules local notifications and alarms (using Android's AlarmManager and a foreground service) to remind you of upcoming shifts. These notifications:

- Are generated and delivered entirely **on your device**.
- Do not rely on any push notification server operated by us or any third party (e.g., Firebase Cloud Messaging is not used).

---

## 3. Data We Do NOT Collect

To be unambiguous, we do not collect:

- Your name, email address, phone number, or any contact information (unless you contact us voluntarily, or you connect Google Drive Backup, in which case only your account email is stored locally on your device as described in Section 2.2).
- Government-issued identification numbers.
- Precise GPS location history.
- Browsing history or cross-app tracking data.
- Advertising identifiers (Android Advertising ID).
- Biometric data.
- Financial or banking information.
- Social media profile data.
- Any data from children under the age of 13.

---

## 4. How We Use Your Information

We use information within the App solely to:

- Provide core app functionality (shift scheduling, alarm notifications, earnings calculation, health insights).
- Back up and restore your data via your own Google Drive account (if enabled).
- Display relevant public holidays based on your selected country.
- Display in-app notifications and alarms on your device.
- Diagnose crashes or bugs through on-device logs during development.

We do not use your information for:

- Advertising or marketing to you.
- Selling, renting, or licensing data to third parties.
- Profiling, scoring, or automated decision-making with legal or significant effects.
- Training machine learning models on your personal data.

---

## 5. Data Sharing and Disclosure

We do not sell, rent, trade, or otherwise share your personal data with any third parties, except in the following limited circumstances:

### 5.1 Google LLC

Certain features of the App rely on Google platform services (Google Drive, Health Connect, Google Play Billing, Google Play Store). Your use of these features is subject to Google's Privacy Policy (available at policies.google.com/privacy). We have no control over and assume no responsibility for Google's data practices.

### 5.2 Nager.Date

As described in Section 2.5, the App queries the Nager.Date public holiday API using only a country code and year. We have no control over and assume no responsibility for Nager.Date's data practices.

### 5.3 Legal Requirements

We may disclose information if we reasonably believe disclosure is required by applicable law, regulation, legal process, or governmental request. To the extent permitted by law, we will attempt to notify you of such requirements.

### 5.4 Protection of Rights

We may disclose information to enforce our Terms of Service, protect our rights or property, or protect the safety of our users or others, where permitted by applicable law.

### 5.5 Business Transfers

In the event of a merger, acquisition, reorganization, bankruptcy, or sale of all or a portion of our assets, your information may be transferred as part of that transaction. We will notify you of any such change in ownership or control of your personal information.

---

## 6. Data Security

We implement reasonable technical and organizational measures to protect your data, including:

- **Local encryption:** Data stored on your device benefits from Android's device-level encryption.
- **Google Drive backup security:** Backups stored in your Google Drive App Data folder benefit from Google's encryption in transit and at rest, and are isolated from your visible Drive files.
- **No server-side storage:** Because we do not operate servers that receive your personal data, server-side breaches of your personal data by us are structurally impossible.

However, **no method of electronic storage or transmission is 100% secure.** We cannot guarantee absolute security. You assume all risk associated with the use of the App, including but not limited to data loss resulting from device theft, loss, hardware failure, software bugs, OS updates, or unauthorized access to your device.

We expressly disclaim liability for any unauthorized access to or disclosure of your information that results from circumstances beyond our reasonable control.

---

## 7. Data Retention

### 7.1 Local Data

Data you store in the App remains on your device until you delete it within the App or uninstall the App. We do not control the retention of data stored on your device.

### 7.2 Google Drive Backup Data

If Google Drive Backup is enabled, backup files in your private App Data folder are subject to Google's storage and retention policies, and to the App's automatic retention of the 5 most recent backups. Deleting your Google account, revoking the App's Drive permission, or uninstalling the App may result in the App losing the ability to manage these backups; the underlying files remain in your Google account subject to Google's policies. We are not responsible for data loss caused by Google's services.

### 7.3 Account Deletion

If you use the "Delete Account" / data-reset feature within the App, locally stored data will be deleted from your device. However:

- We cannot guarantee deletion of backup files previously stored in your Google Drive App Data folder; you may delete these by revoking the App's access at myaccount.google.com/permissions.
- Residual data in system logs may persist until the operating system purges them automatically.
- Files you have manually exported are not deleted and remain your responsibility.

---

## 8. Your Rights

Depending on your jurisdiction, you may have the following rights with respect to your personal data:

### 8.1 Right of Access
You may request confirmation of whether we hold any personal data about you. Given our architecture (no server-side personal data storage), we typically hold only voluntary contact data you have sent us (e.g., support emails).

### 8.2 Right to Rectification
You may correct inaccurate personal data we hold about you.

### 8.3 Right to Erasure ("Right to Be Forgotten")
You may request deletion of personal data we hold. To delete all app data, uninstall the App or use the in-app reset function. For backups held in Google Drive, manage them through your Google Account settings.

### 8.4 Right to Data Portability
You may export your shift and earnings data using the App's export functionality.

### 8.5 Right to Withdraw Consent
You may withdraw any permission you have granted (Health Connect, Calendar, Notifications, Google Drive access) at any time through Android Settings or the relevant Google account permissions page, without affecting prior use.

### 8.6 Right to Restrict Processing
You may contact us to request restriction of any processing of personal data we hold directly.

### 8.7 Right to Object
You may object to any processing of your personal data we carry out on the basis of legitimate interests.

### 8.8 KVKK Rights (Turkey)
If you are located in Turkey, you have additional rights under the Law on Protection of Personal Data No. 6698 (KVKK), including the right to apply to the Personal Data Protection Authority (Kişisel Verileri Koruma Kurumu — KVKK) at kvkk.gov.tr if you believe your rights have been violated.

### 8.9 GDPR Rights (European Economic Area)
If you are located in the EEA, you may lodge a complaint with your local data protection supervisory authority.

To exercise your rights, contact us at: **support.shiftmate@icloud.com**

We will respond to verifiable requests within 30 days. We may need to verify your identity before fulfilling a request.

---

## 9. Children's Privacy

The App is not directed to children under the age of 13 (or 16 in certain jurisdictions under GDPR). We do not knowingly collect personal data from children under these ages. If we become aware that we have inadvertently received personal data from a child under the applicable age threshold, we will delete such data promptly.

If you are a parent or guardian and believe your child has provided us with personal data, please contact us at support.shiftmate@icloud.com.

---

## 10. Third-Party Services

The App integrates with the following third-party services. Each is governed by its own privacy policy, over which we have no control and for which we assume no responsibility:

| Service | Purpose | Privacy Policy |
|---|---|---|
| Google Drive (App Data scope) | Optional encrypted backup of shift data | policies.google.com/privacy |
| Android Health Connect | Sleep and step insights | policies.google.com/privacy |
| Google Play Billing | Subscription processing | policies.google.com/privacy |
| Google Play Store | App distribution, in-app reviews | policies.google.com/privacy |
| Nager.Date (date.nager.at) | Public holiday lookup by country/year | nager.at |

We do not integrate any advertising network, social media SDK, analytics SDK, or cross-app tracking library.

---

## 11. App Permissions

The App requests the following Android permissions, used strictly for the purposes described:

| Permission | Purpose |
|---|---|
| `INTERNET` | Fetch public holiday data (Section 2.5) and communicate with Google Drive (Section 2.2) |
| `POST_NOTIFICATIONS` | Display shift reminder notifications |
| `SCHEDULE_EXACT_ALARM` / `USE_EXACT_ALARM` | Trigger shift alarms at the exact scheduled time |
| `RECEIVE_BOOT_COMPLETED` | Re-register scheduled alarms after device restart |
| `USE_FULL_SCREEN_INTENT` | Show the alarm screen over the lock screen |
| `WAKE_LOCK` | Keep the device awake briefly while an alarm is firing |
| `FOREGROUND_SERVICE` / `FOREGROUND_SERVICE_MEDIA_PLAYBACK` | Play the alarm sound reliably while the alarm is active |
| `VIBRATE` | Vibrate the device for alarms and notifications |
| `READ_CALENDAR` / `WRITE_CALENDAR` | Create and read shift reminder events in your device calendar (Section 2.4) |
| `health.READ_SLEEP` / `health.READ_STEPS` | Read sleep and step data via Health Connect (Section 2.3) |

---

## 12. Disclaimer of Warranties

**THE APP IS PROVIDED "AS IS" AND "AS AVAILABLE," WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, ACCURACY, OR NON-INFRINGEMENT.**

We do not warrant that:

- The App will be uninterrupted, error-free, or free of viruses or other harmful components.
- The App will accurately calculate earnings, schedules, or health metrics for any specific legal, financial, medical, or employment purpose.
- Data stored in the App will not be lost due to device failure, software bugs, or OS updates.
- Notifications and alarms will be delivered at the exact scheduled time in all device and system conditions (e.g., battery optimization, Doze mode, manufacturer-specific restrictions).

You assume all risk associated with the use of the App and any reliance on its output.

---

## 13. Limitation of Liability

TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, IN NO EVENT SHALL CELIX APPS, ITS DEVELOPERS, OFFICERS, OR AFFILIATES BE LIABLE FOR ANY:

- Indirect, incidental, special, consequential, or punitive damages.
- Loss of profits, revenue, data, goodwill, or other intangible losses.
- Damages resulting from unauthorized access to your device or data.
- Damages resulting from interruption or cessation of service.
- Damages resulting from bugs, viruses, or errors in the App.
- Damages resulting from your reliance on information provided by the App (including earnings estimates, schedule projections, or health insights).

THIS LIMITATION APPLIES REGARDLESS OF THE THEORY OF LIABILITY (CONTRACT, TORT, NEGLIGENCE, STRICT LIABILITY, OR OTHERWISE) AND EVEN IF WE HAVE BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.

In jurisdictions that do not allow the exclusion or limitation of liability for consequential or incidental damages, our liability is limited to the maximum extent permitted by law.

---

## 14. Indemnification

You agree to defend, indemnify, and hold harmless Celix Apps and its developers from and against any claims, damages, obligations, losses, liabilities, costs, or debt arising from: (a) your use of the App; (b) your violation of this Policy; (c) your violation of any third-party right, including any privacy or intellectual property right; or (d) any data you input into the App.

---

## 15. Changes to This Policy

We reserve the right to update this Policy at any time. When we make material changes, we will:

- Update the "Last Updated" date at the top of this document.
- Post the revised Policy at the same URL.
- Where required by law or where reasonably practicable, provide additional notice through the App.

Your continued use of the App after the effective date of a revised Policy constitutes your acceptance of the revised Policy. If you do not agree to the revised Policy, you must stop using the App.

We encourage you to review this Policy periodically.

---

## 16. Governing Law and Dispute Resolution

This Policy and any disputes arising out of or relating to it shall be governed by and construed in accordance with the laws of the Republic of Turkey, without regard to its conflict of law provisions.

Any dispute shall first be attempted to be resolved through good-faith negotiation. If unresolved within 30 days, disputes shall be subject to the exclusive jurisdiction of Istanbul courts and enforcement offices.

Users located in other jurisdictions may also have rights under local law that are not affected by this clause.

---

## 17. Contact

For privacy-related questions, requests, or complaints:

**Celix Apps**
Email: support.shiftmate@icloud.com

We aim to respond to all inquiries within 30 business days.

For data protection complaints in Turkey:
**Kişisel Verileri Koruma Kurumu (KVKK)**
Website: kvkk.gov.tr

---

*This privacy policy was last reviewed and updated on June 16, 2026.*
