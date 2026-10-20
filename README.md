# ScreenBrief

ScreenBrief desktop installers for X2 Network staff. This repository holds installers only: no source code and no keys. You add your own Gemini key and Projects token in **Settings** after installing.

**[Download the latest version](https://github.com/craftyfm/screenbrief-releases/releases/latest)**

Requires Windows 10 or later, or macOS 13 (Ventura) or later.

## Windows

1. Download `ScreenBrief-Setup-<version>.exe` from the latest release and run it.
2. From version 0.4.7, ScreenBrief tells you when a new version is out. Click **Update now** in the sidebar, then **Restart & install**.

## Mac

1. Download the `.dmg` for your Mac:
   - Apple silicon (M1 or later): `ScreenBrief-<version>-arm64.dmg`
   - Intel: `ScreenBrief-<version>.dmg`
2. Open the `.dmg` and drag **ScreenBrief** into **Applications**. Eject the disk image and run ScreenBrief from Applications, not from the disk image.
3. ScreenBrief is not signed with an Apple developer certificate, so macOS may say it **is damaged and can't be opened** or that Apple **could not verify** it. Open **Terminal** and run this once:

   ```
   xattr -cr /Applications/ScreenBrief.app
   ```

   Then open ScreenBrief again. Run the command again after installing each new version.

   If macOS still blocks it, go to **System Settings → Privacy & Security**, scroll down and click **Open Anyway**.

On a Mac, ScreenBrief tells you when a new version is out, and **Download update** opens this page. Download and install it the same way.
