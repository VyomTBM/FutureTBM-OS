# 🌐 FutureTBM OS — A Futuristic Web Operating System

**Title:** *FutureTBM OS — A Futuristic Web Operating System*  

**Concept:**  
Design a lightweight, futuristic web OS named **FutureTBM OS**. It should run entirely in the browser using **HTML, CSS, and JavaScript** (with optional utility libraries like TailwindCSS, but avoiding heavy frameworks such as React, NextJS, or Vite). The OS should simulate a desktop environment with a sleek, futuristic style, offering basic apps, temporary sessions, and a DOS emulator.  

---

## 🖥️ Core Features & Apps

- **Desktop Environment**  
  - Futuristic UI with neon accents, glassmorphism, and smooth animations.  
  - Built using **HTML structure**, **TailwindCSS for styling**, and **vanilla JS for window management**.  

- **File Manager**  
  - Allows temporary session storage (data cleared on refresh).  
  - Uses **IndexedDB or LocalStorage** for session persistence.  
  - Drag-and-drop file simulation with **JS event listeners**.  

- **Markdown Text Processor**  
  - A basic editor that converts Markdown to styled HTML.  
  - Built with **textarea + JS parser (like Marked.js)**.  
  - Styled with **TailwindCSS typography utilities**.  

- **DOS Emulator**  
  - A terminal-style app that mimics DOS commands (`dir`, `echo`, `cls`).  
  - Implemented with **JS command parser** or **js-dos WebAssembly** for real DOS execution.  
  - Styled with **monospace fonts + CSS grid**.  

- **Notes App**  
  - Simple sticky notes with draggable windows.  
  - Uses **LocalStorage** for temporary saving.  
  - Styled with **CSS shadows and gradients** for futuristic look.  

- **Clock & System Info**  
  - Displays real-time clock and basic system stats (browser info, memory usage).  
  - Built with **JS Date API** and **navigator object**.  

---

## ⚙️ Technologies Breakdown

| **App** | **Tech Stack** | **Notes** |
|---------|----------------|-----------|
| **Desktop Environment** | HTML, TailwindCSS, Vanilla JS | Window manager, taskbar, icons |
| **File Manager** | HTML, CSS, JS (IndexedDB/LocalStorage) | Temporary session storage |
| **Markdown Processor** | HTML, TailwindCSS, JS (Marked.js optional) | Converts Markdown → HTML |
| **DOS Emulator** | HTML, CSS, Vanilla JS or js-dos (WebAssembly) | Command parser or real DOS execution |
| **Notes App** | HTML, CSS, JS (LocalStorage) | Draggable sticky notes |
| **Clock/System Info** | HTML, CSS, JS (Date API, Navigator API) | Futuristic widget |

---

## 🎨 Style Guidelines

- **Glassmorphism**: Transparent panels with blur effects.  
- **Neon Glow**: Accent colors (cyan, magenta, purple).  
- **Minimal Animations**: Smooth transitions using **CSS keyframes**.  
- **Dark Theme**: Default futuristic look with high contrast.  
