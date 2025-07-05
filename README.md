# 🐾 Meowmentum – Website

This is the **official website and web app** for **Meowmentum**, a smart, AI-powered English–Vietnamese language learning platform.  
The frontend is built with **React**, **TypeScript**, and **Tailwind CSS**, optimized for responsiveness, accessibility, and learner engagement.

> 💡 Learn more about the full platform: [Meowmentum Overview](https://github.com/meowmentum-education)

---

## 🧠 Features

- ⚛️ **React.js SPA** with modular routing
- 🎨 **Tailwind CSS** for clean, responsive UI
- 🧩 Reusable components for vocabulary, quizzes, progress tracking
- 🔐 Integrated with secure JWT-authenticated APIs (backend)
- 📱 Fully mobile-responsive (React Native version available)
- 🔧 Configurable via environment variables
- 🚀 Planned support for PWA and offline caching

---

## 🛠️ Tech Stack

| Layer       | Technology                            |
|-------------|----------------------------------------|
| Framework   | React                               |
| Language    | TypeScript                             |
| Styling     | Tailwind CSS                           |
| State       | React Context API / Zustand (optional) |
| Forms       | React Hook Form + Zod                  |
| Auth        | JWT (via backend API)                  |
| API Client  | Axios / Fetch API                      |
| Testing     | Jest + React Testing Library (planned) |
| Deployment  | Vercel / Netlify / CI pipeline (planned) |

---

## 📁 Project Structure

```
/meowmentum-website
├── components/       # Reusable UI components
├── pages/            # SPA views (e.g., Home, Login, Dashboard)
├── public/           # Static assets
├── styles/           # Tailwind config & global styles
├── utils/            # API clients and helpers
├── hooks/            # Custom React hooks
├── types/            # Shared TypeScript types
├── .env.local        # API URL and app config
└── vite.config.ts    # Vite (if used) or CRA config
```

---

## 🚀 Getting Started

### 📦 Prerequisites

- Node.js (v18+)
- npm or Yarn
- A running instance of the [Meowmentum Backend API](https://github.com/trandaine/meowmentum-backend)

### 🔧 Installation

1. **Clone the repo**

   ```bash
   git clone https://github.com/vutranquangminh/meowmentum-website.git
   cd meowmentum-website
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Configure environment**

   Create a `.env.local` file:

   ```env
   VITE_API_URL=https://localhost:5001/api
   VITE_APP_NAME=Meowmentum
   ```

4. **Run locally**

   ```bash
   npm run dev
   ```

   Then open `http://localhost:3000` to view the app.

---

## 🔐 Authentication

- Uses **JWT tokens** stored in `localStorage` (or cookies, if configured)
- Backend verifies credentials and returns token on login
- Protected routes and UI handled via React guards or custom hooks

---

## 🧪 Testing (optional)

If tests are implemented:

```bash
npm run test
```

Uses **Jest** + **React Testing Library**

---

## 🧱 Development Notes

- Tailwind configuration in `tailwind.config.ts`
- Uses React Router for page navigation
- State management is flexible (Context API or Zustand)
- Fully responsive: tested across mobile & desktop breakpoints

---

## 📦 Deployment

- Deployable to **Vercel**, **Netlify**, or custom Docker-based CI
- Environment variables defined in `.env` or deployment config
- PWA setup under consideration for offline support

---

## 🤝 Contributing

1. Fork this repo
2. Create a feature branch (`feature/your-feature`)
3. Commit your changes
4. Open a Pull Request 🙌

---

## 👥 Maintainers

- 👤 **Vũ Trần Quang Minh** – Frontend & AI Lead  
  📧 `minhvtqgcs220006@fpt.edu.vn`  
  GitHub: [@vutranquangminh](https://github.com/vutranquangminh)

---

> *Meowmentum – learn smarter, not harder. Personalized English learning redefined.*

---