# Privacy Policy for VehicleLog

**Effective Date:** November 18, 2026 
**Developer:** Frolody Project 
**Contact Email:** frolody.band@gmail.com

Thank you for using **VehicleLog** ("the App"). Your privacy is important to us. This Privacy Policy explains how VehicleLog handles your personal records locally on your device and how third-party services integrated into the App (Google ML Kit and Google AdMob) process limited technical and advertising data.

---

## 1. Local-First Storage of Your Vehicle Records

VehicleLog is designed to store your personal vehicle records locally on your device. We do not require you to register an account, and we do not operate developer-owned servers to collect, store, or sell your personal vehicle records.

All information you manually enter into the App—including your display name, vehicle details (name, brand, model, year, license plate, notes), odometer entries, service and expense logs, component tracking records, maintenance schedules, document records, currency/unit/language settings, and attached photos—is stored **locally on your device**.

---

## 2. Device Permissions We Request

Depending on the features you use, the App may request the following permissions:

- **Camera (`CAMERA`)**  
  Used only when you capture photos of your vehicles, receipts, or documents inside the App.
- **Photos & Media (`READ_MEDIA_IMAGES` / `READ_EXTERNAL_STORAGE`)**  
  Used only when you select existing images from your device gallery for vehicles, receipts, or documents.
- **Notifications & Boot Completed (`POST_NOTIFICATIONS`, `RECEIVE_BOOT_COMPLETED`)**  
  Used solely to schedule and display local maintenance or document expiration reminders on your device, including re-scheduling them after a device restart.
- **Network & Advertising (`INTERNET`, `ACCESS_NETWORK_STATE`, `com.google.android.gms.permission.AD_ID`)**  
  Used by integrated Google SDKs to display ads via Google AdMob, manage user consent via Google’s User Messaging Platform (UMP), and download optional on-device AI modules when needed.

You can manage or revoke runtime permissions at any time through your Android device settings.

---

## 3. On-Device Image Processing (Google ML Kit)

VehicleLog uses Google ML Kit for optional convenience features:

1. **Receipt Text Recognition (OCR):** Uses `com.google.mlkit:text-recognition` to read receipt text on your device.
2. **Optional Background Removal:** Uses `com.google.android.gms:play-services-mlkit-subject-segmentation` to remove backgrounds from vehicle photos on your device with a preview before saving.

Images processed by ML Kit stay on your device and are not uploaded to Google servers for model inference. However, Google ML Kit and Google Play Services may download optional on-device model files when required and collect limited technical diagnostic and per-installation telemetry as governed by [Google’s Privacy Policy](https://policies.google.com/privacy) and the [ML Kit Terms of Service](https://developers.google.com/ml-kit/terms).

---

## 4. Advertising (Google AdMob & User Consent)

VehicleLog displays banner and interstitial ads using **Google AdMob** (Google Mobile Ads SDK) and presents consent notices where required using **Google’s User Messaging Platform (UMP)**.

To deliver, measure, and protect ads against fraud, Google AdMob may automatically collect and share certain data, including:
- **Device or other identifiers** (such as the Android Advertising ID / AAID and App Set ID)
- **Approximate location** (inferred from your IP address)
- **App interactions** (such as ad impressions, taps, and basic ad interaction events)
- **App info and performance** (such as crash logs and SDK diagnostics)

All data transmitted by Google AdMob is encrypted in transit (HTTPS). Depending on your region and consent choices, AdMob may serve personalized or non-personalized ads.

You can control ad personalization and your Advertising ID at any time by:
- Updating your choice when prompted by the consent form (where applicable), and/or
- Going to **Android Settings → Google → Ads** (or **Privacy → Ads**) to reset or delete your Advertising ID or opt out of ads personalization.

For more details on how Google uses information from apps that use its advertising services, see [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites) and [Google’s Privacy Policy](https://policies.google.com/privacy).

---

## 5. Backup & Data Deletion

- **Manual Backup & Restore:** You may export or restore a backup file of your local App data using the built-in Backup & Restore feature. Exported files are saved to the location you select.
- **Android Auto Backup:** Standard Android backup (`allowBackup`) may back up local app data to your personal Google account depending on your device's system backup settings.
- **Your Control & Deletion:** You can edit or delete vehicles, records, components, documents, and photos directly inside the App. Uninstalling the App or clearing its storage in Android Settings removes all locally stored records on your device.

---

## 6. Children’s Privacy

VehicleLog is a general utility application and is not directed to children under the age of 13 (or the minimum age required in your jurisdiction). We do not knowingly collect personal information from children.

---

## 7. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in features, SDKs, or legal requirements. Updates will be posted on this page with a revised **Effective Date**.

---

## 8. Contact Us

If you have any questions about this Privacy Policy, please contact: frolody.band@gmail.com
- **Developer:** Frolody Project  
- **Email:** frolody.band@gmail.com  
- **Location:** Indonesia
