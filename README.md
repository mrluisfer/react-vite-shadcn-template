# React + TypeScript + Vite

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/mrluisfer/react-vite-shadcn-template/blob/main/LICENSE)
[![React](https://img.shields.io/badge/react.js-blue.svg)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/vite-purple.svg)](https://vitejs.dev/)
[![TypeScript](https://img.shields.io/badge/typescript-blue.svg)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/tailwindcss-v4-blue.svg)](https://tailwindcss.com/)
[![Tailwind CSS](https://img.shields.io/badge/pnpm-v8-orange.svg)](https://tailwindcss.com/)

This template provides a minimal setup to get React working in Vite with HMR and some Biome.js rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

This template uses Biome.js rules to provide a better linting and formatting experience, you can find more rules and configuration options in the [Biome.js documentation](https://biomejs.dev/).

## 🎉 Features

- **React** - A JavaScript library for building user interfaces.
- **Vite** - A fast, opinionated frontend build tool.
- **TypeScript** - A typed superset of JavaScript that compiles to plain JavaScript.
- **Tailwind CSS** - A utility-first CSS framework.
- **Tailwind Prettier Plugin** - A Prettier plugin for formatting Tailwind CSS classes.
- **Biome.js** - A pluggable linting utility for JavaScript and TypeScript.
- **PostCSS** - A tool for transforming CSS with JavaScript.
- **Autoprefixer** - A PostCSS plugin to parse CSS and add vendor prefixes.
- **shadcn/ui** - Beautifully designed components that you can copy and paste into your apps.

## ⚙️ Prerequisites

Make sure you have the following installed on your development machine:

- Node.js (version 20 or above)
- pnpm (package manager)

## 🚀 Getting Started

Follow these steps to get started with the react-vite-ui template:

1. Clone the repository:

   ```bash
   git clone https://github.com/mrluisfer/react-vite-shadcn-template
   ```

   Or use it as a template on GitHub.

2. Navigate to the project directory:

   ```bash
   cd react-vite-shadcn-template # And rename the folder to your project name
   ```

3. Install the dependencies:

   ```bash
   pnpm install
   ```

4. Start the development server:

   ```bash
   pnpm dev
   ```

## 📜 Available Scripts

- pnpm dev - Starts the development server.
- pnpm build - Builds the production-ready code.
- pnpm lint - Runs Biome.js to analyze and lint the code.
- pnpm preview - Starts the Vite development server in preview mode.

## 📂 Project Structure

The project structure follows a standard React application layout:

```python
react-vite-ui/
  ├── node_modules/      # Project dependencies
  ├── public/            # Public assets
  ├── src/               # Application source code
  │   ├── components/    # React components
  │   │   └── ui/        # shadc/ui components
  │   ├── styles/        # CSS stylesheets
  │   ├── lib/           # Utility functions
  │   ├── App.tsx        # Application entry point
  │   └── index.tsx      # Main rendering file
  ├── biome.json         # Biome.js configuration
  ├── index.html         # HTML entry point
  ├── package.json       # Project metadata and dependencies
  ├── components.json    # shadcn/ui components configuration
  ├── postcss.config.js  # PostCSS configuration
  ├── tailwind.config.ts # Tailwind CSS configuration
  ├── tsconfig.json      # TypeScript configuration
  └── vite.config.ts     # Vite configuration
```

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](https://choosealicense.com/licenses/mit/) file for details.

Made with ❤️ by [mrluisfer](https://github.com/mrluisfer)
