<div align="center">

<img src="icon-192.png" width="80" height="80" alt="SyncPad Logo" />

# SyncPad

### Sync clipboard between any devices — instantly ⚡

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20App-4af0c4?style=for-the-badge&logo=github)](https://Tushar-1001.github.io/syncpad)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)](https://github.com/Tushar-1001/syncpad/pulls)

<br/>

**No login. No app install. No setup. Just a 6-digit code.**

Copy text on your phone → paste it on your PC in seconds 🔥

<br/>

![SyncPad Demo](https://Tushar-1001.github.io/syncpad/demo.gif)

</div>

---

## ✨ Features

- 🔢 **6-digit sync code** — connect any two devices instantly
- ⚡ **Real-time sync** — text appears on other device as you type
- 📱 **Works everywhere** — Android, iPhone, Windows, Mac, Linux
- 🔒 **No login required** — zero account, zero signup
- 📦 **No app install** — just open the website
- ⏱️ **Auto-expire** — sessions delete after 15 minutes
- 🌐 **PWA support** — install on home screen like a native app
- 🆓 **100% Free** — forever

---

## 🚀 How It Works

```
Step 1 — Open syncpad on Device 1 (PC)
         Click "Create Code" → get a 6-digit code (eg. 482910)

Step 2 — Open syncpad on Device 2 (Mobile)
         Enter the same code → click "Join Session"

Step 3 — Type anything on either device
         It syncs instantly on the other ⚡
```

---

## 🎯 Use Cases

| Situation | How SyncPad Helps |
|---|---|
| 📋 Copy text from phone to PC | Paste code → done in 5 sec |
| 🔗 Share a link mobile → laptop | No WhatsApp needed |
| 📝 Transfer notes between devices | Real-time, instant |
| 🧑‍💻 Share code snippets quickly | Works for developers too |
| ✈️ No cable, no Bluetooth needed | Just internet + browser |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, Vanilla JS |
| Backend | Firebase Realtime Database |
| Hosting | GitHub Pages |
| PWA | Service Worker + Web Manifest |

---

## 📦 Self Host (Optional)

Want to self-host your own SyncPad?

### Step 1 — Clone
```bash
git clone https://github.com/Tushar-1001/syncpad.git
cd syncpad
```

### Step 2 — Add Firebase config
Replace the Firebase config in `index.html` with your own:
```js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  databaseURL: "https://YOUR_PROJECT-default-rtdb.firebaseio.com",
  projectId: "YOUR_PROJECT_ID",
  ...
};
```

### Step 3 — Deploy
```bash
git add .
git commit -m "my syncpad"
git push
```

Enable GitHub Pages → your app will be live! ✅

---

## 🔒 Privacy & Security

- ✅ No user data stored permanently
- ✅ Sessions auto-delete after 15 minutes
- ✅ Only people with the code can access a session
- ✅ No tracking, no analytics, no ads
- ✅ Open source — verify yourself!

---

## 🤝 Contributing

Contributions are welcome! 🙌

```bash
# Fork → Clone → Make changes → Submit PR
git checkout -b feature/amazing-feature
git commit -m "Add amazing feature"
git push origin feature/amazing-feature
```

**Ideas for contribution:**
- [ ] QR code share feature
- [ ] Multiple clipboard slots
- [ ] Password protected sessions
- [ ] Dark/Light theme toggle
- [ ] Character limit indicator

---

## ⭐ Give it a Star!

If you find SyncPad useful, please give it a ⭐ — it helps the project grow! 🚀

[![Star on GitHub](https://img.shields.io/github/stars/Tushar-1001/syncpad?style=social)](https://github.com/Tushar-1001/syncpad)

---

## 📄 License

MIT License — free to use, modify and share!

---

<div align="center">

Made with ❤️ by [Tushar](https://github.com/Tushar-1001)

**[🌐 Live App](https://Tushar-1001.github.io/syncpad) · [🐛 Report Bug](https://github.com/Tushar-1001/syncpad/issues) · [💡 Request Feature](https://github.com/Tushar-1001/syncpad/issues)**

</div>
