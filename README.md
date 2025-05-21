# expert-barnacle

[![Deploy](https://github.com/hamiltoon/expert-barnacle/actions/workflows/deploy.yml/badge.svg)](https://github.com/hamiltoon/expert-barnacle/actions/workflows/deploy.yml)

[Live Site](https://hamiltoon.github.io/expert-barnacle/)

---

## Overview

This project is a React application built with Vite and styled using Tailwind CSS. It is automatically deployed to GitHub Pages on every push to the `main` branch.

## Features
- ⚡️ Fast development with Vite
- 🎨 Modern styling with Tailwind CSS
- 🚀 Automatic deployment to GitHub Pages
- 🔒 Simple login button as the start page

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18 or newer recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Setup
Clone the repository and install dependencies:

```bash
git clone https://github.com/hamiltoon/expert-barnacle.git
cd expert-barnacle
npm install
```

### Development
Start the local development server:

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the app.

### Build
Create a production build:

```bash
npm run build
```

The output will be in the `dist` directory.

### Deployment
Deployment is handled automatically by GitHub Actions. On every push to `main`, the app is built and deployed to the `gh-pages` branch, making it available at the [Live Site](https://hamiltoon.github.io/expert-barnacle/).
