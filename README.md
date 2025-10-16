
# 🚀 MacBook GSAP Landing Page

An interactive, animated landing page for MacBook, built with React, Vite, GSAP, Three.js, and TailwindCSS. Features stunning 3D models, smooth animations, and a modern UI. Perfect for showcasing product highlights and performance! 💻✨

---

## 📦 Features

- ⚡ GSAP-powered animations for smooth transitions
- 🖥️ 3D MacBook models with react-three-fiber
- 🎨 Responsive design with TailwindCSS
- 🌙 Dark/light mode support
- 🏆 Product highlights and performance sections
- 🎥 Video backgrounds and interactive features
- 🛒 Modern UI components (Navbar, Footer, Showcase, etc.)

## 🗂️ Folder Structure

```
├── public/
│   ├── fonts/         # Custom font files
│   ├── models/        # 3D model files (.glb)
│   ├── videos/        # Feature and hero videos
│   └── ...            # Images, icons, assets
├── src/
│   ├── components/    # React components (Hero, Features, ProductViewer, etc.)
│   │   ├── models/    # MacBook 3D model components
│   │   ├── three/     # Three.js helpers (lights, switcher)
│   ├── constants/     # App constants
│   ├── store/         # Zustand store
│   ├── App.jsx        # Main app component
│   ├── main.jsx       # Entry point
│   └── index.css      # Global styles
├── index.html         # App HTML template
├── package.json       # Project metadata & scripts
├── vite.config.js     # Vite configuration
└── README.md          # Project info
```

## 🛠️ Tech Stack

- React 19
- Vite
- GSAP
- Three.js & react-three-fiber
- TailwindCSS
- Zustand (state management)

## 🚀 Getting Started

Clone the repo and install dependencies:

```powershell
git clone https://github.com/TestGithubByHusnain/gsap-macbook-app.git
cd gsap-macbook-app
npm ci
```

Run locally:

```powershell
npm run dev
```

Build for production:

```powershell
npm run build
```

Preview production build:

```powershell
npm run preview
```

## 🌐 Deploying to Vercel

1. Push your latest code to the `main` branch on GitHub.
2. Go to [Vercel](https://vercel.com/) and import your repo.
3. Set build command to `npm run build` and output directory to `dist`.
4. Click Deploy! Your site will be live at `https://your-app.vercel.app`.

_Optional_: Add a `vercel.json` for SPA routing:
```json
{
	"rewrites": [ { "source": "/(.*)", "destination": "/index.html" } ]
}
```

## 🙌 Credits

- Inspired by Apple MacBook product pages
- Built with [React](https://react.dev/), [Vite](https://vitejs.dev/), [GSAP](https://gsap.com/), [Three.js](https://threejs.org/), [TailwindCSS](https://tailwindcss.com/)

## 📄 License

MIT
