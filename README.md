# 💻 3D MacBook Pro — Interactive Product Showcase

A stunning **3D interactive MacBook Pro product showcase** built with React.js, Three.js, and React Three Fiber — featuring a realistic 3D model, smooth scroll-based animations, and an immersive user experience.

🔗 **Live Demo:** [https://mac-book-roan.vercel.app](https://mac-book-roan.vercel.app)

---

## 📸 Preview

> *(Add a screenshot or screen recording GIF here)*

---

## 📌 About the Project

This project is an interactive, Apple-inspired MacBook Pro landing page that showcases 3D rendering in the browser. As you scroll through the page, the MacBook model animates with dynamic camera movements, smooth transitions, and section-by-section product storytelling — just like a real product launch page.

---

## ✨ Features

- 🖥️ **Realistic 3D MacBook model** rendered in the browser using Three.js
- 🎬 **Scroll-based animations** powered by GSAP + ScrollTrigger
- 📷 **Dynamic camera movements** that follow user scroll position
- 🧩 **Modular component structure** — NavBar, Hero, ProductViewer, Showcase, Performance, Features, Highlights, Footer
- 📱 **Responsive design** across desktop, tablet, and mobile
- ⚡ **Smooth performance** with optimized 3D rendering via React Three Fiber

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **React.js** | UI framework and component architecture |
| **Three.js** | 3D rendering engine |
| **React Three Fiber** | React renderer for Three.js |
| **GSAP** | Animations and scroll-triggered effects |
| **ScrollTrigger** | GSAP plugin for scroll-based animation control |
| **Vite** | Build tool and development server |
| **Vercel** | Hosting and deployment |

---

## 📁 Project Structure

```
Mac-Book/
├── public/               # Static assets (3D models, images)
├── src/
│   ├── components/
│   │   ├── NavBar.jsx        # Navigation bar
│   │   ├── Hero.jsx          # Hero / landing section
│   │   ├── ProductViewer.jsx # 3D MacBook model viewer
│   │   ├── Showcase.jsx      # Product showcase section
│   │   ├── Performance.jsx   # Performance specs section
│   │   ├── Features.jsx      # Features highlight section
│   │   ├── Highlights.jsx    # Key highlights section
│   │   └── Footer.jsx        # Footer
│   ├── App.jsx           # Root component — assembles all sections
│   └── main.jsx          # React entry point
├── package.json
├── vite.config.js
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- npm or yarn

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/parthbarabde2704/Mac-Book.git
   cd Mac-Book
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm run dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build for Production

```bash
npm run build
```

---

## 🌐 Deployment

This project is deployed on **Vercel** with automatic deployments on every push to `main`.

To deploy your own copy:

1. Push the repo to GitHub.
2. Go to [vercel.com](https://vercel.com) → **Add New Project** → import the repo.
3. Vercel auto-detects Vite — just click **Deploy**.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 👤 Author

**Parth Barabde**
- GitHub: [@parthbarabde2704](https://github.com/parthbarabde2704)
- Live Project: [mac-book-roan.vercel.app](https://mac-book-roan.vercel.app)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> ⭐ If you liked this project, please give it a star on GitHub!

