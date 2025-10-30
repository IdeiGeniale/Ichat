# 💬 IChat

**IChat** is a peer-to-peer chat app built entirely with **HTML, CSS, and JavaScript**, allowing users to connect and chat directly using **unique 6-digit IDs** — no servers, accounts, or installations required.

---

## 🚀 Features

- 🔗 **Peer-to-Peer Messaging** powered by [PeerJS](https://peerjs.com/)
- 🆔 **6-Digit Unique IDs** (auto-generated or saved via cookies)
- 💾 **Local Chat History** with save and load support
- 📒 **ID Book** to store known peers, nicknames, and last contact time
- 🔕 **Mute Peer** option to silence incoming messages
- 💬 **Incoming Connection Alerts** (accept or reject)
- 🍪 **Cookie Consent System** to control ID persistence
- 📋 **Copy & Regenerate ID** buttons
- 🌐 **Fully Client-Side** — no backend required
- 📱 **Mobile-Friendly Responsive UI**

---

## 🧠 How It Works

IChat uses **PeerJS** and **WebRTC** to establish direct browser-to-browser connections.  
Each user gets a **6-digit random ID**, which can be shared to start chatting.

When a connection is made:
1. Both peers establish a **WebRTC data channel** using PeerJS.
2. Messages are sent **directly** between browsers (no central server).
3. Chat history and IDs are stored **locally** in the browser’s `localStorage` and cookies.

---

## 🧩 File Overview

| File | Description |
|------|--------------|
| `IChat.html` | The complete single-file app containing HTML, CSS, and JavaScript. |

---

## 🖥️ Usage

1. Open `IChat.html` in your web browser.  
2. Accept cookies (optional, for persistent ID).  
3. Share your **6-digit ID** with another user.  
4. Enter their ID in the “Enter peer’s 6-digit ID” field.  
5. Click **Connect** to start chatting instantly.

---

## 📜 Local Storage & Cookies

| Key | Purpose |
|-----|----------|
| `peerjs_chat_id` | Saves your generated ID for reuse |
| `peerjs-chat-history` | Stores all saved chat sessions |
| `peerjs-current-chat` | Keeps your ongoing chat in progress |
| `peerjs_id_book` | Stores known peers and nicknames |

---

## 🛡️ Privacy

- 100% **peer-to-peer** — data is **never uploaded** to a server.  
- Cookies are used **only** for ID persistence and preferences.  
- You can **decline cookies** to use a temporary session-only ID.  
- All data (messages, peers, history) remains on your local device.

---

## 🧰 Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **PeerJS (CDN)**
- **WebRTC (built-in browser technology)**

---

## 💡 Future Improvements

- 🎙️ Add **voice and video chat** via PeerJS media streams  
- 📁 Implement **file transfer** between peers  
- 🔐 Add **end-to-end message encryption**  
- 💬 Support **multiple simultaneous chats**  
- ☁️ Optional **cloud sync** for chat logs

---

## 🏷️ Project Info

- **Project Name:** IChat  
- **Author:** IdeiGeniale  
- **Version:** 1.0  
- **License:** MIT  
- **Type:** Vanilla Web App  

---

## 🖋️ Credits

- Built with ❤️ using **PeerJS** and **pure web technologies**  
- Created by **IdeiGeniale**  
