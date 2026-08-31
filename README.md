# BharatOS Web Desktop

A lightweight browser-based desktop environment built with React, TypeScript, Vite, and Tailwind CSS. BharatOS provides a window management system, an IndexedDB-backed virtual filesystem, procedural sound synthesis via Web Audio API, and native productivity apps.

## Features

- **Window Compositor**: Moveable, resizable, minimizable, and maximizable windows with z-index stacking.
- **Virtual Filesystem (VFS)**: Persistent local file storage in IndexedDB with folder hierarchy, file inspector, and quick access directories.
- **Floating Island Dock**: Application dock, system launcher, and status flyouts (Wi-Fi diagnostics, audio master gain, screen brightness dimming overlay, user profile power menu).
- **Procedural Sound Synthesizer**: Native sound effects and ambient focus soundscapes generated in real time using the Web Audio API (no external MP3/WAV assets).
- **Built-in Applications**:
  - **Files**: Explorer with grid/list views, search, category filters, and file metadata preview.
  - **Terminal**: Unix-style shell supporting standard directory operations and command chaining.
  - **FocusDefend**: Deep-work timer with distraction firewall blocklist and focus telemetry.
  - **Notes**: Markdown-enabled text editor with auto-save to virtual storage.
  - **Calculator**: Recursive-descent arithmetic calculator with calculation history.
  - **Settings**: Theme customizer, user profile management (PIN security), wallpaper gallery, and audio controls.
  - **System Monitor**: Session uptime, memory estimation, and window process overview.
  - **Music & Audio**: Interactive procedural tone synthesizer.
  - **Browser & Gallery**: Sandbox web frame and scenic wallpaper viewer.

## Tech Stack

- **Framework**: React 18 + TypeScript
- **Styling**: Tailwind CSS + Lucide Icons
- **State Management**: Zustand
- **Storage**: IndexedDB (`idb`)
- **Audio**: Web Audio API
- **Build Tool**: Vite

## Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

## License

MIT License. Developed by **Aviral Dewangan** (<aviral.dewangan14@gmail.com>).
