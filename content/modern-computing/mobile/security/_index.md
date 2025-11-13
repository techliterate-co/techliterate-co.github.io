+++
date = '2025-09-23T16:53:38-06:00'
title = 'Device Security'
weight = 3

[params]
  menuPre = '<i class="fa-solid fa-shield"></i> '
+++

## **iPhone**

### 1. Audit App Permissions via the Privacy Dashboard

Modern Android versions feature a **Privacy Dashboard** that provides a clear
overview of which sensitive permissions (like location, camera, and microphone)
have been used recently and by which apps. This is the single most effective
way to audit app behavior.

* **Setting:** `Settings` > `Security & privacy` (or just `Privacy`) > **Privacy Dashboard** > `Permission manager`
* **Recommendation:** Regularly check the dashboard to see which apps accessed your Camera, Microphone, and Location in the last 24 hours. For any suspicious app, tap it in the **Permission Manager** and restrict its access to **"Allow only while using the app"** or **"Don't allow."**
* **Why:** This allows you to catch and stop apps (especially free games or utilities) that are improperly accessing sensitive hardware in the background when they shouldn't be.

### 2. Delete/Reset Your Advertising ID and Limit Ad Personalization

Google uses a unique, resettable advertising ID (AAID) tied to your device to
track your activity across apps for targeted advertising. You can delete this
ID and opt out of personalization.

* **Setting:** `Settings` > `Google` > `Ads` (or `Security & privacy` > `Privacy Controls` > `Ads`)
* **Recommendation:** Tap **"Delete advertising ID"** and then ensure the toggle for **"Opt out of Ads Personalization"** (or a similar phrase) is **ON**.
* **Why:** Deleting the ID instantly severs the link between your historical activity data and your current device profile. Opting out tells apps and advertisers not to use any ID (even a new one) to build personalized user profiles for ad delivery.

### 3. Implement Auto-Delete for Google Account Activity

Even after adjusting local device settings, Google still tracks your activity
across its web services (Search, Maps, YouTube) under your Google Account. You
should set up automatic deletion rules for this stored data.

* **Setting:** Go to your **Google Account** settings (either through the phone settings or a browser) > `Data & privacy` > `Activity controls`
* **Recommendation:** For **Web & App Activity** and **Location History**, choose the **"Auto-delete"** option and set the retention period to **3 months** (the shortest available period) or at least **18 months**.
* **Why:** This prevents your sensitive personal data and movement history from being permanently stored on Google's servers, ensuring the data is automatically purged after a short time.

### 4. Enable Google Play Protect and App Permission Reset

Google Play Protect is Android's built-in malware scanner, but it also handles
the security feature of auto-resetting permissions for unused apps. Both should
be confirmed as active.

* **Setting (Play Protect):** Open **Google Play Store** > Tap your **Profile Icon** > **Play Protect**.
* **Setting (Permission Reset):** `Settings` > `Apps` > `Special app access` > **Remove permissions and free up space**
* **Recommendation:** Confirm **Play Protect is active** and that the feature to **"Remove permissions if app isn't used"** is turned **ON** globally.
* **Why:** Play Protect provides a critical baseline defense against malware. The automatic permission reset is a key privacy feature that automatically revokes sensitive permissions (like location or contacts) from apps you haven't used in a few months, limiting the risk of "dormant" apps collecting data.

### 5. Disable Usage and Diagnostics Sharing

Android collects aggregated data about how you use your phone (app performance,
stability, battery life) to send back to Google for system improvements. You
can opt out of this continuous telemetry.

* **Setting:** `Settings` > `Security & privacy` > `More privacy settings` (or just `Privacy`) > **Usage & diagnostics**
* **Recommendation:** Toggle the **"Usage & diagnostics"** setting **OFF**.
* **Why:** Turning this off prevents your device from periodically sending system performance and usage data back to Google, reducing the overall amount of non-essential data your phone transmits.

---

## **Android**

### 1. Audit App Permissions via the Privacy Dashboard

Modern Android versions feature a **Privacy Dashboard** that provides a clear
overview of which sensitive permissions (like location, camera, and microphone)
have been used recently and by which apps. This is the single most effective
way to audit app behavior.

* **Setting:** `Settings` > `Security & privacy` (or just `Privacy`) > **Privacy Dashboard** > `Permission manager`
* **Recommendation:** Regularly check the dashboard to see which apps accessed your Camera, Microphone, and Location in the last 24 hours. For any suspicious app, tap it in the **Permission Manager** and restrict its access to **"Allow only while using the app"** or **"Don't allow."**
* **Why:** This allows you to catch and stop apps (especially free games or utilities) that are improperly accessing sensitive hardware in the background when they shouldn't be.

### 2. Delete/Reset Your Advertising ID and Limit Ad Personalization

Google uses a unique, resettable advertising ID (AAID) tied to your device to
track your activity across apps for targeted advertising. You can delete this
ID and opt out of personalization.

* **Setting:** `Settings` > `Google` > `Ads` (or `Security & privacy` > `Privacy Controls` > `Ads`)
* **Recommendation:** Tap **"Delete advertising ID"** and then ensure the toggle for **"Opt out of Ads Personalization"** (or a similar phrase) is **ON**.
* **Why:** Deleting the ID instantly severs the link between your historical activity data and your current device profile. Opting out tells apps and advertisers not to use any ID (even a new one) to build personalized user profiles for ad delivery.

### 3. Implement Auto-Delete for Google Account Activity

Even after adjusting local device settings, Google still tracks your activity
across its web services (Search, Maps, YouTube) under your Google Account. You
should set up automatic deletion rules for this stored data.

* **Setting:** Go to your **Google Account** settings (either through the phone settings or a browser) > `Data & privacy` > `Activity controls`
* **Recommendation:** For **Web & App Activity** and **Location History**, choose the **"Auto-delete"** option and set the retention period to **3 months** (the shortest available period) or at least **18 months**.
* **Why:** This prevents your sensitive personal data and movement history from being permanently stored on Google's servers, ensuring the data is automatically purged after a short time.

### 4. Enable Google Play Protect and App Permission Reset

Google Play Protect is Android's built-in malware scanner, but it also handles
the security feature of auto-resetting permissions for unused apps. Both should
be confirmed as active.

* **Setting (Play Protect):** Open **Google Play Store** > Tap your **Profile Icon** > **Play Protect**.
* **Setting (Permission Reset):** `Settings` > `Apps` > `Special app access` > **Remove permissions and free up space**
* **Recommendation:** Confirm **Play Protect is active** and that the feature to **"Remove permissions if app isn't used"** is turned **ON** globally.
* **Why:** Play Protect provides a critical baseline defense against malware. The automatic permission reset is a key privacy feature that automatically revokes sensitive permissions (like location or contacts) from apps you haven't used in a few months, limiting the risk of "dormant" apps collecting data.

### 5. Disable Usage and Diagnostics Sharing

Android collects aggregated data about how you use your phone (app performance,
stability, battery life) to send back to Google for system improvements. You
can opt out of this continuous telemetry.

* **Setting:** `Settings` > `Security & privacy` > `More privacy settings` (or just `Privacy`) > **Usage & diagnostics**
* **Recommendation:** Toggle the **"Usage & diagnostics"** setting **OFF**.
* **Why:** Turning this off prevents your device from periodically sending system performance and usage data back to Google, reducing the overall amount of non-essential data your phone transmits.
