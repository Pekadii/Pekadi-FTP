![License](https://img.shields.io/badge/License-MIT-blue) ![Release](https://img.shields.io/badge/Release-1.0-blue) ![Development](https://img.shields.io/badge/Development-1.0-blue.svg)
# Pekadi PS4 FTP 

A lightweight, client-accessible FTP-based PKG uploader for PS4 consoles via Remote Package Installer.

## 💡 Features
- Connect to PS4 FTP using IP and port.
- Navigate the PS4 directory tree.
- Upload `.pkg` files directly to `/data/pkg`.
- Optimized for both desktop and mobile browsers.


## 🚀 Requirements
- Node.js installed
- PS4 Jailbreak on the same LAN or Wifi ( Debug + Server ) Settings enable.
- A `.pkg` game or application file to upload
- If there is no `pkg` folder in /data create one use FileZilla.
- You still need a Desktop - Laptop to run the `server.js`

## 📦 How to Use

1. Extract the `Pekadi-FTP.rar` anywhere on your PC.
2. Open `run.bat` and **edit the path** to match where you extracted the files.
3. Double-click `run.bat` to start the local server.
4. Open your browser and go to `http:// ENTER YOUR IP:3000/Pekadi-FTP.html`
5. Enter your PS4's IP address and FTP port (default: 2121)
6. Navigate to `/data/pkg` and upload your `.pkg` file.

Can't find your `local IP`, On your Desktop open `CMD = Command Prompt or Terminal`, type `ipconfig` If on LAN should be: `Ethernet adapter Ethernet:`
Looking for `IPv4 Address. . . . . . . . :192.168.*.* or 10.0.*.*` then go back to step #4. `http:// ENTER YOUR IP:3000/Pekadi-FTP.html`

> ⚠️ Uploads are only allowed to `/data/pkg/`.

## 🔐 Notes
- This app runs locally and does not store or transmit data externally.

---

© 2025 Pekadi.com
