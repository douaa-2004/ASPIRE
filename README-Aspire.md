# Aspire — SaaS Platform for Managing and Delivering Private Training Courses

![React](https://img.shields.io/badge/Frontend-React%20%2F%20Redux-61dafb.svg?style=flat&logo=react)
![Node.js](https://img.shields.io/badge/Backend-Node.js%20%2F%20Express-339933.svg?style=flat&logo=node.js)
![SaaS](https://img.shields.io/badge/Model-SaaS-blue.svg)
![AI](https://img.shields.io/badge/AI-Powered-orange.svg)

---

## Project Description

Aspire is a web and mobile SaaS platform designed to modernize and personalize the learning experience across North Africa. Built as a true self-learning hub, it combines the features of an educational ERP, an intelligent LMS, and an AI-powered virtual assistant, allowing learners, instructors and institutions to collaborate efficiently within a unified digital ecosystem.

The platform connects three main categories of users:

- Private institutions and schools — complete pedagogical, financial and administrative management tools to digitize their operations
- Independent or affiliated instructors — create their own virtual schools, publish and monetize courses, host interactive quizzes, and track learners individually
- Learners — access interactive online learning paths, join learning communities, track their progress in real time and benefit from intelligent support via a contextual AI

---

## Academic Context

| Field | Detail |
|---|---|
| Author | Bourezg Douaa |
| Institution | Oran 1 University — Faculty of Exact and Applied Sciences |
| Specialization | Information Security |
| Academic Year | 2024/2025 |

---

## Main Features

### Admin / Institution Interface

- Centralized management of announcements
- Course management with publication status, ratings and revenue overview
- Financial management: invoices, expenses, profit overview
- Messaging panel for communication with teachers and parents
- Reports and analytics: enrollment, academic performance, attendance, financial summary
- Schedule management with weekly calendar view
- School portal: public profile and photo gallery

### Teacher Interface

- Assignment management with status tracking (pending, in progress, completed, overdue)
- Quiz creation
- Course content editor with lesson management
- Course overview with student count, revenue and completion rate

### Student Interface

- Personalized dashboard with enrolled courses, attendance rate and average grade
- Assignment tracking with due dates and scores
- Interactive course player with progress tracking
- Per-course progress overview (grades, completed assignments, credits)
- Contextual AI study assistant (explain concepts, solve problems, summarize, study tips)

### Mobile Application

- Onboarding and account verification
- Registration as Student, Teacher or Admin
- Sign in / Sign up with role selection

---

## Innovation Highlights

- Contextual AI chat assisting learners in real time with their learning difficulties
- Automated progress tracking with personalized recommendations based on each user's profile and pace
- Independent virtual schools powered by a SaaS model, letting instructors manage their own courses and students
- Real-time pedagogical and financial analytics to support decision-making
- Optimized mobile application with offline access and gamification elements

---

## Tech Stack

### Frontend

| Technology | Usage |
|---|---|
| React.js | User interface, reusable components |
| React Router | Navigation between pages |
| Redux | Global state management |
| Recharts / Chart.js | Dashboards and analytics visualizations |

### Backend

| Technology | Usage |
|---|---|
| Node.js | Server-side JavaScript runtime |
| Express.js | REST API framework, routes and middlewares |
| AI APIs (NLP) | Quiz generation, contextual AI assistant, learning path analysis |

### Infrastructure

| Technology | Usage |
|---|---|
| AWS / OVH | Secure cloud hosting |
| DBaaS | Managed database for scalability |
| Encrypted storage | Confidential data and document storage |

---

## Project Structure

```
aspire-platform/
├── frontend/
│   └── src/
│       ├── components/
│       │   ├── admin/          # announcements, course-management, financial-management...
│       │   ├── teacher/        # assignments, course-content-editor, my-courses
│       │   └── student/        # dashboard, assignments, course-learning, ai-chat
│       └── redux/              # store.js, userSlice.js
├── backend/
│   ├── controllers/            # Business logic per resource
│   ├── routes/                 # Express REST API endpoints
│   ├── ai/                     # AI assistant and quiz generation services
│   └── server.js               # Server entry point
├── mobile/                      # React Native / mobile application
└── README.md
```

---

## Installation and Setup

### Backend

```bash
git clone https://github.com/your-username/aspire-platform.git
cd aspire-platform/backend
npm install
```

Create a `.env` file:

```
DB_HOST=localhost
DB_PORT=5432
DB_USER=your_user
DB_PASSWORD=your_password
DB_NAME=aspire_db
AI_API_KEY=your_ai_api_key
```

```bash
node server.js
```

### Frontend

```bash
cd ../frontend
npm install
npm start
```

The application will be available at `http://localhost:3000`.

### Mobile

```bash
cd ../mobile
npm install
npm run start
```

---

## Project Status

The platform is currently about 70 percent complete. Core web and mobile features (account management, personalized dashboard, learning and progress-tracking modules) are already implemented. A beta phase has been run with a panel of 1,000 learners to validate usability and functional relevance.

Remaining work focuses on:

- Performance optimization and data security to meet modern SaaS standards
- Integration of third-party services (online payments, digital certificates, partner ad spaces)
- UX/UI improvements based on beta tester feedback

Roadmap: prototype finalization (2025) — fundraising phase (early 2026) — official market launch (mid-2026)

---

## Business Model

Hybrid educational SaaS combining B2C, B2B2C and B2B revenue streams:

- Students: free app access, pay-per-course or course bundles
- Teachers: freemium model (free with limited course creation / Pro subscription for unlimited courses, certification and analytics tools)
- Private schools: paid subscription or license to create their virtual space, manage students and issue official certifications

---

## Future Improvements

### Short term

- Online payment integration
- Digital certificate generation and verification
- UX/UI refinements based on beta feedback

### Long term

- Advanced AI-driven adaptive learning paths
- Hackathons and skill challenges with universities and incubators
- Regional expansion across North Africa and French-speaking Africa
- Recognition and reward program for top-performing instructors

---

Copyright 2025 — Bourezg Douaa — Oran 1 University
