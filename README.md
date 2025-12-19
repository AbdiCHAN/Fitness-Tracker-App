🏋️ Fit Force – Fitness Tracker App
<p align="center"> <img src="images/fitforce-logo.png" alt="Fit Force Logo" width="180"> </p>
📌 Project Overview

Fit Force is a web-based Fitness Tracker App that allows users to log workouts, track progress, and view workout history.
The project focuses on real-world frontend development using clean JavaScript logic and browser storage.

👥 Team

Team Name: 🏋️ Fit Force
Project Manager: Abdirahman

Members & GitHub Usernames:

Abdulhadi – abdulhadishueb

Andy Kimathi – andymkk

Abdullahi – abzulo

Abdirahman – AbdiCHAN

🎯 Features

Log workouts (exercise name, duration, reps)

View workout history

Track progress visually

Persist data using LocalStorage

Optional backend support

🗂️ Folder Structure
fit-force/
│
├── images/                # App images (logo, icons, illustrations)
│   └── fitforce-logo.png
│
├── styles/                # CSS files for styling the app
│   └── main.css           # Main stylesheet
│
├── src/
│   ├── js/                # JavaScript logic
│   │   ├── app.js         # Main app initialization
│   │   ├── storage.js     # LocalStorage handling
│   │   ├── ui.js          # UI rendering and updates
│   │   └── utils.js       # Utility functions
│   │
│   ├── components/        # Reusable components
│   │   ├── workoutCard.js # Workout display component
│   │   ├── progressChart.js # Progress chart component
│   │   └── modal.js       # Modal component
│   │
│   └── backend/           # Optional backend integration
│       └── api.js         # API interaction functions
│
├── index.html             # Landing page
├── README.md              # Project documentation
├── package.json           # Node.js configuration (if applicable)
└── .gitignore             # Files/folders to ignore in Git

📌 Folder Explanation

images/ – Stores all app-related images, including logos and icons.

styles/ – Contains CSS files for styling your app.

src/js/ – Core JavaScript files handling app logic, UI updates, and utilities.

src/components/ – Reusable UI components for workouts, charts, and modals.

src/backend/ – Optional scripts for backend API integration.

index.html – Main entry point for the app.

package.json – Project configuration if Node.js or build tools are used.

🚀 Getting Started

Clone the repository

git clone https://github.com/AbdiCHAN/Fitness-Tracker-App.git
cd Fitness-Tracker-App


Open the app

Simply open index.html in your browser for basic usage.

Optional: Install dependencies (if using Node.js backend or build tools)

npm install
npm start

⚡ Usage

Add your workouts via the input form.

Track your progress visually with charts.

View all past workouts in the history section.

Data is automatically saved to LocalStorage for persistence.