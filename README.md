# Gamehub - Live Streaming Platform 🎮🚀

Welcome to **Gamehub**, a fully functional live-streaming platform built using **Next.js 14**. Designed to empower streamers and engage viewers, Gamehub provides an immersive experience with advanced features and a modern design.

## 🚀 Live Demo
[Live Demo](https://live-stream-production.up.railway.app/) 

---

## 📌 Features
### Core Functionality:
- 📡 **Streaming** using RTMP/WHIP protocols.
- 🌐 **Ingress generation** for seamless streaming setup.
- 🔗 **OBS integration**: Easily connect your favorite streaming software.

### User Features:
- 🔐 **Google Login**: Simple and secure user authentication.
- 📸 **Thumbnail upload** for personalized streams.
- 👀 **Live viewer count** and 🚦 **live statuses**.
- 💬 **Real-time chat** with unique viewer colors.
- 👥 **Following and blocking system** for better community management.
- 🏋️‍♂️ **Streamer Dashboard**: Manage your streams effectively.
- 🐢 **Slow chat mode** and 🔒 **followers-only chat mode**.
- 🔒 Enable/Disable chat functionality.

### Layouts & Views:
- 🔽 **Collapsible layouts**: Hide sidebars, chat, and enable theater mode.
- 📑 **Sidebar tabs**: Followed channels and recommended streams.
- 🏠 **Home page**: Prioritized live streams and recommendations.
- 🔍 **Search results**: Custom layout for easy discovery.

### Backend & Integration:
- 🔄 Syncing user information and live status to the database using **webhooks**.
- 🗃️ **Database**: PostgreSQL hosted on Neon for scalable and secure data management.

### Performance & Design:
- ⚡ **Blazing fast** and scalable architecture.
- 📝 **SSR (Server-Side Rendering)** for optimized performance.
- 🔬 **Grouped routes** for cleaner code and layouts.

---

## 🛠️ Tech Stack
### Frontend:
- [Next.js 14](https://nextjs.org/) - Modern React Framework
- [Socket.IO](https://socket.io/) - Real-time chat functionality
- [Tailwind CSS](https://tailwindcss.com/) - Responsive and customizable UI

### Backend:
- [Node.js](https://nodejs.org/) - Server-side environment
- [Express.js](https://expressjs.com/) - Backend framework
- [PostgreSQL](https://www.postgresql.org/) - Database for structured data
- [Neon](https://neon.tech/) - Serverless PostgreSQL hosting

### Tools & Integrations:
- **OBS (Open Broadcaster Software)** - Streaming setup
- **RTMP/WHIP Protocols** - Reliable streaming connections
- **Webhooks** - Real-time data syncing
- **Deployment** - Optimized for production

---

## 🖥️ Getting Started

### Prerequisites
- **Node.js**: v18 or higher
- **PostgreSQL**: Set up a database on [Neon](https://neon.tech/)
- **OBS Studio**: For streaming setup

### Installation

#### Create a `.env` file with the following:
```env
NEXT_PUBLIC_API_URL=http://localhost:3000/api
DATABASE_URL=your-database-url
GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_CLIENT_SECRET=your-google-client-secret
RTMP_URL=rtmp://your-server-ip:1935/live
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your-clerk-publishable-key
CLERK_SECRET_KEY=your-clerk-secret-key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
CLERK_WEBHOOK_SECRET=your-clerk-webhook-secret
LIVEKIT_API_URL=your-livekit-api-url
LIVEKIT_API_KEY=your-livekit-api-key
LIVEKIT_API_SECRET=your-livekit-api-secret
NEXT_PUBLIC_LIVEKIT_WS_URL=your-livekit-ws-url
UPLOADTHING_SECRET=your-uploadthing-secret
UPLOADTHING_APP_ID=your-uploadthing-app-id
NEXTAUTH_SECRET=your-nextauth-secret
NEXTAUTH_URL=http://localhost:3000
```

#### Run database migrations:
```bash
npm run migrate
```

#### Start the development server:
```bash
npm run dev
```

#### Open your browser and navigate to:
```arduino
http://localhost:3000
```

---

## 📂 Project Structure
```plaintext
🗁 /actions          # Server-side actions for handling requests
🗁 /app              # Application-level configurations and components
🗁 /components       # Reusable React components
🗁 /hooks            # Custom React hooks
🗁 /lib              # Shared libraries and utilities
🗁 /prisma           # Prisma schema and database configurations
🗁 /public           # Static assets
🗁 /store            # State management and stores
🗁 /styles           # CSS and Tailwind styles
🗁 /utils            # Utility functions
🗁 /api              # Backend API endpoints
🗁 /db               # Database and models
```

---

## 🌈 Screenshots

- **Home page with live stream recommendations.**
  
  ![game-hub-adnab](https://github.com/user-attachments/assets/57fc8848-8408-4f39-afc2-2950dcd36ec3)
- **Streamer dashboard with management tools.**
  
  ![game-hub-adnan](https://github.com/user-attachments/assets/704f0526-ae84-4612-8234-259f3928bfe3)

---
