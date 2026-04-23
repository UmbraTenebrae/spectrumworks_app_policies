# Privacy Policy for Arcmin

**Effective date:** April 23, 2026
**App:** Arcmin — exterior ballistics solver
**Publisher:** Spectrum Works
**Contact:** developer@spectrumworks.online

---

## TL;DR

Arcmin is a calculator. It does not have an account system, does not phone home with your shot data, does not show ads, and does not include third-party analytics or tracking SDKs. Everything you enter — rifle profiles, ballistic coefficients, DOPE records, atmospheric conditions, location — stays on your device.

The only data leaving your device is (a) the system font fetch from Google Fonts on first launch, and (b) anything you yourself choose to share via your device's share sheet (e.g. exporting a range-card image or a backup file).

---

## 1. Information we collect

**On your device only.** Arcmin stores the following locally, in your device's app-private storage:

- **Rifle profiles** you create: name, bullet specifications, ballistic coefficient, muzzle velocity, sight height, zero range, drag model, custom drag curves, saved zero presets, saved load presets, scope reticle selection.
- **DOPE records** you record after shots: range, observed drop and windage, conditions at the time, notes.
- **Bullet BC presets** you save (the bundled library and any user additions).
- **App settings:** unit system (imperial / metric), angular unit (mil / MOA), and similar preferences.
- **Whether you've completed the first-run welcome tour.**

This information is only stored on your device. It is not transmitted to us or any third party.

## 2. Sensor and location access

When you tap the in-app buttons that read from your device's sensors, Arcmin performs a single, on-demand read and writes the value into the corresponding form field. No continuous tracking, no background recording.

- **Barometric pressure** (when you tap "Read barometer") — used to fill the atmosphere pressure field. Stored only as the single numeric value you see in the field. Does not require a permission on Android.
- **Latitude only** (when you tap "Read GPS") — used to fill the shooter-latitude field for the Coriolis correction. Arcmin requests "approximate" location accuracy and reads only the latitude. Longitude, altitude, speed, and bearing are read by the OS but not stored or used. The latitude itself is stored only as the single numeric value you see in the field.
- **Accelerometer** (when you use the inclinometer or bubble-level dialog) — used to estimate scope cant and line-of-sight angle in real time while the dialog is open. Readings are not stored after you close the dialog.

Sensor readings never leave your device.

## 3. Information you choose to share

Arcmin's "Share range card" and backup-export features hand a file (PNG image or JSON bundle) to your device's system share sheet. You — not Arcmin — pick the destination (email, messaging app, cloud storage, etc.). Arcmin does not see or transmit this data; the destination app receives the file directly from the OS.

If you export a backup bundle, that bundle contains your rifle profiles, BC presets, DOPE records, and settings. Treat the file with the same care you would any document containing personal preferences.

## 4. Network connections

Arcmin makes the following network requests:

- **Google Fonts** (fonts.gstatic.com) — on first launch, the `google_fonts` library fetches the Inter and JetBrains Mono font files. Once cached, no further font-related network calls occur. The fetch is governed by [Google's Privacy Policy](https://policies.google.com/privacy). Arcmin sends no identifiers, account info, or personal data with this request — only the standard HTTP request needed to retrieve the font file.
- **Google Play Services** — if you installed Arcmin from the Google Play Store, Play Services may communicate with Google for app distribution, update checks, and crash reporting at the OS level. This is governed by Google's policies, not Arcmin.

Arcmin itself does not connect to any backend operated by Spectrum Works. There is no Arcmin server.

## 5. Analytics, advertising, and tracking

Arcmin does **not** include:

- Analytics SDKs (no Firebase Analytics, Google Analytics, Amplitude, Mixpanel, etc.)
- Advertising SDKs
- Crash reporting SDKs (no Crashlytics, Sentry, etc.)
- Attribution / install tracking SDKs
- Social-media SDKs
- Any other third-party data-collection libraries

We do not assign you a user ID or device identifier of any kind.

## 6. Data sharing with third parties

We do not share, sell, rent, or transfer your data to anyone. There is no third-party data sharing because there is no transmission off your device in the first place (excepting the Google Fonts fetch and any export action you initiate, both described above).

## 7. Data retention and deletion

Because your data lives only on your device, you control its lifecycle:

- **To delete a single record** — use the in-app delete actions on rifle profiles, BC presets, DOPE records, and saved zeros.
- **To delete everything** — uninstall Arcmin. On Android and iOS, uninstalling the app removes its private storage, taking all rifle profiles, presets, DOPE records, and settings with it.
- **To migrate to a new device** — use Arcmin's backup-export feature to produce a JSON bundle, then import it on the new device.

We retain no copies of your data because we never received any.

## 8. Children's privacy

Arcmin is a tool for exterior-ballistics calculations and is intended for adult shooters, hunters, and ballistic professionals. The app is not directed at children under 13 (or the equivalent minimum age in your jurisdiction). We do not knowingly collect data from anyone, of any age — see Section 1 — but we explicitly state that the app is not designed for or marketed to children.

## 9. Security

Your data is stored using your device's standard app-private storage. Access is restricted by the operating system to Arcmin itself. We recommend enabling device-level encryption (default on modern Android and iOS) and a screen-lock PIN/biometric to protect your data at rest.

Backup files you export are plain JSON. If you store these in cloud storage or share them, the security of those copies is governed by the destination service.

## 10. Changes to this policy

We may update this Privacy Policy from time to time. Material changes will be communicated by updating the "Effective date" at the top of this document and, where appropriate, by an in-app notice on next launch after the change. Continued use of Arcmin after a policy update constitutes acceptance of the updated terms.

## 11. Your rights

Because we do not collect or store your data on our servers, traditional data-subject-access requests (GDPR Article 15, CCPA right-to-know, etc.) have nothing for us to disclose — there is no record of you to retrieve. If you have questions about the data Arcmin processes locally on your device, see Sections 1–3 above, or contact us using the address at the top of this policy.

## 12. Contact

For privacy-related questions, write to **developer@spectrumworks.online**.

---

*Arcmin is published by Spectrum Works.*
