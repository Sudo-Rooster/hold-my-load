# Hold-My-Load

> **Webhook Alert Dashboard — Built different.**

A dark, fast, no-bullshit webhook alert tool for sending custom Discord alerts, editing Ducky scripts, managing images, and firing payloads — all from a single HTML file. No installs. No backend. No cap.

---

## Quick Start

1. Download the ZIP from the green **`<> Code`** button
2. Extract it
3. Double-click **`index.html`**
4. Enter your Discord Webhook URL in the **Config** tab
5. Hit **Save** — you're live 

> Your settings are saved automatically. You only enter your webhook once.

---

##  Features

### Config
- Set your Discord Webhook URL
- Toggle on a private cloud endpoint
- Customize your bot name & avatar URL
- Test both connections with one click

### Message Builder
- Write alerts with a **live Discord embed preview**
- Pick severity — Info, Warning, or Critical
- Color-coded embeds sent straight to your server
- Send to Discord, Cloud, or both at once

### Payload Generator
- 6 quick-load templates — Server Down, High CPU, Memory Alert, Deployment, Auth Breach, Custom
- Raw JSON editor — write or paste any payload
- Format, copy, and fire with one click

### Ducky Script Editor
- Full Rubber Ducky script editor in the browser
- Quick-insert buttons for common commands
- Load a starter template
- Download your script as a `.txt` file instantly

### Image Utility
- Drag & drop or upload images
- Preview your uploads in a grid
- Send images directly to Discord as embed attachments
- Paste any public image URL

---

##  How to Use as a Web App

Just visit your GitHub Pages link:

```
https://yourusername.github.io/hold-my-load
```

No download needed. Works in any browser.

---

##  Persistence

Hold-My-Load saves your config to `localStorage` — meaning every user's settings are stored on their own machine. Enter your webhook once, it's remembered forever. No accounts. No servers. No tracking.

---

## Tech Stack

| Layer | Tech |
|---|---|
| Frontend | Vanilla HTML / CSS / JS |
| Alerts | Discord Webhook API |
| Storage | localStorage |
| Hosting | GitHub Pages / Any static host |
| Desktop | Double-click `index.html` |

---

##  Requirements

- A Discord server with a webhook URL
- A browser (Chrome, Firefox, Edge — anything works)
- That's it.

---

## Contributing

Pull requests are welcome. Fork it, break it, make it better.

```bash
git clone https://github.com/yourusername/hold-my-load
cd hold-my-load
# make your changes to index.html
git add .
git commit -m "made it harder better faster stronger"
git push origin main
```

---

##  Disclaimer

This tool is for **legitimate alerting and automation purposes only**. The Ducky Script editor is provided for educational and authorized use. Use responsibly.

---

##  License

MIT — do whatever you want with it. Just don't be weird.

---

<div align="center">

Built with by someone who was tired of overengineered alert tools.

**Hold-My-Load** — *because someone's gotta.*

</div>
