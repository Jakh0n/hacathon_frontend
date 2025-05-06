# 🌐 SaaS Frontend

This is the **frontend component** of a multi-tenant SaaS admin panel, built with **Next.js** and **React**. It delivers a fully responsive, dynamic dashboard that adapts to each tenant's configuration.

---

## 📋 Overview

✨ Key Features:
- 🎨 **Dynamic Theme Switching** (Light/Dark mode)
- 💬 **Real-Time Chat Module** (toggleable per tenant)
- 📱 **Responsive UI** for both mobile and desktop
- 🔄 **Seamless Tenant Switching** with isolated configs

Live URL 👉 [https://hacathon-frontend-neon.vercel.app](https://hacathon-frontend-neon.vercel.app)

---

## 🚀 Setup Instructions

Clone and run the frontend locally:

```bash
# Navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Create environment variables
echo "NEXT_PUBLIC_API_URL=http://localhost:3001" > .env.local
echo "NEXT_PUBLIC_WEBSOCKET_URL=http://localhost:3001" >> .env.local

# Start the development server
npm run dev
