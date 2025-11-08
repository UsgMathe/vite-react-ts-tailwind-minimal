# ⚡ Vite + React + TypeScript + TailwindCSS + Prettier (Template)

<p align="center">
  <img src="https://img.shields.io/badge/Template-Official-4ade80?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Vite-4.x-646CFF?style=for-the-badge&logo=vite" />
  <img src="https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react" />
  <img src="https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript" />
  <img src="https://img.shields.io/badge/TailwindCSS-3.x-06B6D4?style=for-the-badge&logo=tailwindcss" />
  <img src="https://img.shields.io/badge/Prettier-Enabled-F7B93E?style=for-the-badge&logo=prettier" />
  <img src="https://img.shields.io/badge/License-MIT-000?style=for-the-badge" />
</p>

> ✅ **Official GitHub Template** for creating modern React applications with a clean, minimal, production-ready setup.

---

## ✨ Features

- ⚡ **Vite** for ultra-fast development
- ⚛️ **React + TypeScript** with strong typing
- 🎨 **TailwindCSS** out of the box
- 🧹 **Prettier + prettier-plugin-tailwindcss**
- 🧭 **`@/*` path alias** preconfigured
- ✅ Clean, minimal, scalable folder structure
- 📦 Zero unnecessary dependencies
- 🚀 Production-ready configuration

---

## 🧠 Why This Template?

Most templates are either too minimal (missing quality-of-life tooling) or too bloated (extra libraries you don't want).

This template is designed to be:

### ✔ Minimal

No unnecessary packages, no boilerplate noise.

### ✔ Scalable

A structure that grows with your project.

### ✔ Professional

Prettier, Tailwind sorting, alias resolution, and clean formatting.

### ✔ Fast

Vite + React + Tailwind targeted for high developer experience (DX).

If your goal is to **start fast and stay organized**, this template is ideal.

---

## 🚀 Getting Started

### ✅ Using Vite

```bash
pnpm create vite@latest my-app -- --template github:usgmathe/vite-react-ts-tailwind-minimal
```

### ✅ Using GitHub CLI

```bash
gh repo create my-app --template=usgmathe/vite-react-ts-tailwind-minimal
cd my-app
pnpm install
pnpm run dev
```

---

## 🎨 Prettier + TailwindCSS Plugin

This template includes:

```
prettier-plugin-tailwindcss
```

It ensures:

- Automatic Tailwind class sorting
- Cleaner and more consistent formatting
- Maintains industry-level standards

Prettier config:

```json
{
  "$schema": "https://json.schemastore.org/prettierrc",
  "semi": true,
  "singleQuote": false,
  "trailingComma": "all",
  "printWidth": 120,
  "tabWidth": 2,
  "useTabs": false,
  "quoteProps": "as-needed",
  "jsxSingleQuote": false,
  "bracketSpacing": true,
  "bracketSameLine": false,
  "arrowParens": "always",
  "plugins": ["prettier-plugin-tailwindcss"]
}
```

---

## 🧭 Alias Configuration

Import from `src` using:

```ts
import Header from "@/components/Header";
import Home from "@/pages/Home";
```

---

## ✅ Scripts

```bash
pnpm run dev       # Start dev server
pnpm run build     # Create production build
pnpm run preview   # Preview built output
```

---

## 📦 Requirements

- Node.js **18+**
- pnpm, npm, or yarn

---

## 🧑‍💻 Ideal Use Cases

- Starting new React projects quickly
- Professional frontend projects
- Monorepo base templates
- Learning environments
- Code consistency across multiple repositories

---

## 📝 License

Licensed under the **MIT License**.

---

## ✨ Author

Created by **Matheus Gabriel Valenga**
📌 GitHub: [https://github.com/usgmathe](https://github.com/usgmathe)
