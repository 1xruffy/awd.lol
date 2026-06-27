# Profile Page — Setup Guide

## Folder structure

Place these files next to your `index.html`:

```
/
├── index.html          ← the page itself
└── assets/
    ├── bg.png          ← background image (any size, will fill/cover)
    ├── pfp.png         ← default profile picture (shown on load)
    ├── spotify.png     ← Spotify icon (42×42px recommended)
    └── roblox.png      ← Roblox icon (42×42px recommended)
```

---

## How to customise

| Feature | How |
|---|---|
| **Background** | Replace `assets/bg.png` — any image, it covers the whole screen |
| **Profile picture** | Replace `assets/pfp.png` OR hover the circle and click the pencil to upload via browser |
| **Display name** | Click the green pencil icon next to your name to edit inline |
| **Spotify link** | Right-click the Spotify icon → paste your Spotify profile URL |
| **Roblox link** | Right-click the Roblox icon → paste your Roblox profile URL |
| **Discord** | Click the Discord card → fill in username, avatar URL, and status |

> **Tip:** All changes auto-save in your browser's localStorage, so they persist across refreshes.

---

## Discord avatar URL

1. Open Discord
2. Click your profile picture → "Edit Profile"
3. Or right-click your avatar in a server → "Copy Image Address"
4. Paste that URL into the "Avatar image URL" field in the Link Discord popup

---

## Hosting

Open `index.html` directly in a browser — no server needed for local use.
For online hosting, upload the whole folder to GitHub Pages, Netlify, or any static host.
