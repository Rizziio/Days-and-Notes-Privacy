# Days & Notes Privacy Policy

**App:** Days & Notes (Android package `com.calendarnotes.app`)
**Version covered:** 1.0.0
**Developer:** Tarenix Technologies (legal entity: Tarenix LLC)
**Contact:** info@tarenix.com
**Effective date:** November 21, 2026
**Policy URL:** https://rizziio.github.io/Days-and-Notes-Privacy/

## 1. Summary

Days & Notes is a local-first calendar notes app. It has no account, no login, no advertising, no analytics or tracking, and no Days & Notes server. **Tarenix does not collect, receive, or have access to your notes, images, or any other personal data through the app.** Your data stays on your device unless you choose to move it (for example by creating a backup file) or Android's own backup features copy it (see Sections 5 and 6).

## 2. Information the app handles

Everything below is created by you and is stored only on your device, in app-private storage:

| Data | Purpose | Where it lives |
|---|---|---|
| Note text for each calendar date | Provide the app | App-private database on your device |
| Images you add to notes (from the Android Photo Picker or the camera) | Show images inline in notes | Copies stored in app-private storage; the original is not modified |
| Recovery History (earlier versions of notes and images) | Let you restore earlier versions; kept for 14 days | App-private database/storage on your device |
| App Lock settings (on/off, timeout) | Remember your App Lock choice | A private settings file on your device |

The app does not ask for your name, email address, phone number, location, contacts, or any device or advertising identifier, and does not read your contacts, location, microphone, or other apps' data.

## 3. No collection, transmission, or sharing by Tarenix

Based on review of the app's source code, manifest, and dependencies for version 1.0.0:

- The app contains no network code and no third-party SDKs for analytics, advertising, crash reporting, or attribution.
- Notes, images, search queries, Recovery History, and backup contents are not sent to Tarenix or to any third party by the app.
- We do not sell or share personal data, and the app does not include ads or tracking.
- The app does not write note text, image contents, or search contents to logs.

Because Tarenix does not receive your data, we cannot access, recover, or delete your notes on your behalf. You control your data directly in the app.

## 4. Permissions and system features

- **Photo Picker:** To add an image, the app uses the Android Photo Picker, which lets you pick specific images without granting the app access to your whole photo library. The selected image is copied into private app storage.
- **Camera:** If you choose to take a photo, the app opens your device's camera app. The app does not itself request the camera permission. The captured photo is copied into private app storage; a temporary file is used during capture.
- **App Lock (optional):** Off by default. When enabled, the app uses Android's built-in biometric / device-credential prompt (the app declares the standard Android biometric permissions for this purpose only). Authentication is handled entirely by Android. Days & Notes does not receive, see, or store your fingerprint, face data, PIN, pattern, or password. While App Lock is enabled the app blocks screenshots and hides its content in the recent-apps view.
- **File access for backups:** Backup and restore use Android's system file picker. The app can access only the file or location you select.

## 5. Android-managed backup and device transfer

The app allows Android's standard backup and device-transfer features to include its **notes database and note images** (not App Lock settings, caches, or temporary files). When Android backup is on (for example, Google backup on your device), Android may store this data in your Google account's backup storage, and may transfer it to a new device when you set one up.

- This is performed by Android and Google under your device and account settings, not by Days & Notes; Tarenix does not receive or access this data.
- Google's handling of backup data is governed by Google's own terms and privacy policy.
- It is best-effort and not guaranteed. You can control or turn it off in your device's Android system backup settings.
- Because App Lock settings are not backed up, App Lock is Off on a restored device until you enable it again.

## 6. Backups you create

In **Settings → Backup & Restore → Create Backup** you can save a backup file to a location you choose through the Android system Save dialog. A backup contains your current notes, images, the last 14 days of Recovery History, dates and timestamps, and format/version information. It does not include Undo/Redo state, search history, caches, App Lock settings, or device-identifying information.

- **The backup file is not encrypted by the app.** Anyone who can access the file can read it. If you save it to a cloud storage provider, email it, or share it, that provider or recipient handles it under their own terms and privacy policy. You are responsible for where you store it.
- Creating a new backup does not delete older backup files. You manage and delete them yourself.
- Restoring checks the file first. Merge is the default; Replace overwrites current notes and requires confirmation.

## 7. Retention and deletion

- **Current notes and images:** kept on your device until you delete them or remove the app's data. They do not expire automatically.
- **Recovery History:** kept for 14 days and then removed. You can also permanently delete a recovery version or all Recovery History in the app (with confirmation).
- **Removed images:** may remain in private storage temporarily while a valid Recovery version still needs them, then are cleaned up.
- **Clear Cache** does not remove notes or active images. **Clear Storage/Data** removes local app data. **Uninstalling** removes the app and its local data, but not backup files you saved elsewhere or any copies held by Android/Google backup.
- **Backups outside the app** (your own files, and Android/Google backup copies) must be deleted by you through your file manager, storage provider, or device/Google account backup settings.

Since Tarenix holds no copy of your data, there is nothing for us to delete on our systems.

## 8. Security

Notes and images are stored in app-private storage that other apps cannot normally read, and optional App Lock adds Android-native authentication. No method of storage or backup is perfectly secure or guaranteed against loss; keep your own backup of important notes.

## 9. Children's privacy

Days & Notes is not directed to children and does not knowingly collect personal information from anyone, including children.

## 10. Changes to this policy

If the app's data practices change (for example if a feature that uses a network service is added), this policy will be updated before the change is released, and the effective date will change. The updated policy will be posted at the URL above.

## 11. Contact

Questions about this policy: **info@tarenix.com**
Tarenix Technologies (Tarenix LLC)
