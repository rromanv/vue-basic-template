# Vue 3 + Vite Template

A modern Vue 3 starter template with Vite, Tailwind CSS, ESLint, and Prettier.

## Features

- ⚡️ [Vue 3](https://vuejs.org/) with `<script setup>` SFC syntax
- 🚀 [Vite 7](https://vite.dev/) for blazing fast development
- 🎨 [Tailwind CSS 4](https://tailwindcss.com/) with CSS-first configuration
- 📦 [Vue Router 4](https://router.vuejs.org/) for routing
- 🔍 [ESLint 9](https://eslint.org/) with flat config
- 💅 [Prettier 3](https://prettier.io/) with Tailwind CSS plugin

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Vue - Official](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (formerly Volar)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)

## Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Available Scripts

| Script               | Description                       |
| -------------------- | --------------------------------- |
| `npm run dev`        | Start development server          |
| `npm run build`      | Build for production              |
| `npm run preview`    | Preview production build          |
| `npm run lint`       | Lint and auto-fix with ESLint     |
| `npm run lint:check` | Check linting without auto-fix    |
| `npm run format`     | Format code with Prettier         |
| `npm run format:check` | Check formatting without auto-fix |

## Project Structure

```
├── public/              # Static assets
├── src/
│   ├── assets/          # Asset files (images, fonts, etc.)
│   │   ├── style.css    # Global styles with Tailwind
│   ├── components/      # Vue components
│   ├── views/           # Page components
│   ├── App.vue          # Root component
│   ├── main.js          # App entry point
│   ├── router.js        # Vue Router configuration
├── eslint.config.js     # ESLint flat config
└── vite.config.js       # Vite configuration with Tailwind plugin
```

## Tailwind CSS 4

This template uses Tailwind CSS 4 with the new CSS-first configuration approach. Tailwind is integrated directly as a Vite plugin (`@tailwindcss/vite`), eliminating the need for separate `tailwind.config.js` and `postcss.config.js` files.

To customize Tailwind, use CSS variables and the `@theme` directive in your CSS file. See the [Tailwind CSS documentation](https://tailwindcss.com/docs) for more details.
