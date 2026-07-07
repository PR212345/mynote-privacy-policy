# Privacy Policy for My Note

**Last Updated:** July 7, 2026

Your privacy is the absolute core of **My Note**. This application is designed to give you 100% control and ownership over your personal thoughts, notes, and tasks. Unlike standard note-taking applications, My Note operates on a **zero-network, offline-first, local-only architecture**.

---

## 1. Zero Network Access (No Data Collection)

* **No Network Permission:** My Note does not request or require the Android `INTERNET` permission. 
* **Zero Transmission:** The app has no way to transmit, upload, or share any of your notes, pins, or settings to external servers, cloud providers, analytics packages, or third-party developers.
* **No Tracking:** We do not compile analytics, tracking metrics, usage statistics, or user behavior tracking. 

## 2. On-Device Local Storage & Security

* **Database Encryption:** All notes, checklist items, and folders are stored locally on your device in an encrypted Room database secured by **SQLCipher** using hardware-backed cryptography key management.
* **Authentication Data:** If you enable the App Lock or individual note locks, the PIN is hashed locally using a one-way cryptographically secure SHA-256 algorithm. We do not store or transmit your raw PIN.
* **Biometric Auth:** Biometric verification utilizes Android's secure system-level BiometricPrompt API. Your biometric data (fingerprints, face scan data) is kept securely within the hardware security module (TEE/Secure Enclave) of your device and is never accessible to the app.

## 3. Local Backups and Portability

* **Encrypted Backups:** You can generate backups of your notes. Backups are exported as locked, encrypted files.
* **Device Portability:** These backup files can be transferred by you (using USB, local share, or any method of your choice) to a new device and imported back into the My Note application.
* **Sovereignty:** Because we do not run servers, if you lose your device and do not have a backup file, we cannot recover your notes. You are in complete control of your data.

## 4. Permissions Used

The application requests only the minimum necessary system permissions to function offline:
* **POST_NOTIFICATIONS / SCHEDULE_EXACT_ALARM / USE_EXACT_ALARM:** Used exclusively to trigger reminders/notifications for notes and tasks you have set alarms for.
* **RECEIVE_BOOT_COMPLETED:** Used to reschedule your active note alarms when you restart your device.
* **USE_BIOMETRIC:** Used to allow you to unlock your app or secure notes using your device's biometric authentication.
* **READ/WRITE_EXTERNAL_STORAGE:** (On older Android versions) Used to export and import backup files.

## 5. Contact Us

Since we do not collect any user data or have a server backend, we have no way to identify you. If you have questions or feedback about My Note, please feel free to reach out to us at:
* **Email:** dragonwarriorworks@gmail.com
