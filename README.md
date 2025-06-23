# 🐾 Meowmentum – Website (Web Frontend)

This is the **official website and web app** for **Meowmentum**, a smart, AI-powered English language learning platform. The frontend is built with **Next.js** and **TypeScript**, optimized for performance, responsiveness, and learner engagement.

> 💡 Learn more about the full platform: [Meowmentum Overview](https://github.com/meowmentum-education)

---

## 🧠 Features

- 🌐 **Next.js** SPA with pre-rendering and dynamic routing
- 🎨 **Tailwind CSS** for clean, responsive design
- 🧩 Modular components for vocabulary, quizzes, and progress tracking
- 🔐 Integrated with JWT-authenticated APIs (via backend)
- ⚙️ Configurable via environment variables
- 📱 Mobile-friendly (PWA-ready)

---

## 🛠️ Tech Stack

| Layer       | Technology                          |
|-------------|--------------------------------------|
| Framework   | React (Next.js 14)                   |
| Language    | TypeScript                           |
| Styling     | Tailwind CSS                         |
| State       | React Context API / Zustand (optional) |
| Forms       | React Hook Form + Zod                |
| Auth        | JWT (via backend API)                |
| API Client  | Axios / Fetch API                    |
| Testing     | Jest + React Testing Library (optional) |
| Deployment  | Vercel / Netlify / Custom CI (planned) |

---

## 📁 Project Structure

```
/meowmentum-website
├── components/       # Reusable UI components
├── pages/            # Next.js routes
│   ├── index.tsx     # Homepage
│   ├── login.tsx     # Auth routes
│   └── dashboard/    # Protected student features
├── public/           # Static assets
├── styles/           # Tailwind config & globals
├── utils/            # Helpers and API client
├── hooks/            # Custom React hooks
├── types/            # Shared TypeScript types
├── .env.local        # API base URL, secrets
└── next.config.js    # Next.js configuration
```

---

## 🚀 Getting Started

### 📦 Prerequisites

- Node.js (v18+)
- Yarn or npm
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
   NEXT_PUBLIC_API_URL=https://localhost:5001/api
   NEXT_PUBLIC_APP_NAME=Meowmentum
   ```

4. **Run locally**

   ```bash
   npm run dev
   ```

   Open `http://localhost:3000` to view the site.

---

## 🔐 Authentication

- Uses **JWT tokens** stored in localStorage (or HttpOnly cookies optionally)
- User sessions handled through backend-authenticated endpoints

---

## 🧪 Testing (optional setup)

If tests are configured:

```bash
npm run test
```

---

## 🧱 Development Notes

- Tailwind config in `tailwind.config.ts`
- Protected routes use simple route guards or middleware (WIP)
- Mobile-first UI tested via dev tools and PWA audit

---

## 📦 Deployment

- Supports auto-deploy with **Vercel** or **Netlify**
- Dockerfile and CI/CD pipeline planned

---

## 🤝 Contributing

1. Fork this repo
2. Create a branch (`feature/your-feature`)
3. Commit your changes
4. Open a pull request 🙌

---

## 👥 Maintainers

- 👤 **Vũ Trần Quang Minh** – Frontend & AI Lead  
  📧 `minhvtqgcs220006@fpt.edu.vn`  
  GitHub: [@vutranquangminh](https://github.com/vutranquangminh)

---

> *Meowmentum – learn smarter, not harder. Personalized English learning redefined.*

---