# ALX Listing App

### Milestone 1: Scaffolding and Initial Setup for Listing Page
---

## About the Project

The ALX Listing App is the foundation for building a modern Airbnb clone.  
This milestone focuses on setting up the structure and configuration of the project using **Next.js**, **TypeScript**, **TailwindCSS**, and **ESLint**.  
The goal is to create a clean, organized, and scalable base that supports reusable components and follows standard best practices for web development.

---

## Learning Objectives

By completing this milestone, you will:

- Set up a production-ready Next.js project.  
- Use TypeScript for type safety and clean code.  
- Configure TailwindCSS for responsive and modern UI design.  
- Organize folders and components for scalability.  
# ALX Listing App

A small scaffold for an Airbnb-like listing page built with Next.js (Pages Router), TypeScript and Tailwind CSS. This repository contains the minimal project structure, example components, and configuration you can build on.

## Quick start

1. Clone the repo and install dependencies:

```bash
cd alx-listing-app
npm install
```

2. Run the development server:

```bash
npm run dev
```

Open http://localhost:3000 in your browser.

## What’s included

- Next.js (Pages Router) + TypeScript
- Tailwind CSS (configured via `tailwind.config.js`)
- PostCSS configuration
- ESLint (basic setup)
- Example components and interfaces

## Project structure

```
alx-listing-app/
├── components/
│   └── common/
│       ├── Card.tsx        # Reusable card component
│       └── Button.tsx      # Reusable button component
├── constants/
│   └── index.ts            # App-wide constants
├── interfaces/
│   └── index.ts            # TypeScript interfaces
├── pages/
│   ├── _app.tsx            # App wrapper (imports global CSS)
│   └── index.tsx           # Example landing page
├── public/
│   └── assets/             # Images and SVGs (placeholder included)
├── styles/
│   └── globals.css         # Tailwind directives only
├── tailwind.config.js
├── postcss.config.js
├── tsconfig.json
└── package.json
```

## Tailwind configuration (important files)

- `tailwind.config.js` — content paths already include `./pages/**/*.{ts,tsx}` and `./components/**/*.{js,ts,jsx,tsx}`.
- `styles/globals.css` — contains only Tailwind directives:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## Components

- `components/common/Card.tsx` — simple reusable card for listings.
- `components/common/Button.tsx` — basic button component with Tailwind styles.

## Interfaces

- `interfaces/index.ts` — contains `CardProps` and `ButtonProps` TypeScript interfaces used by the components.

## Assets

Place images, icons and other static assets in `public/assets/`. A placeholder SVG is included to get started.


## Author

Enya Elvis — Frontend Developer

GitHub: enyasystem
