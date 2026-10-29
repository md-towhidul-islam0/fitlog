<<<<<<< HEAD
# FitLog
A dark-mode, no-nonsense workout tracking app to log exercises, customize routines, and monitor fitness progress.

---

## Table of Contents

- [About the Project](#about-the-project)
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Dependencies](#dependencies)
- [Installation & Setup](#installation--setup)
- [Folder Structure](#folder-structure)
- [Contributions](#contributions)
- [How to Contribute](#how-to-contribute)
- [License](#license)
- [Contact](#contact)

---
=======
# 🏋️ FitLog — Personal Workout Planner

A modern, responsive, and minimalist workout planning application built with **Next.js, React, TypeScript, and Tailwind CSS**. FitLog helps users explore exercises, create daily workout plans, save favorite workouts, and track estimated workout statistics through a clean dark-themed interface.

<p align="center">
  <a href="https://fitlog-git-main-null-a884.vercel.app/">
    <strong>🌐 Live Demo</strong>
  </a>
  &nbsp; • &nbsp;
  <a href="https://github.com/towhidislam3489/fitlog">
    <strong>💻 GitHub Repository</strong>
  </a>
</p>

---

## 📸 Screenshots

Explore the FitLog interface and its key pages.

<!-- Add your actual screenshots to the public/screenshots/ directory. -->

### 🏠 Home & Workout Library

![FitLog Home Page](/public/screenshot/home.png)

### 💪 Workout Details

![FitLog Workout Details](/public/screenshot/workout-details.png)

### 📋 My Plan

![FitLog My Plan](/public/screenshot/my-plan.png)

> **Note:** Replace these example screenshot paths with your actual screenshots. If a screenshot is not available yet, add it after capturing the corresponding page.

---

## 📖 Project Overview

FitLog is designed for people who want a simple and organized way to plan their workouts. Rather than overwhelming users with complicated fitness dashboards, it focuses on workout discovery, daily planning, saved exercises, and essential fitness statistics.

**Project goals:**
- Make workout selection simple and convenient.
- Help users organize their daily exercise routines.
- Provide quick access to saved workouts and planned exercises.
- Deliver a consistent experience across desktop, tablet, and mobile devices.
>>>>>>> 83562dd (updatereadme)

## About the Project  
FitLog is designed for individuals who want a clean, minimalist, and dark-themed gym companion. Instead of overly complex fitness trackers, FitLog provides a direct experience: pick your lifts, lock them into your daily plan, track estimated workout durations and calorie burn, and log your overall progress.

<<<<<<< HEAD
---

## Project Overview  



- **Goal:** Simplify workout selection and day-to-day plan creation with zero distraction.
- **Library Coverage:** 12 primary exercises targeting 7 major muscle groups (Chest, Back, Legs, Shoulders, Arms, Core, Full Body).
- **Core Metrics:** Duration (minutes), Calorie Burn (kcal), Difficulty/User Ratings, and Saved Workouts Counter.

---

## Key Features  
- **Comprehensive Workout Library** — Browse detailed cards for major lifts (Bench Press, Deadlift, Squat, Kettlebell Swings, etc.) filtered by muscle groups and targeted equipment.
- **Interactive Plan Builder** — Select lifts and add them directly into your daily workout schedule ("My Plan").
- **Workout Counter & Saved List** — Quick navbar counters for tracking active plans and saved exercises.
- **Dark-Theme Responsive UI** — Focused visual presentation optimized for easy viewing while working out.

---

## Tech Stack  
**Frontend:** Next.js · React · Tailwind CSS · TypeScript  
**Hosting/Deployment:** Vercel  
**Tools:** Git · VS Code  

---

## Dependencies  
Example dependencies extracted from the web application stack:

```json
{
  "next": "^14.x",
  "react": "^18.x",
  "react-dom": "^18.x",
  "lucide-react": "^0.x"
}
=======
- **Workout Library:** Browse 12 primary exercises, including Bench Press, Deadlift, Squat, and Kettlebell Swings.
- **Muscle Group Filtering:** Explore exercises across seven muscle groups: Chest, Back, Legs, Shoulders, Arms, Core, and Full Body.
- **Interactive Plan Builder:** Add selected exercises to your personal daily workout plan.
- **My Plan:** View and manage your selected workout activities.
- **Saved Workouts:** Save favorite exercises for convenient access.
- **Workout Statistics:** Explore estimated workout duration, calorie burn, difficulty levels, and user ratings.
- **Dynamic Navigation Counters:** View workout plan and saved exercise counts.
- **Responsive Interface:** Optimized layouts for different screen sizes.
- **Modern Dark Theme:** Enjoy a clean interface designed for a focused fitness experience.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Next.js 16 | React framework and App Router |
| React 19 | Interactive user interfaces |
| TypeScript 5 | Type-safe development |
| Tailwind CSS 4 | Styling and responsive layouts |
| DaisyUI 5 | Prebuilt UI components |
| Lucide React | Icons |
| React Toastify | Toast notifications |
| ESLint 9 | Code quality and linting |
| Vercel | Deployment and hosting |
| Git & GitHub | Version control |

## 📦 Dependencies

### Production Dependencies

| Package | Version |
|---|---|
| `next` | `16.3.6` |
| `react` | `19.2.8` |
| `react-dom` | `19.2.8` |
| `lucide-react` | `^1.48.0` |
| `react-toastify` | `^11.1.0` |

### Development Dependencies

| Package | Version |
|---|---|
| `typescript` | `^5` |
| `tailwindcss` | `^4` |
| `@tailwindcss/postcss` | `^4` |
| `daisyui` | `^5.7.46` |
| `eslint` | `^9` |
| `eslint-config-next` | `16.3.6` |
| `@types/node` | `^20` |
| `@types/react` | `^19` |
| `@types/react-dom` | `^19` |

## ⚙️ Getting Started

Follow these instructions to run FitLog locally.

### Prerequisites

Make sure you have installed:

- [Node.js](https://nodejs.org/)
- npm
- [Git](https://git-scm.com/)
- A code editor such as [Visual Studio Code](https://code.visualstudio.com/)

### 1. Clone the Repository

```bash
git clone https://github.com/towhidislam3489/fitlog.git
```

### 2. Navigate to the Project Directory

```bash
cd fitlog
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Development Server

```bash
npm run dev
```

### 5. Open in Your Browser

Visit:

```text
http://localhost:3000
```

The FitLog application should now be available on your local machine.

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the development server |
| `npm run build` | Create a production build |
| `npm run start` | Run the production server after building |
| `npm run lint` | Check code quality with ESLint |

## 📁 Project Structure

```text
fitlog/
├── public/
│   └── screenshots/       # Project screenshots
├── src/
│   ├── app/
│   │   ├── [id]/          # Dynamic route
│   │   ├── myplan/        # Workout plan page
│   │   ├── workouts/      # Workout library
│   │   ├── layout.tsx     # Root layout
│   │   ├── page.tsx       # Home page
│   │   └── globals.css    # Global styles
│   ├── assets/            # Static assets
│   ├── buttoncomponent/   # Button components
│   ├── component/         # Reusable components
│   ├── context/           # Context API and state
│   └── type/              # TypeScript types
├── package.json
├── package-lock.json
├── next.config.ts
└── README.md
```

*The directory structure is based on the available project information. Update it if your actual repository contains additional files or folders.*

## 🚀 Deployment

FitLog is deployed on Vercel.

- **Live Application:** https://fitlog-git-main-null-a884.vercel.app/
- **GitHub Repository:** https://github.com/towhidislam3489/fitlog

To deploy your own version, import the GitHub repository into [Vercel](https://vercel.com/) and follow the deployment instructions.

## 🔮 Future Improvements

- Add workout completion tracking.
- Introduce weekly and monthly fitness progress reports.
- Add interactive progress charts.
- Provide personalized workout recommendations.
- Improve workout history and data persistence.

## 👨‍💻 Author

**Towhid Islam**

- GitHub: [@towhidislam3489](https://github.com/towhidislam3489)
- LinkedIn: [Towhid Islam](https://www.linkedin.com/in/towhidislam77/)

---

If you find this project useful, consider giving the repository a ⭐ **star**!

**Built with ❤️ using Next.js, React, TypeScript, and Tailwind CSS.**
>>>>>>> 83562dd (updatereadme)
