# ClipPal — Install & Usage Guide

A lightweight clipboard history tool that lives in your macOS menu bar.

---

## 1. Installation

1. Download `ClipPal.dmg`.
2. Double-click to open, then drag **ClipPal** into the **Applications** folder.
3. Eject the disk image from the Finder sidebar. Done.

---

## 2. First Launch (Important)

Because ClipPal is independently developed and not notarized by Apple, macOS will block it the first time.

1. Open **Finder → Applications**.
2. **Right-click ClipPal** and choose **Open**.
3. If you still see "cannot verify the developer", go to **System Settings → Privacy & Security**, scroll to the bottom, and click **Open Anyway**. Enter your password.

> This step only needs to be done once. After that, double-click works normally.

---

## 3. Grant Accessibility Permission (for auto-paste)

1. Open **System Settings → Privacy & Security → Accessibility**.
2. Find **ClipPal** in the list and toggle it on.
3. If you don't see it, click the **+** button and add ClipPal from Applications.
4. Restart ClipPal after granting (menu bar icon → Quit, then reopen).

> Without this permission, clicking a history item only copies it to the clipboard — you'll need to press `⌘V` manually. With it, pasting is fully automatic.

---

## 4. Getting Started

Press the default shortcut **`⌃⌘V`** (Control + Command + V) to bring up the history panel.

![History panel](history.png)

| Action | Shortcut |
| :--- | :--- |
| Navigate | `↑` `↓` |
| Paste selected | `⏎` |
| Quick paste item N | `⌘1` – `⌘9` |
| Delete selected | `⌘⌫` |
| Close panel | `⎋` |
| Paste with mouse | Click any item |

- **Search**: Just start typing after opening the panel. Case- and diacritic-insensitive.
- **Right-click menu**: Pin to top or delete.
- **Auto deduplication**: Copying the same content again just moves it to the top.
- **Privacy**: Concealed clipboard content from password managers is ignored by default.

---

## 5. Menu Bar & Settings

Click the menu bar icon for more options:

![Menu bar](menu.png)

Open **Settings...** to customize:

![Settings](settings.png)

- History size (30 / 50 / 100 / custom 5–500)
- Global shortcut
- Auto-paste, sound, ignore concealed
- **Launch at login**
- Language (System / 中文 / English)
- Panel transparency

---

## FAQ

**Where is my history stored?**
`~/Library/Containers/com.lipingweipersonalteam.ClipPal/Data/Library/Application Support/ClipPal/`

**The shortcut doesn't work.**
It may conflict with another app. Try a different combination in Settings.

**Auto-paste doesn't work.**
Check **System Settings → Privacy & Security → Accessibility** and make sure ClipPal is enabled.

**How do I uninstall completely?**
Quit ClipPal, delete it from Applications, remove the data folder above, then remove ClipPal from **System Settings → General → Login Items & Extensions**.

---

© ClipPal
