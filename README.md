# 🛒 Shoppy — React Admin Dashboard

A blazing-fast, fully-featured **React** admin dashboard template built with **Create React App + Tailwind CSS + Syncfusion React UI**. It ships with light / dark themes, 8 accent colors, responsive layouts, advanced charts, a Kanban board, calendar, data grid, and everything you need to kick-start your next internal tool or SaaS admin panel.

## Table of Contents
- [Live Demo](#live-demo)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Folder Structure](#folder-structure)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

---

## Live Demo

👉 **Production build:** https://your-shopsy.vercel.app/

---

## Features

- ✨ **Create React App powered**  
- 🎨 **Theme switcher** – light, dark & 8 brand colors  
- 📊 **Advanced charts** – Line, Area, Column, Pie, Radar, Financial, Sparkline & Stacked  
- 🗂️ **Data grid** – filtering, pagination & sorting out-of-the-box  
- 🗓️ **Calendar** – drag-and-drop events, day / week / month views  
- 📌 **Kanban board** – drag cards between custom swim-lanes  
- 🏎️ **Responsive design** with smooth UX  
- 🔒 **Auth-ready** structure – drop-in JWT / Firebase / Supabase  

---

## Tech Stack

| Category | Libraries |
|---|---|
| Framework | [React](https://reactjs.org/) + [Create React App](https://create-react-app.dev/) |
| Styling | [Tailwind CSS 3](https://tailwindcss.com/) |
| UI Components | [Syncfusion React](https://www.syncfusion.com/react-components) (Charts, Grid, Calendar, Kanban) |
| Routing | [React Router 6](https://reactrouter.com/) |
| Icons | [react-icons](https://react-icons.github.io/react-icons/) |
| State Mgmt | React Context API |
| Tooling | ESLint, Prettier |

---

## Getting Started

### Prerequisites

- **Node.js >= 18**
- **npm** or **yarn**

### Clone & Run

```bash
# clone the repo
git clone https://github.com/sumit-616/shoppy.git
cd shoppy

# install dependencies
npm install         # or yarn install

# start dev server
npm start           # or yarn start
```

The app will be available at **http://localhost:3000**.

---

## Available Scripts

| Command | Description |
|---|---|
| `npm start` | Start development server with Create React App |
| `npm run build` | Create an optimized production build |
| `npm run test` | Run tests (if configured) |
| `npm run lint` | Lint all source files with ESLint (optional) |
| `npm run format` | Format source files with Prettier (optional) |

---

## Folder Structure

```text
src
├── components
│   ├── Charts/
│   ├── Button.jsx
│   ├── Cart.jsx
│   ├── ChartsHeader.jsx
│   ├── Chat.jsx
│   ├── Footer.jsx
│   ├── Header.jsx
│   ├── Navbar.jsx
│   ├── Notification.jsx
│   ├── Sidebar.jsx
│   ├── ThemeSettings.jsx
│   └── UserProfile.jsx
├── contexts
│   └── ContextProvider.js
├── data
│   ├── avatar.jpg
│   ├── avatar2.jpg
│   ├── avatar3.png
│   ├── product1.jpg — product9.jpg
│   └── welcome-bg.svg
├── pages
│   ├── Charts/
│   ├── Calendar.jsx
│   ├── ColorPicker.jsx
│   ├── Customers.jsx
│   ├── Ecommerce.jsx
│   ├── Editor.jsx
│   ├── Employees.jsx
│   ├── Kanban.jsx
│   └── Orders.jsx
├── App.css
├── App.js
├── index.css
└── index.js
```
---

## Contributing

Contributions, issues and feature requests are welcome!  
Feel free to **open an issue** or **submit a pull request**.

1. Fork the repository  
2. Create your feature branch (`git checkout -b feat/amazing-feature`)  
3. Commit your changes (`git commit -m 'feat: add amazing feature'`)  
4. Push to the branch (`git push origin feat/amazing-feature`)  
5. Open a Pull Request

