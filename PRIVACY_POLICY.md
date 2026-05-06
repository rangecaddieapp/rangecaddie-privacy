# Range Caddie — Privacy Policy

_Last updated: May 5, 2026_

Range Caddie is a personal launch monitor analytics app for the Garmin R10. This policy explains what data the app handles, where it lives, and what we do with it.

The short version: **everything stays on your device. We don't have servers. We don't collect, transmit, or sell your data.**

---

## 1. Data we collect

Range Caddie does not collect any personal information. There is no account creation, no sign-in, no analytics SDK, and no third-party tracking.

The app reads and stores the following information **locally on your iPhone** only:

- **Profile information you enter:** your name (or nickname), handedness, handicap, the clubs in your bag, and the goals you select. All entered by you, stored only on your device.
- **Imported session data:** golf shot data parsed from CSV files you choose to import. This includes per-shot metrics (carry, ball speed, smash factor, launch angle, spin rate, club path, face angle, etc.), club used, and any notes you add. The CSV file itself is read once during import; we don't keep a reference to the original file.
- **Notes you write:** any text notes you add to specific shots or sessions.
- **App preferences:** which features you've toggled on/off (e.g., excluded shots, filter selections).

All of the above is stored using iOS's standard `UserDefaults` system, in your app's private container. It is not accessible to other apps and not transmitted off your device.

## 2. Data we do NOT collect

- Your location
- Your contacts, photos, or any other device data
- Crash reports or analytics
- Identifiers, device IDs, or advertising IDs
- Any data tied to your Apple ID

## 3. Network usage

Range Caddie does not make any network requests. The app functions entirely offline. You can verify this in iOS Settings → Range Caddie → check that "Cellular Data" and "Local Network" permissions are not requested or used.

## 4. Sharing features

Range Caddie includes optional features for you to share content yourself:

- **CSV export:** generates a `.csv` file in your device's temporary storage and presents the iOS Share Sheet so you can save it, AirDrop it, or send it via Messages/Mail/Files. The file leaves the app only when you choose to share it; we don't transmit anything.
- **Session image card:** generates a summary image and presents the iOS Share Sheet. Same model — only goes where you direct it.
- **Lesson prep export:** generates a text summary and presents the iOS Share Sheet.

In all cases, the destination is chosen by you through the iOS Share Sheet. Range Caddie does not control or see what happens after that.

## 5. Importing CSV files

When you tap "Import" and pick a Garmin CSV file, the app reads the file once to extract shot data, then stores that parsed data in your app's local container. We do not keep a reference to or re-read the original file. If you want to remove the original file from your device, do so through the Files app.

## 6. Data retention and deletion

Your data stays on your device until you:

- Delete a session inside the app (swipe to delete on the home screen)
- Reset the app via Profile & Settings → "Reset onboarding" (clears profile only, sessions remain)
- Delete the app from your iPhone (clears everything)

There is no cloud backup unless you enable iCloud Backup at the iOS level, in which case `UserDefaults` may be included in your encrypted iCloud Backup per Apple's standard practices. We do not control or access this backup.

## 7. Children's privacy

Range Caddie is intended for users 13 and older. We do not knowingly collect data from children under 13. Since we collect no data at all, there is no special handling required, but we mention it for transparency.

## 8. Third-party services

Range Caddie has no third-party SDKs, no advertising networks, no analytics, and no third-party APIs. The app's only dependencies are Apple's own SwiftUI and Foundation frameworks.

## 9. Changes to this policy

If this policy ever changes (e.g., if we add a feature that requires network access), the new version will be posted at this URL with an updated "Last updated" date. We will also note material changes inside the app.

## 10. Contact

Questions about this privacy policy or about Range Caddie's data handling? Email **RangeCaddieApp@gmail.com**.

---

**Summary:** Range Caddie is a fully offline app. Your data is yours, lives on your device, and is never transmitted by us. The only ways data leaves your phone are when you explicitly tap a share/export button and choose where to send it.
