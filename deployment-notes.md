# Deployment Notes – Fit Force App

## GitHub Pages
- The live app will be deployed using GitHub Pages.
- Ensure you are on the main branch before deploying:
  git checkout main
  git pull origin main
- Push any changes and the app will be live.

## Running Locally
- Clone the repo:
  git clone https://github.com/AbdiCHAN/Fitness-Tracker-App.git
- Navigate to project folder:
  cd Fitness-Tracker-App
- Open index.html in a browser to test frontend.
- For backend (optional):
  cd backend
  npm install
  node server.js

## Updating the App
- Always pull latest changes before working:
  git pull origin main
- Commit your changes:
  git add .
  git commit -m "Describe your changes"
  git push origin main --force