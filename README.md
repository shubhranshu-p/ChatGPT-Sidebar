# ChatGPT Sidebar – Chrome Extension

A super-lightweight Chrome extension that opens **ChatGPT in the browser sidebar** with one click.

- ✅ Opens the official ChatGPT website in Chrome’s side panel  
- ✅ If you’re already logged in, it goes straight to ChatGPT  
- ✅ If not logged in, you sign in as usual (inside the sidebar)  
- ✅ **No data collection**, no tracking, no ads  
- ✅ Simple “load unpacked” installation from source

> ⚠️ This project is **unofficial** and **not affiliated with OpenAI** or ChatGPT in any way.

## ✨ Features

- **One-click access**  
  Click the extension icon and ChatGPT opens instantly in Chrome’s sidebar.

- **Uses official ChatGPT**  
  Nothing is proxied or modified. It just loads `https://chatgpt.com` (or the ChatGPT page you configured) in a side panel.

- **Respects your existing login**  
  - Already logged in → ChatGPT loads directly in the sidebar  
  - Not logged in → You’ll see the normal OpenAI login flow inside the sidebar

- **Zero data collection**  
  - Extension does **not** read, store, or send any of your data  
  - No analytics, no external servers, no third-party APIs

---

## 🧩 Installation (Developer Mode)

Since this is a developer-mode extension, you install it manually:

1. **Download the code**
   - Click the green **Code** button on this repo  
   - Choose **Download ZIP**  
   - Extract the ZIP to a folder on your system

2. **Open Chrome Extensions page**
   - Go to `chrome://extensions/` in your address bar

3. **Enable Developer mode**
   - Toggle **Developer mode** on (usually in the top-right corner)

4. **Load the extension**
   - Click **Load unpacked**
   - Select the folder you extracted from the ZIP

5. **Pin the extension (optional)**
   - Click the puzzle-piece icon (Extensions) in Chrome’s toolbar  
   - Pin **ChatGPT Sidebar** so it’s always visible

You’re done! 🎉

---

## 🚀 Usage

1. Click the **ChatGPT Sidebar** extension icon in the Chrome toolbar.
2. A side panel/sidebar will open with the ChatGPT page.
3. If you’re:
   - **Logged in** → You can start chatting immediately.
   - **Not logged in** → Sign in with your OpenAI account inside the sidebar, then use ChatGPT as normal.

All your conversations, history, settings, etc. are handled by the official ChatGPT website itself.

---

## 🔒 Privacy & Permissions

- **Data collection**:  
  - The extension **does not collect, store, or transmit** any user data.
  - No databases, no cookies handled manually, no third-party APIs.

- **Permissions** (depending on your manifest):  
  - Minimal permissions required to open the side panel and display ChatGPT.
  - No access to your browsing history or page contents unless explicitly required by your implementation.

You can always inspect the source code in this repo to verify what it does.

---

## 🛠️ Development (optional)

If you want to modify the extension:

1. Clone the repository:
   ```bash
   git clone https://github.com/shubhranshu-p/ChatGPT-Sidebar.git
   cd ChatGPT-Sidebar
