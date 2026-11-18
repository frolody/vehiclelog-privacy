# Privacy Policy for VehicleLog

**Effective Date:** Effective Date, e.g., November 18, 2026
**Developer:** Frolody Project  
**Contact Email:** frolody.band@gmail.com

Thank you for using **VehicleLog** ("the App"). Your privacy is important to us. This Privacy Policy explains what information the App accesses, how it is processed and stored, and your rights regarding your data.

---

## 1. Overview & Local-First Storage

VehicleLog is designed as an offline-first personal vehicle maintenance and expense tracker. We do not require you to create an account, and we do not operate developer-owned servers to collect, store, or sell your personal vehicle records.

All records you enter into the App—including your display name, vehicle details (name, brand, model, year, license plate, notes), odometer logs, service and expense records, component tracking data, reminders, document records, currency/unit/language preferences, and attached photos—are stored **locally on your device**.

---

## 2. Information & Device Permissions We Use

Depending on the features you choose to use, the App may request the following permissions on your Android device:

- **Camera (`CAMERA`)**  
  Used only when you capture photos of your vehicle, maintenance receipts, or vehicle documents directly inside the App.
- **Photos / Media Storage (`READ_MEDIA_IMAGES` / `READ_EXTERNAL_STORAGE`)**  
  Used only when you choose to select existing photos from your device gallery for vehicle profiles, receipts, or documents, or when restoring/exporting files you choose.
- **Notifications & Boot Receiver (`POST_NOTIFICATIONS`, `RECEIVE_BOOT_COMPLETED`)**  
  Used solely to schedule and display local maintenance or document expiration reminders on your device, including re-scheduling local reminders after your device restarts.

You can revoke any of these permissions at any time through your Android device settings.

---

## 3. On-Device Image Processing & Google ML Kit

VehicleLog includes optional features powered by Google ML Kit:

1. **Receipt Text Recognition (OCR):**  
   Uses Google ML Kit Text Recognition (`com.google.mlkit:text-recognition`) to scan receipt images on your device and prefill expense or service fields.
2. **Optional Vehicle Photo Background Removal:**  
   Uses Google ML Kit Subject Segmentation (`com.google.android.gms:play-services-mlkit-subject-segmentation`) to remove photo backgrounds on your device with a preview before saving.

Your photos are processed locally on your device. However, Google ML Kit and Google Play Services may download required optional AI model files (such as the subject segmentation module) to your device when needed and may collect limited technical diagnostic or usage telemetry as governed by [Google’s Privacy Policy](https://policies.google.com/privacy) and the [ML Kit Terms of Service](https://developers.google.com/ml-kit/terms).

---

## 4. Backup, Export & Data Sharing

- **Manual Backup & Restore:** You may export or import a backup file of your local App data using the built-in Backup & Restore feature. Any exported file is saved where you choose on your device or third-party storage provider.
- **Android System Backup:** Android's standard OS backup (`allowBackup`) may back up local app data to your personal Google account depending on your device's Android backup settings.
- **No Sale or Advertising Tracking:** We do not sell, rent, or trade your data, and the App does not include third-party advertising SDKs.

---

## 5. Data Retention & Deletion

Because your data is stored locally on your device, you have full control over it at all times:

- You can edit or delete individual vehicles, records, components, documents, and photos directly within the App.
- Uninstalling the App or clearing App storage in Android Settings permanently removes all locally stored App data (except any backup files you manually exported or system backups managed by your Android OS settings).

---

## 6. Children’s Privacy

VehicleLog is a general utility application and is not directed to children under the age of 13 (or the applicable minimum age in your jurisdiction). We do not knowingly collect personal information from children.

---

## 7. Changes to This Privacy Policy

We may update this Privacy Policy from time to time (for example, when adding new features or updating third-party libraries). Any changes will be posted on this page with an updated **Effective Date**.

---

## 8. Contact Us

If you have any questions or concerns about this Privacy Policy, please contact us at: frolody.band@gmail.com

- **Developer:** Frolody Project
- **Email:** frolody.band@gmail.com
