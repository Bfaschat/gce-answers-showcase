# GCE Answers

<p align="center">
  <img src="logo.svg" alt="GCE Answers Logo" width="400">
  <br>
  <strong>The Ultimate Modern Forum for GCE & TVEE Preparation</strong>
</p>

<p align="center">
  A high-fidelity, gamified, and community-driven Q&A platform tailored for students, tutors, and mentors navigating the GCE O/L, A/L, and TVEE curricula.
</p>
<p align="center">
<br>
  <img src="camgceb.svg" alt="Cameroon GCE Board Logo" width="350" style="opacity: 0.8;">
  <br>
  </p>
 
---

## 🚀 Vision
**GCE Answers** is more than just a forum; it's a social learning ecosystem. Inspired by industry leaders like StackOverflow and Reddit, it combines rigorous academic integrity with modern social features, enabling Cameroon's brightest minds to collaborate, solve, and excel.

## ✨ Core Features

### 📝 Advanced Q&A Engine
- **Multi-Format Posts**: Support for text-based questions, image-rich discussions, media galleries, external links, and interactive polls.
- **Academic Precision**: Native integration of **KaTeX** for complex mathematical/chemical formulas and **PrismJS** for code snippets.
- **Structured Discussions**: Deeply nested threading with "Accepted Answer" mechanics to highlight the most helpful contributions.

### 🏆 Gamification & Trust
- **Reputation System**: Earn points through community validation. Unlock advanced platform privileges (editing, flagging, moderation) as you grow.
- **Dynamic Badges**: Over 80+ unique badges across Bronze, Silver, and Gold tiers to reward consistency, expertise, and community service.
- **Verified Tutors**: Dedicated verification workflows for educators and mentors, distinguished by specialized UI badges.

### 🏫 Subject & Syllabus Mastery
- **Scoped Communities**: Discussion areas organized by Exam Level (GCE O/L, A/L, TVEE) and Department (Science, Arts, Technical).
- **Curriculum Integration**: Auto-templated questions based on subject codes and exam levels to ensure high-quality, searchable content.
- **Mastery Tracking**: Integrated syllabus tracking allowing users to visualize their preparation journey.

### 🛡️ Professional Moderation
- **Trust & Safety**: Comprehensive reporting system with severity tagging and resolution tracking.
- **Admin Dashboard**: Real-time analytics, activity heatmaps, and user management tools for community health.
- **Shadow-banning & Enforcement**: Advanced tools for handling spam, harassment, and academic integrity violations.

### 💬 Social & Real-time
- **Messaging Hub**: Direct peer-to-peer conversations with real-time delivery and unread notifications.
- **Presence & Activity**: Live "Most Helpful" leaderboards and presence indicators to foster a vibrant, active community.

---

## 🛠️ Technical Stack

### **Frontend**
- **Next.js 15**: Leveraging App Router, Server Components, and Turbopack for lightning-fast performance.
- **React 19**: Modern UI patterns and robust state management.
- **Tailwind CSS 4**: A high-density, performant design system with native dark mode support.
- **Lucide React**: Clean, consistent iconography.
- **SWR**: Efficient client-side data fetching and revalidation.

### **Backend & Infrastructure**
- **Kysely**: Type-safe SQL query builder for robust database interactions.
- **PostgreSQL**: Reliable relational data storage (Supabase).
- **Upstash Redis**: Real-time rate limiting and caching.
- **Vercel Analytics**: Privacy-focused performance monitoring.
- **Dicebear**: Automated, stylish avatar generation.

---

## 📂 Repository Structure

```text
forum/
├── apps/
│   └── web/            # Next.js Application (Core platform)
├── packages/
│   ├── db/             # Kysely schema, migrations, and seed scripts
│   ├── tsconfig/       # Shared TypeScript configurations
│   └── eslint-config/  # Unified linting rules
├── .husky/             # Git hooks for code quality
└── turbo.json          # Turborepo orchestration
```

---

## 🏁 Getting Started

### 1. Prerequisites
- **Node.js**: >= 24
- **npm**: >= 10
- **Docker**: For local database development

### 2. Installation
```bash
npm install
```

### 3. Database Setup
1. Create a `.env` in `packages/db/`.
2. Run migrations:
```bash
npm run migrate
```

### 4. Local Development
```bash
npm run dev
```

---

## 📄 License
This project is proprietary. All rights reserved by **GCE Answers**.

---
<p align="center">Made with ❤️ for the future of education in Cameroon.</p>
