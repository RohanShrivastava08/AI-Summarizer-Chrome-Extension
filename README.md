# 🧠 AI-Summarizer Chrome Extension

<img width="229" height="37" alt="Image" src="https://github.com/user-attachments/assets/f53dd693-d55b-4709-9eee-c6f85e1a78d5" />

<img width="1470" height="956" alt="Image" src="https://github.com/user-attachments/assets/14dcb7da-39f5-4f1b-b77d-c0b7211db7ce" />

<img width="1470" height="956" alt="Image" src="https://github.com/user-attachments/assets/00a38393-338c-468e-a139-f53d27796019" />

<img width="1470" height="956" alt="Image" src="https://github.com/user-attachments/assets/94a9f659-2636-460d-8fe2-d09854e19690" />


- A simple and efficient Chrome Extension that summarizes webpages or selected text on the go.
- Built with JavaScript and Chrome’s Manifest V3 APIs.


## 📋 Table of Contents
- Introduction
- Features
- Project Implementation Process
- File Structure
- Technology Stack
- Installation
- Usage
- Screenshots
- Contributing
- License
- Contact

## 📘 Introduction

This project demonstrates how to build a Chrome Extension with:

- ⚡ Manifest V3 – Modern Chrome Extension architecture

- 🧩 Background & Content Scripts – Handle logic and text extraction

- 🎨 Popup & Options Pages – Simple UI to interact with the summarizer

- 🛠 Customizable Backend – Plug in any summarization API (OpenAI, Hugging Face, etc.)

### Flow:

- User installs the extension in Chrome.
- Select text or open the popup.
- Background + content scripts extract content.
- API call generates the summary.
- Popup displays the result instantly.

## ✨ Features

📝 Summarize Content → Selected text or entire webpage

⚡ Lightweight & Fast → Runs smoothly inside Chrome

🎨 Popup UI → Simple, minimal interface

🛠 Options Page → Save API keys & preferences

🔒 Local Storage → Stores data securely with Chrome storage

## 🛠 Project Implementation Process

#### 1. Manifest Setup
- Defined permissions, background service worker, popup, and options page.

#### 2. Background & Content Scripts
- background.js handles summarization requests.
- content.js extracts selected text or page content.

#### 3. Popup & Options Page
- popup.html + popup.js → Display summary results.
- options.html + options.js → Manage API key and user settings.

#### 4. Messaging Flow
- Popup → Background → Content → Summarizer API → Back to Popup.

## 📁 File Structure

```bash
AI-Summarizer-Chrome-Extension/
├── background.js        # Background service worker  
├── content.js           # Content script for text extraction  
├── icon.png             # Extension icon  
├── manifest.json        # Chrome extension manifest v3  
├── options.html         # Options page  
├── options.js           # Options page logic  
├── popup.html           # Popup UI  
├── popup.js             # Popup functionality  
└── README.md            # Project documentation  
```

## 💻 Technology Stack

Category Tech Used

⚡ Extension Base   Chrome Manifest V3

🧩 Scripting   JavaScript (Background, Content, Popup)

🎨 UI   HTML + CSS (Popup & Options)

🛠 Storage   Chrome Storage API


## 🛠 Installation

Follow these steps to set up and run the Techny project locally:

#### 1. Clone the repository

```bash
git clone https://github.com/YourUsername/AI-Summarizer-Chrome-Extension.git
cd AI-Summarizer-Chrome-Extension
```

#### 2. Load the extension in Chrome

- Open chrome://extensions/
- Enable Developer Mode (toggle on top right)
- Click Load unpacked and select this project folder

### 3. Verify
- The extension icon will appear in Chrome’s toolbar

## 🚀 Usage
- Click the extension icon in your toolbar
- Enter or configure your API key in the Options page
- Select text → Right-click → “Summarize” OR use the popup
- Get instant summaries right inside Chrome


## 📸 Screenshots



## 🤝 Contributing
We welcome community contributions! Follow the steps below to contribute:

#### Fork the repository
- Create a new branch:
```bash
git checkout -b feature/YourFeature
```

- Commit your changes:
```bash
git commit -m 'Add your feature'
```

- Push to the branch:
```bash
git push origin feature/YourFeature
```

- Open a pull request with detailed explanations of your changes.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Contact
For any questions or suggestions, feel free to reach out:

- Email: rohansh0808@gmail.com
- GitHub: Rohansh0808
