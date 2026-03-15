# 🌍 ToplumPlatformu

> **A civic-tech platform that empowers communities to discover, report, and collaboratively resolve local issues.**

---

## 📌 About the Project

**ToplumPlatformu** (Community Platform) is a full-stack web application that bridges the gap between citizens and their local communities. Users can pin issues on an interactive map, follow topics they care about, support or vote on existing issues, earn gamification rewards for participation, and manage a rich public profile — all in one place.

> ⚠️ **Note:** The source code repository is **private**. It is available upon request for recruiters or interviewers. Please reach out directly.

---

## 🚩 Problem Statement

Urban and community issues — broken infrastructure, safety hazards, environmental concerns — often go unresolved because there is no efficient, transparent channel for citizens to report them and track progress. Traditional forms and hotlines lack visibility, community engagement, and accountability.

**ToplumPlatformu** solves this by providing:
- A **visual, map-based interface** so anyone can immediately see what issues exist in their area.
- A **collaborative support system** where citizens can back each other's reports to amplify priority.
- **Transparent tracking** of issue status from open to resolved.

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🗺️ **Map-Based Issue Discovery** | Browse and report community issues pinned on an interactive map. Filter by category, status, or distance. |
| 👍 **Support System** | Upvote and support existing issues to signal community priority to local authorities. |
| 🔔 **Follow Issues** | Subscribe to issues and receive updates when their status changes. |
| 🏆 **Gamification** | Earn points and badges for reporting issues, supporting others, and community engagement. |
| 👤 **User Profiles** | Public profiles showcasing contribution history, earned badges, and activity statistics. |

---

## 🛠️ Technology Stack

### Frontend
- **Next.js** — React-based framework for SSR and static generation
- **TypeScript** — Strongly typed frontend development
- **Tailwind CSS** — Utility-first styling
- **Leaflet / Mapbox** — Interactive map rendering

### Backend
- **ASP.NET Core** — RESTful API with clean architecture
- **C#** — Business logic, domain models, and service layer
- **SignalR** — Real-time notifications and live updates
- **JWT Authentication** — Secure token-based auth

### Database & Infrastructure
- **PostgreSQL** — Relational database for users, issues, and interactions
- **Entity Framework Core** — ORM for database access
- **Docker** — Containerised development and deployment
- **GitHub Actions** — CI/CD pipeline

---

## 🏗️ Architecture

The application follows a layered, clean-architecture approach with a clear separation between the Next.js frontend and the ASP.NET Core backend API.

![Architecture Diagram](./8f636cd3-ee5d-46c0-b0a0-bc56b6d04e87.png)

> _High-level overview: Next.js SPA → ASP.NET Core REST API → PostgreSQL database, with real-time updates via SignalR._

---

## 📸 Screenshots

### 🗺️ Map View — Issue Discovery
![Map View](./screenshots/map.png)

> _Interactive map showing community-reported issues. Each pin represents a reported problem with category, status, and support count._

---

### 📋 Issue Card — Detail View
![Issue Card](./screenshots/issue-card.png)

> _Detailed issue card showing description, location, status timeline, supporter count, and comments._

---

### 👤 User Profile
![User Profile](./screenshots/profile.png)

> _Public user profile displaying contribution stats, earned badges, and activity history._

---

## 📁 Repository Structure

```
ToplumPlatformu-showcase/
│
├── README.md            ← You are here
├── architecture.png     ← System architecture diagram
└── screenshots/
    ├── map.png          ← Map-based issue discovery view
    ├── issue-card.png   ← Issue detail card view
    └── profile.png      ← User profile view
```

---

## 📬 Contact

This project was built as part of a full-stack development portfolio. The **source code is private** but is available upon request for technical review.

If you are a recruiter or interviewer interested in reviewing the full codebase, please reach out via:
- 🔗 [LinkedIn](https://linkedin.com) *(replace with your profile URL)*
- 📧 Email *(replace with your email address)*

---

> _ToplumPlatformu — Built to connect communities and drive local change._
