# 🌐 Personal 3D Portfolio – Hasee10

> A modern, interactive developer portfolio built with **React**, **Three.js**, and **TailwindCSS**. Features include animated 3D models, smooth page transitions, and responsive design — all bundled with blazing-fast performance via **Vite** and deployed on **GitHub Pages**.

---

## 📸 Live Demo

🎯 [Visit the Portfolio](https://hasee10.github.io/Personal_Portfolio/)

![Preview](./src/assets/portfolio_preview.png)

---

## 🚀 Features

- ⚡ **Vite** – Ultra-fast build tool
- 🎨 **TailwindCSS** – Utility-first responsive styling
- 🧠 **React** – Component-based architecture
- 🌌 **Three.js / @react-three/fiber** – Fully interactive 3D elements
- 🎥 **Framer Motion** – Smooth animations and transitions
- 💬 **Contact Form** – Send emails with EmailJS
- 📱 **Mobile-Ready** – Responsive layout across all devices
- 🌍 **Deployed via GitHub Pages**

---

## 📁 Folder Structure

```

Personal\_Portfolio/
├── public/
│   ├── desktop\_pc/             # GLTF model for 3D scene
│   ├── planet/                 # Planet model assets
│   └── ...
├── src/
│   ├── assets/                 # Images & icons
│   ├── components/             # UI components
│   ├── constants/              # Data-driven content
│   ├── hoc/                    # Higher-order components
│   ├── utils/                  # Helper functions
│   ├── App.jsx                 # Main app component
│   ├── main.jsx                # Entry point
│   └── styles.js               # Inline styling
├── tailwind.config.cjs
├── vite.config.js             # Vite + deployment base config
├── package.json
└── README.md

````

---

## 🧪 Local Development

```bash
# 1. Clone the repo
git clone https://github.com/Hasee10/Personal_Portfolio.git
cd Personal_Portfolio

# 2. Install dependencies
npm install

# 3. Start the dev server
npm run dev

# App runs at http://localhost:5173/
````

---

## 🚢 Deployment (GitHub Pages)

Ensure `vite.config.js` includes the correct base:

```js
export default defineConfig({
  base: '/Personal_Portfolio/',
  plugins: [react()],
})
```

Then deploy:

```bash
npm run build
npm run deploy
```

The site will be available at:

```
https://Hasee10.github.io/Personal_Portfolio/
```

---

## 🛠 Tech Stack

| Tech            | Usage                    |
| --------------- | ------------------------ |
| React           | UI Framework             |
| Vite            | Build Tool               |
| Tailwind CSS    | Styling                  |
| Three.js / Drei | 3D Graphics              |
| Framer Motion   | Animations               |
| EmailJS         | Contact form integration |
| GitHub Pages    | Hosting & Deployment     |

---

## 📬 Contact

If you'd like to collaborate, feedback, or just connect:

* 🧑‍💻 LinkedIn: [linkedin.com/in/hasee10](https://www.linkedin.com/in/hasee10)
* 📧 Email: [ihaseebarshad@gmail.com](mailto:ihaseebarshad10@gmail.com)

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

* [Three.js](https://threejs.org/)
* [@react-three/fiber](https://docs.pmnd.rs/react-three-fiber/)
* [EmailJS](https://www.emailjs.com/)
* [Framer Motion](https://www.framer.com/motion/)
* [TailwindCSS](https://tailwindcss.com/)

---
