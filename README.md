# Gayatri Bennalkar — Portfolio

A modern, fully responsive personal portfolio website built with **React.js**, **Tailwind CSS**, and **Framer Motion**.

---

## ✨ Features

- **Dark Theme** with gradient accents (Emerald / Cyan / Violet)
- **Framer Motion** animations — fade-in, slide-in, float, stagger
- **Typing Animation** in Hero section (cycles through roles)
- **Glassmorphism** card design throughout
- **Project Filtering** — All / Web / Backend
- **Scroll Progress Indicator** (top bar)
- **Responsive Hamburger Menu** for mobile
- **Form Validation** in Contact section
- **Scroll-triggered** section reveals
- Custom scrollbar, mesh gradient orbs, animated grid

---

## 📁 Folder Structure

```
portfolio/
├── public/
│   └── RESUME.pdf          ← Place your resume PDF here
├── src/
│   ├── components/
│   │   ├── Navbar.jsx
│   │   ├── Hero.jsx
│   │   ├── About.jsx
│   │   ├── Skills.jsx
│   │   ├── Projects.jsx
│   │   ├── Education.jsx
│   │   ├── Contact.jsx
│   │   └── Footer.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
└── postcss.config.js
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ installed
- npm or yarn

### Installation

```bash
# 1. Navigate to project folder
cd portfolio

# 2. Install dependencies
npm install

# 3. Start development server
npm run dev
```

Open **http://localhost:5173** in your browser.

### Build for Production

```bash
npm run build
```

The `dist/` folder will be ready to deploy.

---

## 📦 Dependencies

| Package | Purpose |
|---|---|
| react, react-dom | UI framework |
| framer-motion | Animations |
| react-icons | Icon library |
| tailwindcss | Styling |
| vite | Build tool |

---

## 🎨 Customization

### Update Personal Info
Edit the data in each component:
- **Hero.jsx** — Name, intro, roles array
- **About.jsx** — Bio paragraphs, traits
- **Skills.jsx** — skillGroups array with levels
- **Projects.jsx** — projects array with title, tech, links
- **Education.jsx** — education and experience arrays
- **Contact.jsx** — contactInfo array
- **Footer.jsx** — Social links

### Add Your Resume
Place your `RESUME.pdf` in the `/public` folder.

### Change Colors
Edit `tailwind.config.js` and `src/index.css` CSS variables.

---

## 🌐 Deployment

Deploy easily to **Vercel**, **Netlify**, or **GitHub Pages**:

```bash
# Vercel
npx vercel

# Netlify drag-and-drop the dist/ folder after npm run build
```

---

## 📄 License
MIT — free to use and customize.
