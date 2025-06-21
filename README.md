
![image](https://github.com/user-attachments/assets/9978a0fc-d3a9-4681-91fa-c762d5221165)


 📄 `README.md` — **React + Vite**

````markdown
 🛍️ Brand Page – React + Vite Project

A modern, responsive **brand showcase website** built using **React.js with Vite**.  
This project is designed to highlight brand identity with an elegant layout, smooth UX, and optimized performance — ideal for landing pages, digital products, or creative portfolios.

---

 🔗 Live Demo

▶️ [View Brand Page](https://prabha34.github.io/React-Projects/project-1-brand-page)

---

 ✨ Key Features

- ⚡ Built with **Vite** (blazing fast dev + build time)
- ⚛️ Uses **React.js** for component-based architecture
- 📱 Mobile-first, responsive design
- 🎨 Clean UI with reusable components
- 🌐 Deployed on **GitHub Pages**

---

 ⚙️ Getting Started

 📦 Installation (Run Locally)

1. **Clone the repository**
```bash
git clone https://github.com/prabha34/React-Projects.git
````

2. **Navigate to the project directory**

```bash
cd React-Projects/project-1-brand-page
```

3. **Install dependencies**

```bash
npm install
```

4. **Run the development server**

```bash
npm run dev
```

The app will be available at `http://localhost:5173` (or similar, as shown in your terminal).

---

 🚀 Deployment Guide (GitHub Pages)

This Vite app is deployed using [`gh-pages`](https://www.npmjs.com/package/gh-pages).

 🔧 Step 1: Set base path in `vite.config.js`

Inside `vite.config.js`, add the `base` option:

```js
import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'

export default defineConfig({
  base: '/React-Projects/project-1-brand-page/',
  plugins: [react()],
})
```

> Note: Adjust the path to match your folder structure in the GitHub repo.

---

 📜 Step 2: Add deploy scripts to `package.json`

```json
"scripts": {
  "dev": "vite",
  "build": "vite build",
  "preview": "vite preview",
  "predeploy": "npm run build",
  "deploy": "gh-pages -d dist"
}
```

---

 📥 Step 3: Install `gh-pages`

```bash
npm install gh-pages --save-dev
```

---

 🧱 Step 4: Build the project

```bash
npm run build
```

---

 🌐 Step 5: Deploy to GitHub Pages

```bash
npm run deploy
```

✅ This will push your `dist/` folder to the `gh-pages` branch.

Once deployed, your live site will be available at:

```
https://prabha34.github.io/React-Projects/project-1-brand-page/
```

 📌 Future Enhancements

* 🔄 Add animations using **Framer Motion**
* 📬 Integrate a backend contact form (e.g., EmailJS)
* 🧾 Add testimonials, gallery, or pricing sections
* 🔍 Improve SEO and meta tags for better discoverability

---

 🙋‍♀️ Author

Made with 💖 by **Swathi**
GitHub: [@prabha34](https://github.com/prabha34)

---

 📄 License

This project is licensed under the [MIT License](LICENSE).

````

---
 🧠 TL;DR Deployment Cheatsheet

```bash
npm install gh-pages --save-dev
# edit vite.config.js base: '/repo-name/folder-name/'
npm run build
npm run deploy
````


