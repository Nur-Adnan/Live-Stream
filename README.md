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
DATABASE_URL=your-neon-database-url
GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_CLIENT_SECRET=your-google-client-secret
RTMP_URL=rtmp://your-server-ip:1935/live
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
🗁 /components       # Reusable React components
🗁 /pages            # Next.js pages and routes
🗁 /public           # Static assets
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

## 📈 Roadmap
- Add mobile responsiveness.
- Implement advanced analytics for streamers.
- Support for multiple streaming platforms.
- AI-based stream recommendations.

---

## 🕌 Contributing
Contributions are welcome! Feel free to fork this repo and submit a pull request. For major changes, please open an issue first to discuss your ideas.

---

## 💃 License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## 💬 Contact
For questions or feedback, reach out via GitHub or connect with me on:

- **GitHub**
- **LinkedIn**

---

## 🌟 Acknowledgments
Special thanks to the open-source community for the tools and inspiration to build this project.
