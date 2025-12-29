# 📦 Pocket Apps

Personal app store for Mudita Kompakt and other e-ink Android devices.

## 🚀 How it works

1. Install the **Pocket Apps** store app on your device (one-time cable setup)
2. Connect to WiFi
3. Browse, download, and install apps wirelessly
4. Updates are automatic

## 📱 Available Apps

| App | Description | Status |
|-----|-------------|--------|
| 🃏 Scoundrel | Roguelike card game | ✅ Available |
| 🎮 Kompakt Games | Game collection (10+ games) | 🔜 Coming Soon |
| 🔐 Kompakt Crypto | Encryption & password tools | 🔜 Coming Soon |

## 📂 Repository Structure

```
pocket-apps/
├── apps.json          # App catalog
├── apks/              # APK files
│   ├── scoundrel-1.0.0.apk
│   └── ...
└── README.md
```

## 🔧 For Developers

### Adding a new app

1. Add your APK to the `apks/` folder
2. Update `apps.json` with your app info:

```json
{
  "id": "your-app-id",
  "name": "Your App Name",
  "icon": "🎯",
  "version": "1.0.0",
  "size": "100 KB",
  "author": "Your Name",
  "category": "Category",
  "shortDesc": "Short description",
  "description": "Full description...",
  "changelog": "v1.0.0 - Initial release",
  "apkFile": "your-app-1.0.0.apk",
  "minAndroid": "8.0"
}
```

## 📜 License

MIT License - Feel free to fork and create your own app store!

---

Made with ❤️ for minimalist tech enthusiasts
