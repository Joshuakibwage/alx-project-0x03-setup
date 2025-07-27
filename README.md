# 🚀 Splash App – ALX Project 0x03 Setup

Welcome to **Splash App**, a modular, scalable Next.js + TypeScript application created as part of the **ALX Reactify TS: Mastering Advanced TypeScript in React** project.

This setup showcases **shared layouts**, **dynamic routing**, **Google Fonts integration**, and **imperative navigation** using `useRouter`.

---

## 📌 Project Highlights

- ✅ Shared **Header** and **Footer** layout components
- ✅ Reusable **Button** component with props and color themes
- ✅ Google Fonts (`Montserrat`) integration via global Tailwind setup
- ✅ **Imperative routing** with `useRouter` hook for interactive navigation
- ✅ Organized interface definitions in a centralized directory
- ✅ Custom **404 error page** with Tailwind styling and icons
- ✅ Built with **TypeScript**, **Tailwind CSS**, and **React Icons**

---

## 🧠 Learning Objectives

> This project demonstrates:

- DRY (Don't Repeat Yourself) layout patterns using a shared `Layout` component.
- Usage of third-party libraries like `react-icons`.
- Prop-driven, reusable components (e.g., `Button`).
- Advanced routing patterns in Next.js (imperative vs. declarative).
- Clean file organization for scalability and maintainability.
- Custom error handling with styled fallback pages.

---

## 📁 Project Structure

alx-project-0x03-setup/
├── components/
│ ├── common/
│ │ └── Button.tsx
│ └── layouts/
│ ├── Footer.tsx
│ ├── Header.tsx
│ └── Layout.tsx
├── interface/
│ └── index.ts
├── pages/
│ ├── 404.tsx
│ └── index.tsx
├── public/
├── styles/
│ └── global.css
├── tsconfig.json
├── tailwind.config.js
└── README.md


---

## ⚙️ Tech Stack

| Tool / Library     | Purpose                          |
|--------------------|----------------------------------|
| Next.js            | App framework (Routing + SSR)    |
| TypeScript         | Static typing                    |
| Tailwind CSS       | Utility-first CSS styling        |
| React Icons        | Icon components (`react-icons`)  |
| Google Fonts       | Global typography (Montserrat)   |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Joshuakibwage/alx-project-0x03-setup.git
cd alx-project-0x03-setup

2. Install Dependencies

npm install
# or
yarn install

3. Run the Development Server

npm run dev
# or
yarn dev

Visit http://localhost:3000 in your browser.
✨ Features in Action

    🌐 Landing Page Navigation:

        Buttons route to /generate-text-ai, /text-to-image, /counter-app via useRouter.

    🎨 Button Component:

        Accepts props: label, size, backgroundColor, action.

        Fully reusable across the app.

    🧩 Shared Layout:

        Layout.tsx wraps all pages with a common Header and Footer.

    📦 Interfaces:

        All interfaces are stored in interface/index.ts for maintainability.

    🔄 Custom 404 Page:

        Personalized error message and navigation using FaHome icon from React Icons.

🗂️ Available Pages
Path	Description
/	Home/Landing page
/generate-text-ai	Placeholder (currently 404)
/text-to-image	Placeholder (currently 404)
/counter-app	Placeholder (currently 404)
/404	Custom error page for invalid routes

    ⚠️ Note: Feature pages currently return 404 but are wrapped with the shared layout. You can build them out in future tasks.

🧠 Educational Value

This repo is part of a hands-on learning journey in mastering:

    TypeScript interfaces across components and pages

    DRY layout strategies

    Tailwind theming and customization

    Routing paradigms in Next.js

📜 License

This project is for educational use under the ALX Africa program. If you'd like to extend or reuse it, feel free to fork and adapt!
✍️ Author

Joshua Kibwage
ALX ProDev Frontend Track
