# 2023-27_Sushant-Singh_CS-2341737_7TH_4CSE10

## Web Developer Internship at Beast Learners

This repository contains the internship documents and project report completed during my three-month internship as a **Web Developer Intern at Beast Learners**.

### Student Details

- **Name:** Sushant Singh
- **Roll Number:** CS-2341737
- **Program:** B.Tech Computer Science and Engineering
- **Section:** 4CSE10
- **Batch:** 2023–27
- **University:** IILM University, Greater Noida, U.P.

---

## Internship Details

- **Organization:** Beast Learners
- **Role:** Web Developer Intern
- **Internship Duration:** 1 June 2026 – 1 September 2026
- **Project:** BEAST OS
- **Project Type:** Cross-Platform EdTech Operating System

---

## About the Project

**BEAST OS** is an EdTech platform developed by Beast Learners for ICSE-level board exam preparation.

The platform combines student learning features, AI-assisted tutoring, quizzes, syllabus tracking, subscription management, and administrative analytics into a connected web application.

During the internship, my primary contribution focused on the frontend development and enhancement of the following modules:

- Student Home Dashboard
- AI Tutor Interface
- Subscription Store
- Admin BI Analytics Dashboard

---

## My Contributions

### 1. Student Home Dashboard

Developed the student-facing Home Dashboard containing:

- Personalized welcome section
- Daily Challenge banner
- Study Streak widget
- Quick navigation cards
- Syllabus Progress section
- Empty-state handling

### 2. AI Tutor Interface

Worked on the frontend interface of the Beast AI Tutor, including:

- AI Tutor header
- Welcome message
- Credit balance display
- Message input interface
- Empty conversation state

### 3. Subscription Store

Developed the subscription interface with:

- Monthly and yearly plans
- Feature comparison
- Pricing information
- Savings badge
- Upgrade actions
- Reusable plan-card components

### 4. Admin BI Analytics Dashboard

Contributed to the internal analytics dashboard with:

- Active Subscribers statistic
- Credits Burned statistic
- Daily Active Users statistic
- Daily Active Credits line chart
- Subscription Plan Distribution bar chart
- Live REST API data integration

---

## Technology Stack

| Technology / Tool | Purpose |
|---|---|
| React.js | Frontend development |
| Tailwind CSS | Responsive UI styling |
| Recharts | Data visualization |
| React Hooks | State and data handling |
| REST APIs | Live data integration |
| Supabase | Backend/data source consumed by frontend |
| PostgreSQL | Database used by the backend |
| Razorpay API | Subscription/payment integration |
| Lucide Icons | UI icons |

---

## System Architecture

BEAST OS follows a decoupled architecture where the React.js frontend communicates with backend services through REST APIs.

```text
                 ┌─────────────────────┐
                 │       Student       │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │   React.js Frontend │
                 │    + Tailwind CSS   │
                 └──────────┬──────────┘
                            │
                     REST API Calls
                            │
                            ▼
                 ┌─────────────────────┐
                 │   Backend Services  │
                 │      Supabase       │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ PostgreSQL Database │
                 └─────────────────────┘

          ┌──────────────────────────────────┐
          │       Admin BI Dashboard         │
          │     Recharts Data Visualisation  │
          └──────────────────────────────────┘
