# ChatGPT Clone – Frontend

This is the frontend of the **ChatGPT Clone** built using **Next.js 14 (App Router)** and **Tailwind CSS**. It connects to a NestJS backend API to simulate real-time conversations with AI.

## ✨ Features

- Clean chat interface with light UI
- Backend integration for sending/receiving messages
- Auto-scroll chat history
- Responsive design with Tailwind CSS

## 🔗 Live Demo

[https://chatgpt-clone-frontend-alpha.vercel.app/](https://chatgpt-clone-frontend-alpha.vercel.app/)

## 🚀 Backend Repo

Check the backend here: [chatgpt-clone-backend](https://github.com/ZiadGamalDev/chatgpt-clone-backend)

## 🛠️ Technologies Used

- **Next.js 14 (App Router)**
- **TypeScript**
- **Tailwind CSS**
- **OpenAI API (via backend)**

## 📦 Getting Started

1. **Clone the repo**:

```bash
git clone https://github.com/ZiadGamalDev/chatgpt-clone-frontend.git
cd chatgpt-clone-frontend
```

2. **Install dependencies**:

```bash
npm install
```

3. **Set environment variable**:

Create a `.env.local` file and add:

```env
NEXT_PUBLIC_BACKEND_URL=https://your-backend-api.onrender.com
```

4. **Run the app locally**:

```bash
npm run dev
```

Visit: `http://localhost:3000`

## 💡 Project Structure

```
src/
├── app/
│   ├── layout.tsx
│   ├── page.tsx
├── styles/
│   └── globals.css
```

## 🤝 Contribution

This project was built as part of the AI for Technical Track at ITI.

## 📄 License

MIT
