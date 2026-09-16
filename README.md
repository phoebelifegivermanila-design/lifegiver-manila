# Lifegiver Manila

Official web application for **Lifegiver Manila**, built with [Next.js](https://nextjs.org), React 19, TypeScript, and Tailwind CSS.

---

## 🚀 Tech Stack

- **Framework**: [Next.js](https://nextjs.org) (App Router)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Linting**: [ESLint](https://eslint.org/)
- **Deployment**: [Vercel](https://vercel.com)

---

## 🛠️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18.17 or higher recommended)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/phoebelifegivermanila-design/lifegiver-manila.git
   cd lifegiver-manila
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to view the application.

---

## 📁 Project Structure

```text
├── public/              # Static assets (images, icons, SVGs)
├── src/
│   └── app/
│       ├── layout.tsx   # Root layout and font configuration
│       ├── page.tsx     # Home page
│       └── globals.css  # Global styles and Tailwind configuration
├── next.config.ts       # Next.js configuration
├── tsconfig.json        # TypeScript configuration
├── eslint.config.mjs    # ESLint configuration
└── package.json         # Project metadata and dependencies
```

---

## 📦 Scripts

- `npm run dev` — Starts the development server with Hot Module Replacement.
- `npm run build` — Compiles and builds the production application.
- `npm run start` — Starts the production server after building.
- `npm run lint` — Runs ESLint checks across project files.

---

## 🌐 Deployment on Vercel

This repository is optimized for deployment with [Vercel](https://vercel.com):

1. Go to [Vercel Dashboard](https://vercel.com/dashboard).
2. Click **Add New...** > **Project**.
3. Import the `lifegiver-manila` repository (`https://github.com/phoebelifegivermanila-design/lifegiver-manila`).
4. Keep the default Next.js build settings and click **Deploy**.
