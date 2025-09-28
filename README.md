# 🔹 Next.js Project Setup and Basics

## 🔹 Step 1: Create the Repository on GitHub

1. Go to [GitHub](https://github.com/).
2. Click on the **New repository** button.
3. Name the repository:

   ```
   alx-project-0x02-setup
   ```
4. Add a description (optional):
   *“Next.js Project Setup with TypeScript and Tailwind CSS”*
5. Initialize with a **README.md**.
6. Click **Create Repository**.

---

## 🔹 Step 2: Clone Repository Locally

```bash
git clone https://github.com/SireTallest/alx-project-0x02-setup.git
cd alx-project-0x02-setup
```

---

## 🔹 Step 3: Initialize Next.js Project with TypeScript & Tailwind CSS

```bash
npx create-next-app@latest . --typescript --eslint --tailwind
```

When prompted, choose defaults. This will create:

* `pages/`
* `styles/`
* `public/`
* `tsconfig.json`
* `next.config.js`
* `.eslintrc.json`

---

## 🔹 Step 4: Update README.md

Replace the default content with this:

```markdown
# Next.js Project Setup and Basics

## Introduction
This repository serves as a comprehensive guide to setting up and working with **Next.js**, **TypeScript**, and **Tailwind CSS**.  
It covers project scaffolding, routing, reusable components, API integration, and best practices for building modern web applications.

---

## Project Description
This project introduces the fundamentals of creating a scalable Next.js app. It demonstrates how to structure a project properly, implement reusable components, handle routing, integrate APIs, and build responsive layouts with Tailwind CSS.

---

## Learning Objectives
By completing this project, you will:
- Scaffold a Next.js project with TypeScript and Tailwind CSS.
- Implement routing with the Pages Router.
- Create reusable UI components.
- Manage component props and state with TypeScript.
- Fetch and display data from external APIs.
- Build responsive layouts with navigation.
- Follow clean code and best practices.

---

## Requirements
- Node.js (v16 or later)
- npm or yarn
- GitHub account
- VS Code (recommended)
- Basic React + TypeScript knowledge

---

## Project Structure
```

alx-project-0x02/
├── components/
│   ├── common/
│   │   ├── Button.tsx
│   │   ├── Card.tsx
│   │   ├── PostCard.tsx
│   │   ├── PostModal.tsx
│   │   └── UserCard.tsx
│   └── layout/
│       └── Header.tsx
├── interfaces/
│   └── index.ts
├── pages/
│   ├── \_app.tsx
│   ├── \_document.tsx
│   ├── about.tsx
│   ├── home.tsx
│   ├── index.tsx
│   ├── posts.tsx
│   └── users.tsx
├── public/
│   └── assets/
│       └── images/
├── styles/
│   └── globals.css
├── .eslintrc.json
├── next.config.js
├── package.json
├── README.md
└── tsconfig.json

```

---

## Best Practices
- Organize components by domain (layout, common, etc.).
- Use TypeScript interfaces for props.
- Use ESLint for linting.
- Optimize API calls and enable lazy loading.
- Write descriptive commit messages.
- Maintain proper documentation.

---

## Implementation Guide
1. Initialize Next.js with TypeScript and Tailwind CSS.
2. Implement basic routing with the Pages Router.
3. Create reusable components (Button, Card, etc.).
4. Build navigation with a Header component.
5. Fetch and render data from JSONPlaceholder API.
6. Test and refine components step by step.
```

---

## 🔹 Step 5: Push Changes to GitHub

```bash
git add .
git commit -m "Initial setup with Next.js, TypeScript, and Tailwind CSS"
git push origin main
``
