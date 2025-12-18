# Rated: Production Guild (RPG) Management System

![RPG Logo](./res/assets/logo/rpg-logo.png) 
*The unified operating system for the Rated: Production Guild talent community.*

## 📌 Project Overview
The **Rated: Production Guild (RPG) App** is a mobile-first, all-in-one solution designed to streamline the operations of our talent school organization. It integrates attendance tracking, point-of-sale (POS) commerce, and financial management into a single platform tailored for the creative arts.

### 🏛 Institutional Affiliation
- **University:** Saint Louis University (SLU)
- **School:** School of Accountancy, Management, Computing, and Information Studies (SAMCIS)

---

## 🎭 Core Modules
- **Attendance & Talent Tracking:** QR-based check-ins for rehearsals, workshops, and production meetings with real-time occupancy tracking.
- **Guild Store (POS):** A secure mobile terminal for ticket sales, organization merchandise, and workshop fees.
- **Production Finance:** Centralized ledger for tracking income from the POS and production-related expenses.
- **Event Management:** Dynamic event feed with role-based visibility for internal and public activities.

---

## 👥 User Roles & Permissions
The system utilizes **Role-Based Access Control (RBAC)** to ensure data security and operational focus:

| Role | Responsibility | Key Features |
| :--- | :--- | :--- |
| **Admin** | Exec Committee | Full system control, role management, and global audit. |
| **Finance** | Finance Committee | Access to POS Terminal and Profit/Loss reports. |
| **Public Relations** | PR & Marketing | Creation of public events and organization-wide announcements. |
| **Productions** | Guild Heads | Internal event posting (rehearsals) and QR attendance scanning. |
| **Users** | Members | Digital QR ID, event registration, and personal attendance logs. |

---

## 🛠 Tech Stack
- **Frontend:** [Flutter](https://flutter.dev/) (Mobile-First)
- **Backend:** [Supabase](https://supabase.com/) (PostgreSQL Database, Auth, and Storage)
- **Database Security:** Row Level Security (RLS) for financial data protection.
- **Infrastructure:** GitHub (Version Control & Documentation)

---

## 🎨 Design System
The application follows a **Dark Mode / Stage Aesthetic** to reflect the production environment of the guild.
- **Primary Color:** RPG Red (`#A50207`)
- **Accent Color:** SAMCIS Gold (`#F2D024`)
- **Background:** Deep Stage Black (`#121212`)

---

## 📂 Documentation Guide
For more detailed information, please refer to the files in the `/docs` folder:
1. `docs/user_roles.md` - Deep dive into permissions.
2. `docs/data_architecture.md` - Database schema and ERD.
3. `docs/user_stories.md` - Detailed workflows for all roles.
4. `docs/ui_ux_guidelines.md` - Mobile design and component rules.

---

## 🚀 Getting Started
*(Instructions for developers to clone and run the app will be added here once development begins.)*
