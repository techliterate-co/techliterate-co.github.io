+++
date = '2025-09-23T16:53:38-06:00'
title = 'Device Privacy'
weight = 4

[params]
  menuPre = '<i class="fa-solid fa-shield"></i> '
+++

### 1. App Tracking Transparency (ATT) - Deny Cross-Site Tracking

This remains the foundational privacy control in iOS. You should ensure this
setting is globally configured to prevent apps from asking for permission to
track you across other companies' apps and websites.

* **Setting:** `Settings` > `Privacy & Security` > `Tracking`
* **Recommendation:** Toggle **OFF** "Allow Apps to Request to Track."
* **Why:** This action automatically denies all applications the ability to link your activity (like purchases, browsing, and usage) between their app and third-party sites. This severely limits the data third-party companies can collect to build a profile of you for targeted advertising.

### 2. Precise Location Access - Limit to "While Using" and Disable "Precise Location"

For any app that doesn't absolutely require your street address (like a navigation app), you should restrict the specificity and duration of its access to your location data.

* **Setting:** `Settings` > `Privacy & Security` > `Location Services`
* **Recommendation:** For most apps, choose **"While Using the App"** and toggle **OFF** "Precise Location."
* **Why:** By disabling "Precise Location," you only share an approximate, 10-square-mile area, which is enough for weather or local searches but protects your exact whereabouts. Limiting access to "While Using" prevents an app from tracking your movement in the background when you are not actively using it.

### 3. Safari’s Advanced Link & Browser Fingerprinting Protection

iOS 26 has significantly enhanced Safari's protections against hidden trackers and fingerprinting techniques. These should be enabled in your browser settings.

* **Setting:** `Settings` > `Safari` > `Privacy & Security` section
* **Recommendation:** Ensure **"Prevent Cross-Site Tracking"** is ON and that the new **"Advanced Fingerprinting Protection"** (a feature expanded in iOS 26) is active (it should be on by default in the latest versions). Also, confirm **"Link Tracking Protection"** is enabled to strip tracking parameters from URLs.
* **Why:** This prevents websites and advertisers from using subtle technical details about your device (like screen size, available fonts, etc.) to create a unique "fingerprint" of you, and it blocks tracking codes added to links you click in Mail or Messages.

### 4. Lock/Hide Sensitive Apps and Configure Notifications

iOS 26 introduced the ability to lock and hide certain applications (like banking, messaging, or health apps) for an extra layer of security and privacy against unauthorized physical access.

* **Setting (Lock):** Tap and hold an app icon, then tap "Require Face ID/Touch ID."
* **Setting (Notifications):** `Settings` > `Notifications` > `Show Previews`
* **Recommendation:** **Lock or Hide** any sensitive app and set Notification Previews to **"When Unlocked"** or **"Never."**
* **Why:** Locking or hiding apps protects them from prying eyes if your phone is briefly accessed while unlocked. Hiding notification previews prevents the content of personal messages, emails, and alerts from being displayed on your lock screen for anyone nearby to read.

### 5. Disable "Share iPhone Analytics" and "Improve Siri & Dictation"

These system settings govern how much data you share with Apple to improve their services. While this data is anonymized, you have the option to stop sharing it completely.

* **Setting (Analytics):** `Settings` > `Privacy & Security` > `Analytics & Improvements`
* **Recommendation:** Toggle **OFF** "Share iPhone Analytics."
* **Setting (Siri):** `Settings` > `Privacy & Security` > `Improve Siri & Dictation`
* **Recommendation:** Toggle **OFF** "Improve Siri & Dictation."
* **Why:** This prevents your iPhone from sending diagnostic logs, usage data, and audio recordings of your voice interactions to Apple for analysis, giving you complete control over what operational data leaves your device.

---

Would you like to know how to enable any of these specific settings, or are you interested in a similar list for an Android device?
