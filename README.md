# DevCode Saver & Editor 🚀

A lightweight, privacy-focused, browser-based code editor and snapshot manager with Progressive Web App (PWA) support. Write, edit, test, and manage your code snippets locally without any server-side dependencies.

## ✨ Key Features

- ➕ **Smart Workspace Setup:** Easily clear the canvas to start a new file with built-in data loss protection safeguards (`confirm` check).
- 📂 **File Operations:** Open existing local files to view/edit or download your current canvas instantly with the correct file extension.
- 📸 **Local History & Snapshots:** Save instantaneous snapshots of your code to the browser's local storage (`localStorage`). Never lose your working state.
- 📤 **Data Portability:** Export your entire operation history as a portable `.json` backup file and import it back seamlessly whenever needed.
- 📲 **PWA Ready:** Install the application directly onto your desktop or mobile device for a native-app-like experience and quick offline access.
- 🎨 **Modern Dark UI:** Responsive grid layouts crafted using custom CSS variables optimized for deep focus and scanning efficiency across desktop and mobile screens.

## 🛠️ Tech Stack

- **Frontend:** Semantic HTML5, CSS3 Grid & Flexbox (with Modern Custom Properties)
- **Logic:** Vanilla JavaScript (ES6+)
- **Portability & Lifecycle:** Web Storage API (`localStorage`), FileReader API
- **Offline / PWA:** Service Worker API, Web App Manifest

## 🚀 Getting Started

Since this is a client-side web app, setting it up locally takes less than a minute.

### Prerequisites
You only need a modern web browser (Chrome, Edge, Safari, or Firefox).

### Setup Instructions
1. Clone the repository to your local system:
   ```bash
   git clone [https://github.com/mugic1/devcode-saver.git](https://github.com/mugic1/devcode-saver.git)