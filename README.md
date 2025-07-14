# 🥑 Farm-to-Table Hub

A full-stack platform that connects local farmers, campus co-ops, and students through
**web** (React/Node) *and* **mobile** (Flutter) front-ends.  
Users can browse fresh produce, build a cart, and check out seamlessly.

---

## ✨ Features
| Consumer |
|----------|----------------|
| 🔎  Keyword & category search
| 📦 Inventory dashboard |
| 🛒  Persistent cart


---

## 🏗️ Tech Stack
| Layer | Tech |
|-------|------|
| Mobile app | **Flutter** 3.16 • Riverpod • GoRouter |
| Web client | **React 18** • Next.js • Tailwind CSS |
| Server | **Node.js** • Express • REST + WebSocket |
| Database | **MongoDB Atlas** |
| Cloud / DevOps | Docker • GitHub Actions • Render |
| Search & Vector store | Pinecone + LangChain (for product Q&A) |

---

## 🚀 Local Setup

```bash
# 1. clone
git clone https://github.com/tushitam1/farm-to-table-hub.git
cd farm-to-table-hub

# 2. install root dependencies
npm install

# 3. start API (port 5000) & web (port 3000)
npm run dev
