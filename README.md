# Treasury releases

Releases of the **Treasury offline Android app**: signed app files (APK) and `releases.json`, which the app reads to offer updates.

- No source code and no data are kept here.
- Each release lists its SHA-256 fingerprint; the app refuses a download that doesn't match.
- Android only installs an update signed with the same key as the installed app.
- Signing certificate SHA-256: `44:53:8F:43:4D:1B:9C:72:21:7E:98:79:31:1C:CE:12:59:A9:B7:AA:52:6F:E0:14:B6:D7:ED:B9:D4:5C:A8:DE`

## Installing Treasury on an Android phone

Treasury keeps your money records **only on your phone**, encrypted with your password. There's no account and no server. This guide installs it from the official releases page.

You need an Android phone (Android 7 or newer) and about 15 MB of space.

### 1. Download

1. On the phone, open **https://github.com/jessedtan-dev/treasury-releases/releases**.
2. Under the newest version, tap **treasury-X.Y.Z.apk** (for example `treasury-1.0.0.apk`) to download it.

Only download Treasury from that page. A copy from anywhere else could be a fake.

### 2. Install

1. Open the downloaded file (from the download notification, or Files → Downloads).
2. Android asks to allow your browser (or Files) to **install unknown apps**. Tap **Settings**, switch **Allow from this source** on, then go back.
3. Tap **Install**. If Google Play Protect asks about an unknown app, tap **More details → Install anyway**. It does this for any app not from the Play Store.
4. Once it's installed, you can switch **Allow from this source** off again for your browser.

### 3. Set up

1. Open **Treasury** and read the warning: there's no "forgot password" service.
2. Choose a **password** (or a passphrase of 4+ words), then a **PIN** for everyday unlocking.
3. **Write down the recovery key** it shows, or tap **Email it to myself**. You type two parts of it back to finish.
4. Optional: fingerprint unlock, and the **"+ Add entry" widget** (long-press the home screen → Widgets → Treasury).

**Keep the password and the recovery key safe.** If you lose both, nobody can open your data, including us.

### 4. Updates

- Settings → App version → **Check for updates**, or wait for the quiet daily check.
- It shows what's new, then downloads the update, checks its fingerprint, makes a backup and opens Android's installer. Tap **Update**.
- The first time, Android asks to allow Treasury to install apps: switch it on, then go back.
- Updates only install over an app signed with the same key, so a fake update can't replace the real app.

### 5. Backups

- Settings → Backups. **Back up now** saves an encrypted file through the Share menu (Drive, Files, email).
- A weekly automatic backup also goes to Documents/Treasury on the phone (the newest 4 are kept).
- **New phone:** install Treasury, set it up, then Settings → Backups → **Restore** your backup file. A backup from the web version restores the same way.

