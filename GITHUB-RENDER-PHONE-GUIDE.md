# Phone-only GitHub + Render deployment

## 1. Create a GitHub repository
Create a new GitHub repository named `texas-holdem-friends`.
Do not add a README or .gitignore during repository creation.

## 2. Upload this project
Upload all files and folders in this package while preserving the structure:
- package.json
- server.js
- render.yaml
- .gitignore
- README.md
- public/index.html
- public/app.js
- public/style.css

Do NOT upload `node_modules`.

## 3. Deploy on Render
Create a Render Web Service from the GitHub repository.
Build command: `npm install`
Start command: `npm start`
Plan: Free

The app listens on Render's PORT environment variable automatically.

## 4. Share
After deployment, open the Render URL, create a room, then use Share Room to send the game link to friends.

This app uses virtual chips only and has no real-money wagering.
