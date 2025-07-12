<h1 align="center">🔁 Skill Swap</h1>
<p align="center">
  <em>A real-time platform where knowledge becomes currency.</em><br/>
  <strong>Offer what you know. Learn what you love.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Built%20For-Hackathon-blueviolet?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Stack-Full%20Stack-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge" />
</p>

---

## 🌐 Live Preview

🔗 [**Live Site**](#)  
🎥 [**Demo Video**](#)

---

## 🧠 What is Skill Swap?

**Skill Swap** is a collaborative learning platform that lets users exchange skills with one another — no money involved. Whether you're a coder wanting to learn piano or a photographer willing to trade portrait sessions for design lessons — this is your space.

> "Because everyone has something to teach — and something to learn."

---

## ✨ Core Features

<table>
<tr><td>🔐 <strong>Authentication</strong></td><td>Secure login using Replit Auth</td></tr>
<tr><td>👤 <strong>User Profiles</strong></td><td>Customizable bios, skill tags, profile images, availability toggle</td></tr>
<tr><td>📚 <strong>Skill Management</strong></td><td>Add, edit, or delete your offered and requested skills</td></tr>
<tr><td>🔍 <strong>Advanced Search</strong></td><td>Filter users by skill, availability, tags</td></tr>
<tr><td>🔁 <strong>Swap System</strong></td><td>Send, accept, reject, or cancel swap requests with real-time updates</td></tr>
<tr><td>⭐ <strong>Feedback & Ratings</strong></td><td>Post-swap feedback builds trust within the community</td></tr>
<tr><td>🔔 <strong>Notifications</strong></td><td>Real-time alerts via WebSockets (Socket.io)</td></tr>
<tr><td>📊 <strong>Admin Dashboard</strong></td><td>Track usage analytics, moderate users, export reports</td></tr>
<tr><td>📱 <strong>Responsive UI</strong></td><td>Clean, mobile-friendly layout powered by Tailwind CSS</td></tr>
</table>

---

## ⚒️ Tech Stack

| Layer        | Tech Used                          |
|--------------|-------------------------------------|
| **Frontend** | React.js, Tailwind CSS              |
| **Backend**  | Node.js, Express.js                 |
| **Database** | PostgreSQL (via Prisma / Knex)      |
| **Auth**     | Replit Auth / JWT                   |
| **Real-Time**| WebSockets (Socket.io)              |
| **Deploy**   | Vercel (Frontend), Render (Backend) |

---

## 🛠 Improvements Implemented

- ✅ Fixed all **TypeScript errors** for smooth compilation
- ⭐ Integrated **Rating System** with post-swap feedback
- 🔍 Improved **Filtering & Skill Tag Search**
- 🖼 Enabled **Profile Picture Upload**
- 🔁 Fully functional **Swap Request Flow**
- 🔔 Finished **WebSocket Notifications**
- 📊 Added **Admin Analytics** dashboard

---

## 📁 Project Structure

skill-swap/
├── client/ # React frontend

│ ├── components/ # Reusable UI components

│ └── pages/ # Routes and views

├── server/ # Express backend

│ ├── routes/ # API routes

│ └── controllers/ # Logic & database interaction

├── db/ # PostgreSQL schema & seed files

└── public/ # Static assets


---

## 🚀 Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/skill-swap.git
cd skill-swap

# Install dependencies
cd server && npm install
cd ../client && npm install

# Start backend and frontend
cd ../server && npm run dev
cd ../client && npm start
