# Mirror-Mirror-Pharaoh
I’m building a desktop app using Electron + HTML/CSS/JS. It uses your webcam as a mirror, overlays an Egyptian frame, has optional crown overlay, prompt text, and lets you snap &amp; save a photo. I want to polish it, add face tracking (optional), package it, etc.
🔍 Recommended .gitignore contents

Here’s what you should ignore for an Electron + Node project. If GitHub gives you a “Node” template, that covers most. Here are example entries:

# dependencies
/node_modules

# build output
/dist
/build

# Electron packaging output
/out-*-electron
/*.exe
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
