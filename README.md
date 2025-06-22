# 🎵 Spotify‑Style Music Player

A sleek React + Vite web app that re‑imagines Spotify’s home screen and bottom player bar.
**Live Demo:** [View Here](https://spotify-frontend-kartikey.vercel.app/) 👈

---

## ✨ Features

|                            |                                                                         |
| -------------------------- | ----------------------------------------------------------------------- |
| 🔍 **Search & Navigation** | Home & Search routes, library sidebar, filter tabs (All/Music/Podcasts) |
| 📊 **Featured Charts**     | Top 50 Global/India, Trending playlists, Mega Hits, Happy Favorites     |
| 🎧 **Now Playing Bar**     | Shuffle, Previous, Play/Pause, Next, Repeat, progress slider, timestamp |
| 🎶 **Playlist & Podcasts** | Create your first playlist, follow podcasts, auto‑update UI             |
| 🖼 **Responsive Grid**     | Card‑based album covers with hover effects                              |
| ⚡ **Fast SPA**             | Vite dev server + code‑splitting gives instant reloads                  |

## 🗂️ Project Structure

```text
src/
├── assets/               # Static images & icons
├── components/
│   ├── AlbumItem/        # Album card component
│   │   └── AlbumItem.jsx
│   ├── Display/          # Generic album grid
│   │   └── Display.jsx
│   ├── DisplayAlbum/     # Album details view
│   │   └── DisplayAlbum.jsx
│   ├── DisplayHome/      # Home page (featured charts, hits)
│   │   └── DisplayHome.jsx
│   ├── DisplayNav/       # Tabs: All | Music | Podcasts
│   │   └── DisplayNav.jsx
│   ├── Player/           # Bottom music player bar
│   │   └── Player.jsx
│   ├── Sidebar/          # Left navigation & library
│   │   └── Sidebar.jsx
│   └── SongItem/         # Individual song row
│       └── SongItem.jsx
├── context/
│   └── PlayerContext.jsx # React context for global playback state
├── App.jsx               # Root component / routes
├── main.jsx              # Vite entry point
└── index.css             # Tailwind design system
```

## 🚀 Quick Start

> **Prerequisite:** Node.js ≥ 18

1. Open the project in **VS Code** and launch an integrated terminal (`Right‑click sidebar → “Open in Integrated Terminal”`).
2. Install dependencies:

   ```bash
   npm install
   ```
3. Start the dev server:

   ```bash
   npm run dev
   ```
4. Visit the local URL shown in the terminal — your app is live!

ℹ️   The instructions above are adapted from the *How to Run this Project*


### ⚠️ Troubleshooting

* Ensure `node_modules` appears after `npm install` — re‑run the command if it doesn’t.
* On Windows, run the terminal **as Administrator** if you hit permission errors.
* Still stuck? Check the PDF guide or watch the YouTube playlist linked therein.fileciteturn1file0L17-L17

## 🛠️ Built With

* **React 18** & **Vite** 🏎️
* **Tailwind CSS** 💅
* **Context API** for global player state ☑️
* **ESLint + Prettier** for code quality 🧹

---

Made with ❤️ by Kartikey!
