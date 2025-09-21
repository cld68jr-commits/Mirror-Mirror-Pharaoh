# Mirror Mirror / Pharaoh

A desktop app built with **Electron + HTML/CSS/JavaScript**. It uses your webcam as a mirror, overlays an Egyptian frame (with optional crown overlay), shows prompt text, lets you snap a photo, and saves it. The project is open source and meant for learning, polish, and collaboration.

---

## 🚀 Features

- Live webcam mirror view  
- Ornate Egyptian frame overlay  
- Toggle crown overlay  
- Prompt text on screen: *“Mirror Mirror on the Wall — Who is the Pharaoh of Them All?”*  
- Snap photo / Save as PNG  
- Flip/mirror toggle for webcam  
- Roadmap ideas: face detection to auto-position crown, packaging for Windows/Mac/Linux, UI polish  

---

## 🛠 Tech Stack

| Component | Technology |
|-----------|------------|
| Framework / Runtime | Electron |
| Languages | HTML, CSS, JavaScript |
| Assets | PNG overlays (`egyptian_frame.png`, `pharaoh_crown.png`) |
| Saving snapshots | Canvas API + Electron’s file dialog / file system |
| Optional future tools | MediaPipe (or similar face tracking), electron-builder or similar for packaging |

---

## 🔧 Getting Started

### Prerequisites

- Node.js (version 16+ recommended)  
- npm or yarn  
- (Optional) electron-builder or similar tools if you want to build installers  

### Installation & Running Locally

```bash
git clone https://github.com/YOUR_USERNAME/Mirror-Mirror-Pharaoh.git
cd Mirror-Mirror-Pharaoh
npm install
npm start

/*.app
/*.dmg

# OS files
.DS_Store
Thumbs.db

# logs
npm-debug.log*
yarn-debug.log*
yarn-error.log*

# IDE settings
.vscode/
.idea/
