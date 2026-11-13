# 👛 tgWallet

A lightweight Web3 cryptocurrency wallet built as a Google Chrome browser extension for managing Ethereum accounts, viewing balances, and sending transactions.

---

## 📖 Overview

**tgWallet** brings decentralized wallet functionality directly into your browser toolbar. Powered by **Ethers.js** and Chrome Extension APIs, it allows users to create or import Ethereum wallets, inspect account balances, and interact with Ethereum networks without leaving their browser.

---

## ✨ Features

- **Browser Extension Integration:** Accessible anytime from the Chrome toolbar via a clean popup interface (`popup.html`).
- **Ethereum & Web3 Support:** Built with `ethers.js` for secure wallet creation, key management, and blockchain interactions.
- **Chrome Storage & APIs:** Uses `chromeapi` to manage extension state and local wallet data smoothly.
- **Custom UI:** Styled popup interface (`style.css`) with custom branding assets.

---

## 🗂️ Project Structure

```text
tgWallet/
├── assets/          # Icons, images, and static visual resources
├── chromeapi/       # Chrome extension background/storage API handlers
├── ethers.js        # Ethers.js library for Ethereum blockchain interaction
├── manifest.json    # Chrome Extension configuration and permissions
├── popup.html       # Main wallet extension popup UI
├── popup.js         # Wallet logic, event handlers, and Web3 calls
├── style.css        # Popup styling and layout
└── README.md
```

---

## 🛠️ Tech Stack

- **Platform:** Google Chrome Extension (Manifest)
- **Blockchain Library:** Ethers.js
- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Browser APIs:** Chrome Extension APIs (`chromeapi`)

---

## 🚀 Getting Started (Load in Chrome)

Because this is a Chrome extension, you can load it directly into your browser without a build step:

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   ```
2. Open Google Chrome and navigate to:
   ```text
   chrome://extensions/
   ```
3. Toggle **Developer mode** **ON** (top-right corner).
4. Click **Load unpacked** (top-left corner).
5. Select the cloned **`tgWallet`** folder on your computer.
6. Click the **Extensions puzzle icon** in your Chrome toolbar and pin **tgWallet** to start using it!

---

## ⚠️ Security Disclaimer

This project is intended for educational and testnet development purposes. Always verify network settings before importing private keys or seed phrases holding real funds.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
