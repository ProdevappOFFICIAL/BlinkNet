# <p align="center">
  <img src="https://raw.githubusercontent.com/ProdevappOFFICIAL/BlinkNet/refs/heads/main/BlinkNetLogo.png" alt="BlinkNet Logo" width="200"/>
</p>

 BlinkNet - The Fastest Offline and Online File Sharing App

BlinkNet is a high-performance, cross-platform file sharing application built with *Electron, **Vite, and **React. Designed to outperform traditional solutions like **AirDrop, **Xender, and **Senda*, BlinkNet combines blazing-fast transfer speeds with a beautiful desktop-native UI.

> *Mission:* To make file sharing lightning fast, secure, and seamless for everyone—no cables, no limits.

---

## 🚀 Features

- *Cross-Platform* (Windows, macOS, Linux)
- *Peer-to-Peer File Transfer* (using WiFi Direct, WebRTC, TCP/UDP sockets)
- *Offline Mode* – Share without internet
- *Device Discovery* with Local Network Scanning
- *Secure Transfers* with optional end-to-end encryption
- *Drag & Drop File Sharing*
- *Transfer History* & Logs
- *Smart Suggestions* based on frequent connections
- *Built-in File Preview* and progress tracking
- *Dark Mode UI*
- *Customizable Settings* for paths, themes, and performance

---

## 🖥 Technologies Used

| Frontend          | Backend / Core Logic         | Others                          |
|------------------|------------------------------|----------------------------------|
| ElectronJS        | Node.js (Native Modules)     | WebRTC / TCP Sockets             |
| React + Vite      | Rust (planned for speed)     | Tailwind CSS                     |
| IPC Channels      | File System APIs             | Bonjour / Zeroconf (for discovery) |

---

## 🧑‍💻 Developer Workflow

- Electron hosts the app shell and communicates with system-level APIs.
- React + Vite powers the fast, reactive UI.
- IPC (ipcMain and ipcRenderer) bridges the frontend and backend.
- Transfer engines use Node.js sockets and optionally Rust modules via neon-bindings or napi-rs.
- Peer discovery via Bonjour or UDP broadcast.
- Real-time progress tracking through event channels.

---

## 📸 UI Pages (Overview)

- *Dashboard* – Discover devices, quick actions
- *Send File* – Select file, choose peer, track upload
- *Receive File* – Accept/Reject incoming files
- *Transfer History* – Logs with filters and sorting
- *Settings* – Choose paths, encryption, themes, etc.

---

## 📁 Folder Structure
