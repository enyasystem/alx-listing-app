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
- Create basic reusable components such as Card and Button.

---

## Requirements

### Prerequisites

- Basic knowledge of Next.js, React, and TypeScript.  
- Familiarity with TailwindCSS.  
- Understanding of ESLint and project structuring.

### Technical Requirements

- **Next.js version:** 13+  
- **Node.js version:** 16+  
- A text editor like VS Code with Tailwind and TypeScript extensions.

---

## Project Setup
Tailwind Configuration

tailwind.config.js

module.exports = {
  content: [
    './pages/**/*.{ts,tsx}',
    './components/**/*.{js,ts,jsx,tsx}',
  ],
  theme: {
    extend: {},
  },
  plugins: [],
};


styles/globals.css

@tailwind base;
@tailwind components;
@tailwind utilities;

Folder Structure
alx-listing-app/
│
├── components/
│   └── common/
│       ├── Card.tsx
│       └── Button.tsx
│
├── interfaces/
│   └── index.ts
│
├── constants/
│   └── index.ts
│
├── public/
│   └── assets/
│       └── (images, icons, SVGs)
│
├── pages/
│   └── index.tsx
│
├── styles/
│   └── globals.css
│
└── README.md

Run the following command to create the app:

```bash
npx create-next-app@latest alx-listing-app --typescript --tailwind --eslint --no-app-router --no-src-dir
```
## Components and Interfaces

Card.tsx – reusable component for property display.

Button.tsx – reusable component for actions like “Book Now” or “View Details”.

interfaces/index.ts – defines TypeScript interfaces such as CardProps and ButtonProps.

constants/index.ts – stores reusable data and configuration values.

public/assets/ – contains project images and icons.

Run the Project

After cloning the repository:

cd alx-listing-app
npm install
npm run dev


Then open your browser and visit http://localhost:3000
 to confirm that the app runs successfully.

Repository Information

Repository Name: alx-listing-app

Required Files:

pages/index.tsx

components/common/Card.tsx

components/common/Button.tsx

interfaces/index.ts

constants/index.ts

public/assets/

README.md

Assessment and Submission

Submit before the deadline.

Include all required files.

Generate and submit your review link.

Participate in peer review sessions.

Author

Enya Elvis
Frontend Developer, Nigeria
GitHub: your-username
