# 🌱 Eco-Action Tracker

Track your eco-friendly activities like recycling, sustainable commuting, and energy savings. Visualize your impact, earn rewards, and join a gamified community working toward a greener planet.

---

## 🚀 Tech Stack

- **Frontend**: Html, Css, JavaScript
- **Backend**: Express.js, Node
- **Database**: MongoDB
- **Visualization**: Chart.js / Recharts
- **Gamification**: XP, Badges

---

## 🎯 Key Features

- User Authentication (Login, Sign Up, JWT)
- Log Eco-Friendly Actions (e.g., biking, recycling)
- Personal Dashboard (impact graphs, progress)
- Gamification (XP, badges, streaks)
- Community Page (leaderboard)

---

## 👥 Team & Work Distribution

### 🖼️ Frontend – *Janvi & Devansh*

- Landing Page (Home)
- Authentication (Login / Signup / Forgot Password)
- Dashboard Layout (Sidebar, Header)
- UI Components (Buttons, Modals, Forms)
- Log Action Form UI
- Mobile Responsiveness & Styling

- User Dashboard Sections:
  - Profile Card (Avatar, XP, Level)
  - Personal Impact Charts
  - Gamification Panel (XP bar, badges)
- Community Page UI:
  - Leaderboard
  - Join Challenges
- Rewards & Badges UI

---

### 🔧 Backend – *Vidhan & Jitendra*

- Project Setup (monorepo / folder structure)
- GitHub Actions / Linting / Deployment Setup
- API Integration (frontend ↔ backend)
- User Authentication Flow (frontend & backend)
- "Log New Action" full feature
- MongoDB Models (User, Action, Badge)
- Deployment (Render / Vercel / MongoDB Atlas)

- REST API with Express.js:
  - Auth Routes: `POST /auth/signup`, `POST /auth/login`
  - Action Logging: `POST /actions/log`
  - Fetch Data: `GET /user/:id/impact`, `/leaderboard`, `/badges`
- MongoDB Schema Design:
  - User, ActionLog, Badge, Challenge
- Gamification Logic:
  - XP & badge assignment based on actions
- Community Stats:
  - Total CO2 saved, top users, streaks
- JWT Auth Middleware


---

## 📌 Future Enhancements

- Admin Panel for managing actions/challenges
- Tree-planting rewards with real-world impact
- AI-based suggestions for sustainable actions
- PWA / Mobile App version

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

