# KareAI Assignment - Perplexica Frontend

This is the completed frontend assignment for KareAI, featuring a fully functional, responsive web app built using **Next.js 15 (App Router)**. It includes widgets for weather, news, AI-based chat with PDF upload functionality, and clean UI components using TailwindCSS and Shadcn.

---

## 🚀 Tech Stack

- **Framework:** Next.js 15 (App Router)
- **Styling:** TailwindCSS, Shadcn/UI
- **ORM:** Drizzle (SQLite/Postgres support)
- **PDF Parsing:** `pdf-parse`
- **Build Output:** Standalone mode (`output: 'standalone'`)
- **Server Functions:** API routes via Next.js
- **Deployment Ready:** `node .next/standalone/server.js`

---

## 🔧 Getting Started

### Clone & Setup

```bash
git clone https://github.com/PraveenAntenor/Perplexica-KareAI-Assignment.git
cd Perplexica
npm install
npm run db:push
npm run build
node .next/standalone/server.js

---

## 📦 Features Implemented

- ✅ Responsive UI with modular components
- ✅ Weather widget using OpenWeatherMap API
- ✅ News widget with live headlines
- ✅ AI-powered PDF chat functionality
- ✅ Memory-based threaded chat interface
- ✅ Clean architecture and folder structure
- ✅ Standalone build for easy deployment

---




## 📁 Project Structure (Highlights)
/app
└── chat/
└── dashboard/
└── layout.tsx
/components
└── ui/
└── widgets/
/lib
└── utils.ts
└── pdf.ts
/public
/styles
.env.example







