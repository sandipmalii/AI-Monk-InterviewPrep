# 🧠 AI Monk Interview Prep

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![React](https://img.shields.io/badge/React-TypeScript-blue)](https://reactjs.org/)
[![TailwindCSS](https://img.shields.io/badge/Style-TailwindCSS-38B2AC)](https://tailwindcss.com/)
[![Firebase](https://img.shields.io/badge/Backend-Firebase-FFCA28)](https://firebase.google.com/)
[![Clerk](https://img.shields.io/badge/Auth-Clerk-5436DA)](https://clerk.dev/)

Ace your dream interviews with the power of AI!  
**AI Monk Interview Prep** is a modern, full-stack AI mock interview platform that enables users to practice interviews in real-time, receive personalized feedback, and build confidence — powered by **Google Gemini AI**.

**Date** :- 21-04-25

---
## 🌐 Live Demo

🚀 [Coming Soon 🚧 – Deploy via Vercel or Render]

---

## 📚 Table of Contents

- [✨ Features](#-features)
- [🚀 Tech Stack](#-tech-stack)
- [💡 What You'll Learn](#-what-youll-learn)
- [📦 Getting Started](#-getting-started)
- [🧪 Project Structure](#-project-structure)
- [📸 Screenshots](#-screenshots)
- [🛡️ License](#️-license)

---

## ✨ Features

✅ **Secure Login & Registration** – Powered by [Clerk](https://clerk.dev)  
✅ **Create Custom Interviews** – Choose your field and configure interview settings  
✅ **AI-Driven Questions** – Realistic interview questions from **Google Gemini AI**  
✅ **Voice Analysis** – Receive **Text-to-Speech feedback** to improve responses  
✅ **User Progress Tracking** – Persistent data management with Firebase  
✅ **Sleek & Responsive UI** – Built with Shadcn UI + TailwindCSS

---

## 🚀 Tech Stack

| Frontend | Backend | Authentication | AI Integration | Styling | DB |
|----------|---------|----------------|----------------|---------|----|
| React + TypeScript | Firebase | Clerk | Google Gemini AI | Shadcn UI + TailwindCSS | Firestore |

---

## 💡 What I Have Learn

🔍 How to integrate **AI APIs** like Gemini into React apps  
🛠️ Setup **Firebase** for real-time data handling  
🔐 Secure your app using **Clerk Authentication**  
🎨 Build beautiful & accessible UIs using **Shadcn UI**  
🚀 Deploy a fully functional mock interview platform

---

## 🖼️ Screenshots
Coming soon... (Add images or GIFs of the platform here)

---


## License
This project is licensed under the MIT License.

## 💬 Let’s Connect

💻 Built with passion by **[@sandipmalii](https://github.com/sandipmalii)**  
🌟 If you found this project helpful:  
⭐ Star the repo  
🔗 Share it with your friends  
💬 Drop a suggestion or feedback anytime!

---

Made with ❤️ | Happy building, Sandip 🚀

---

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default tseslint.config({
  languageOptions: {
    // other options...
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
})
```

- Replace `tseslint.configs.recommended` to `tseslint.configs.recommendedTypeChecked` or `tseslint.configs.strictTypeChecked`
- Optionally add `...tseslint.configs.stylisticTypeChecked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and update the config:

```js
// eslint.config.js
import react from 'eslint-plugin-react'

export default tseslint.config({
  // Set the react version
  settings: { react: { version: '18.3' } },
  plugins: {
    // Add the react plugin
    react,
  },
  rules: {
    // other rules...
    // Enable its recommended rules
    ...react.configs.recommended.rules,
    ...react.configs['jsx-runtime'].rules,
  },
})
```


## 📦 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/sandipmalii/AI-Monk-InterviewPrep.git
cd AI-Monk-InterviewPrep

 --Install Dependencies--
pnpm install

--Run the App--
pnpm run dev
