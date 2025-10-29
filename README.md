# 📝 NoteFlow Frontend

A **Google Keep–style notes app** built using **Next.js**, **TypeScript**, and **Tailwind CSS**, with linting, formatting, and CI/CD integration.  
This repository contains the **frontend** for the NoteFlow project. The backend (Express + MongoDB) is in a separate repository.

---

## 🚀 Tech Stack

- **Framework:** Next.js (TypeScript)
- **Styling:** Tailwind CSS
- **Linting & Formatting:** ESLint + Prettier
- **Version Control:** Git & GitHub
- **CI/CD:** GitHub Actions
- **Code Quality:** SonarQube (Planned)

---

## 🏗️ Project Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/sai2yeshwanth/noteflow-frontend.git
cd noteflow-frontend

## Getting Started

First, run the development server:
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

🧩 Folder Structure

src/
 
 ├── components/    # Reusable UI components
 
 ├── pages/         # Next.js pages
 
 ├── hooks/         # Custom React hooks
 
 ├── services/      # API calls and external integrations
 
 ├── utils/         # Helper functions
 
 ├── styles/        # Global styles

🧹 Code Quality

To check linting and formatting:
```bash
npm run lint
npm run format
```
Prettier will auto-format your code, and unused imports will be removed on save (via VS Code settings).

⚙️ Environment Variables

Create a .env.local file and include:
NEXT_PUBLIC_API_URL=http://localhost:5000/api

🧪 Testing (Coming Soon)

Unit testing with Jest + React Testing Library

Integration testing setup planned

📄 License

This project is licensed under the MIT License.

🔗 Related Repositories

Backend: NoteFlow Backend

