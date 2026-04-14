# Privacy Policy

**App:** LOADOUT
**Developer:** Spectrum Works
**Effective Date:** April 12, 2026
**Last Updated:** April 12, 2026

---

## 1. Overview

LOADOUT is a firearm maintenance and ammo inventory tracking application. This policy describes what data the app collects, how it is stored, and under what circumstances it leaves your device.

---

## 2. Data Collected

LOADOUT collects only data that you explicitly enter:

- Firearm details (name, make, model, caliber, type, divisions, round count, acquisition date, notes)
- Maintenance tasks and completion history
- Ammunition inventory (caliber, brand, load description, round count)
- Range session logs (date, firearm, rounds fired, ammo used, notes)
- Spare parts inventory
- App settings and preferences

**No data is collected automatically.** LOADOUT does not collect analytics, crash reports, device identifiers, location data, or any information beyond what you type into the app.

---

## 3. Data Storage

### Local Storage
All data is stored locally on your device in a SQLite database. This data remains on your device unless you explicitly enable cloud sync (see below) or use the export feature.

### Cloud Sync (Optional)
If you choose to create an account and enable cloud sync, your data is transmitted to and stored on [Supabase](https://supabase.com) — a third-party cloud database platform. The following applies:

- Data is associated with your account via a user ID
- Transmission occurs over HTTPS
- Only the data you have entered into the app is synced — no device metadata is transmitted
- You may delete your account and all associated remote data at any time from the Settings screen
- Supabase's own privacy policy governs how they handle data on their infrastructure: [https://supabase.com/privacy](https://supabase.com/privacy)

Cloud sync is entirely optional. The app is fully functional without an account.

---

## 4. Data Export

The export feature generates CSV files from your local data and opens your device's share sheet. You control where those files are sent. Spectrum Works does not receive exported files.

---

## 5. Push Notifications

If you enable push notifications for maintenance tasks, the app schedules local notifications on your device. These are processed entirely on-device by the operating system. No notification content is transmitted to any server.

---

## 6. Account and Authentication

Account creation and authentication are handled by Supabase Auth. Your email address is used solely for account identification and is not shared with third parties by Spectrum Works. Refer to Supabase's privacy policy for details on how authentication credentials are stored and processed.

---

## 7. Third-Party Services

| Service | Purpose | Policy |
|---------|---------|--------|
| Supabase | Optional cloud sync and authentication | [supabase.com/privacy](https://supabase.com/privacy) |

No advertising SDKs, analytics platforms, or tracking libraries are included in this app.

---

## 8. Data Retention and Deletion

- **Local data** can be deleted by uninstalling the app or clearing app data in your device settings.
- **Cloud data** can be deleted by deleting your account from Settings → Account → Delete Account. This permanently removes all synced data from Supabase servers.

---

## 9. Children's Privacy

LOADOUT is not directed at children under the age of 13 and does not knowingly collect information from children.

---

## 10. Changes to This Policy

If this policy changes materially, the updated version will be posted with a revised effective date. Continued use of the app after changes are posted constitutes acceptance of the updated policy.

---

## 11. Contact

Questions about this privacy policy can be directed to Spectrum Works at developer@loadoutapp.cloud.
