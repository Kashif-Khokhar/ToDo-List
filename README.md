# 🎯 TaskFlow | Sleek Productivity Management

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge&logo=vercel)](https://to-do-list-delta-beige-30.vercel.app/)
[![React](https://img.shields.io/badge/React-19-blue?style=for-the-badge&logo=react)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-6-purple?style=for-the-badge&logo=vite)](https://vitejs.dev/)

**TaskFlow** is a modern, high-performance To-Do application engineered for a seamless user experience. Built with **React 19** and **Vite**, it combines minimalist aesthetics with robust functionality, featuring a dynamic theme engine and persistent data management.

---

## 🚀 Key Features

- **✨ Advanced CRUD Operations**: Seamlessly create, read, update, and delete tasks with an optimized UI flow.
- **🎨 Dynamic Theme Engine**: Toggle between 6 premium themes including professional Light/Dark modes and vibrant Glassmorphism-inspired gradients.
- **💾 Local Persistence**: Intelligent synchronization with `localStorage` ensures your productivity data is never lost.
- **🕒 Contextual Time-stamping**: Automated logging of task creation and modification times for better tracking.
- **📊 Real-time Productivity Metrics**: Live task counter provides immediate feedback on your current workload.
- **📱 Responsive Architecture**: Fluid layout transitions ensure a premium experience across mobile, tablet, and desktop devices.

---

## 🛠️ Technical Architecture

### Core Tech Stack
- **Framework**: [React 19](https://react.dev/) (Hooks-based architecture)
- **Build Optimization**: [Vite 6](https://vitejs.dev/)
- **Iconography**: [Bootstrap Icons](https://icons.getbootstrap.com/)
- **Styling**: Vanilla CSS3 with CSS Custom Properties (Variables) for the theme engine.

### Project Structure
```bash
src/
├── assets/          # Static assets and branding
├── Components/      # Modular UI Components
│   ├── Header.jsx   # Theme engine & Brand identity
│   ├── AddTask.jsx  # Task creation & editing logic
│   └── ShowTask.jsx # Task display, storage & deletion
├── App.jsx          # Root component & State orchestration
├── index.css        # Global design system & Theme definitions
└── main.jsx         # Application entry point
```

---

## 🎨 Professional Themes

| Theme | Style | Visual Feel |
| :--- | :--- | :--- |
| **Light** | Minimalist | Clean, high-contrast professional work environment. |
| **Medium** | Balanced | Soft neutrals designed for long-term focus. |
| **Dark** | Midnight | Deep slate blue optimized for low-light productivity. |
| **G-Blue** | Gradient | Modern indigo-to-cyan flow with deep depth. |
| **G-Astral** | Cosmic | Multi-layered dark gradient with soft highlight accents. |
| **G-Sunset** | Warm | Energetic pastel palette with soft transitions. |

---

## 💻 Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/Kashif-Khokhar/ToDo-List.git
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Start Development Server**
   ```bash
   npm run dev
   ```

The application will be accessible at `http://localhost:5173`.

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

Built with persistence and precision for modern developers.

