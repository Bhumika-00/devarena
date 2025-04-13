# 🚀 DevArena

**Real-Time Multiplayer Coding Platform with Live Code Translation**

---

## 📖 Overview

DevArena is an innovative real-time, multiplayer coding challenge platform that enhances multilingual learning by allowing users to:

- Write code in one language (e.g., Java)
- View translated equivalent in another (e.g., Rust) instantly 💡
- Compete in live challenges with a real-time leaderboard 🏆
- Experience lightweight performance with **zero raw code storage**

---

## ✨ Key Features

- 🔄 **Live Code Translation** (e.g., Java ➡️ Rust)
- 💬 Compare OOP vs Systems-level paradigms
- 🔒 **No source code is stored**, only metadata (status, timestamps, language, score)
- 📊 **Real-time leaderboard** and streak tracking
- ⚡ **Lightweight and type-safe validation**

---

## 🛠 Tech Stack

### 🧩 Frontend
- `Next.js` – SSR & routing  
- `TypeScript` – Type-safe logic  
- `Tailwind CSS` – Utility-first responsive design  
- `Zustand` – Minimal state management  
- `ShadCN UI` – Customizable UI components  

### 🌐 Backend / Tools
- `Convex` – Serverless DB & function management  
- `Convex Functions` – Code execution metadata, validation logic  
- `Clerk` – Authentication  
- `Vercel` – Hosting & deployment  
- `Loca.lt / Ngrok` – Tunneling for local development  

---

## 📦 Getting Started

### ✅ Prerequisites

Make sure you have the following installed:

- `Node.js` (v16 or later)
- `Git`
- `pnpm` or `npm`

---

### 🔄 Clone the Repository

```bash
git clone https://github.com/your-username/DevArena.git
cd DevArena
```

---

### 📥 Install Dependencies

Using `pnpm`:

```bash
pnpm install
```

Or using `npm`:

```bash
npm install
```

---

### 🚀 Run the Development Server

```bash
pnpm dev
```

Then open your browser and navigate to:

```
http://localhost:3000
```

---

### 🌐 Deployment

App is hosted via **Vercel**  
Tunnel your local server with:

```bash
npx localtunnel --port 3000
# OR
npx ngrok http 3000
```

---

## 📣 Roadmap

- [ ] Add more language pairs
- [ ] Mobile-friendly UI
- [ ] Team-based multiplayer challenges
- [ ] Community challenge creation

---

## 🧑‍💼 Author

📌 Prepared by: **Bhumika Sharma**  


---

## 📄 License

MIT License. Feel free to use and contribute!

---

Made with ❤️ by **Bhumika Sharma**




