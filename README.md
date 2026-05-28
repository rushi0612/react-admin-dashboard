# React Admin Dashboard

A fully featured **Admin Dashboard** built with React.js, Tailwind CSS, and Syncfusion UI components. Includes multiple pages, interactive charts, data tables, dark/light mode, and theme customization.

## 🔗 Live Demo


---

## ✨ Features

- 📊 **Ecommerce Dashboard** — earnings overview, revenue stats, sparkline charts
- 📦 **Orders & Customers** — data tables with product and customer info
- 👥 **Employees** — employee management table
- 📋 **Kanban Board** — drag and drop task management
- 📅 **Calendar** — interactive calendar with events
- 🎨 **Theme Settings** — 5 color themes + Dark/Light mode toggle
- 📈 **Charts** — Line, Area, Bar, Pie, Financial, Stacked, Pyramid, Color Mapping
- ✏️ **Rich Text Editor** — built-in editor page
- 🎨 **Color Picker** — interactive color picker tool
- 📱 **Responsive Design** — works on desktop and mobile

---

## 🛠️ Tech Stack

| Tech | Usage |
|------|-------|
| React.js | UI components & routing |
| Tailwind CSS | Styling & dark mode |
| Syncfusion | Charts, Kanban, Calendar, Grid |
| React Router v6 | Page navigation |
| React Icons | Icon library |
| Context API | Global state (theme, color, menu) |

---

## 🚀 Getting Started

### Prerequisites
- Node.js installed
- npm

### Installation

```bash
# Clone the repo
git clone https://github.com/rushi0612/react-admin-dashboard.git

# Go into the folder
cd react-admin-dashboard

# Install dependencies
npm install

# Start development server
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📁 Project Structure

```
react-admin-dashboard/
├── src/
│   ├── components/
│   │   ├── Charts/          # Reusable chart components
│   │   ├── Navbar.jsx
│   │   ├── Sidebar.jsx
│   │   ├── Header.jsx
│   │   ├── ThemeSettings.jsx
│   │   └── ...
│   ├── pages/
│   │   ├── Ecommerce.jsx    # Main dashboard
│   │   ├── Orders.jsx
│   │   ├── Employees.jsx
│   │   ├── Customers.jsx
│   │   ├── Kanban.jsx
│   │   ├── Calendar.jsx
│   │   ├── Charts/          # Chart pages
│   │   └── ...
│   ├── contexts/
│   │   └── ContextProvider.js  # Global theme & state
│   ├── data/
│   │   └── dummy.js         # Mock data
│   └── App.js
└── package.json
```

---

## 📸 Pages Overview

- **/** — Ecommerce Dashboard (earnings, charts, recent transactions)
- **/orders** — Orders data table
- **/employees** — Employee management
- **/customers** — Customer list
- **/kanban** — Kanban task board
- **/calendar** — Event calendar
- **/editor** — Rich text editor
- **/color-picker** — Color picker tool
- **/line, /area, /bar, /pie** — Chart pages

---

## 🙋‍♂️ Author

**Rushikesh Patil**
- GitHub: [@rushi0612](https://github.com/rushi0612)
- LinkedIn: [Rushikesh Patil](https://www.linkedin.com/in/rushi0612)
