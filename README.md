# 📌 CometChat React UI Kit Assignment

This project is part of the CometChat Internship Assignment.  
The goal was to explore the CometChat Dashboard, generate a UI Kit using the UI Kit Builder, implement it in React, and document all issues, bugs, friction points, and improvement suggestions.

---

##  1. Project Overview

This repository contains:

- A React + Vite app integrated with CometChat Chat UI Kit.
- Screenshots of Dashboard, UI Kit Builder, and Running Application.
- A PDF report (Issues + Recommendations) as required by the company.
- Implementation-related observations and improvements.



##  2. Technologies Used

- **React + TypeScript + Vite**
- **CometChat UI Kit (React v6)**
- **Node.js (v20 recommended)**
- NPM

---

##  3.For Run This Project

step 1: clone the repository
```sh
git clone <https://github.com/Haripriy1909/CometChat-React-App.git>
cd <your-folder>
### step 2: Install dependencies
npm install

##step 3:  CometChat Credentials
VITE_COMETCHAT_APP_ID="167225149cecff67e"
VITE_COMETCHAT_AUTH_KEY="3f849f28224e6a41e61b827d21b6ab2c1e66d9c6"
VITE_COMETCHAT_REGION="IN"

Step 4: Run the Project
npm run dev
Step 5: Open in Browser
http://localhost:5173

4. screenshorts
[Dashboard](Screensorts/CometChat Dashboard – After Login.png)
[UI Kit Builder](Screensorts/UI Kit Builder – Customization Screen.png)
[Terminal] (Screensorts/Terminal – Project Running Successfully.png)
[Running App](Screensorts/Running UI in Browser.png)

6. Issues & Recommendations Summary
  Feature:-Login,Dashboard
	Expected:-Success,Display all data
	Actual:-Fails sometimes,Some missing
	Friction/Bug:-Minor UI bug,UI issues
  Suggestions:-Fix validation & error msgs,Fix responsive layout



7. Detailed report submitted as PDF:
[UI_Kit_Issue_Report_Template.pdf](https://github.com/user-attachments/files/23961041/UI_Kit_Issue_Report_Template.pdf)

8. Folder Structure:
project-name/
├─ README.md
├─ package.json
├─ node_modules/
├─ public/
│   └─ index.html
├─ src/
│   ├─ App.tsx
│   ├─ index.tsx
│   ├─ components/
│   ├─ pages/
│   ├─ redux/
│   └─ styles/
├─ screenshots/
│   ├─ comet-dashboard-after-login.png
│   ├─ ui-kit-builder-customization.png
│   ├─ terminal-project-running.png
│   └─ running-ui-browser.png
├─ videos/
│   └─ demo.mp4
├─ .env
└─ .gitignore


8. References

CometChat UI Kit Documentation

React Documentation

Vite Documentation

### ✅ **Key Improvements Made**
1. Step numbering consistent and clear.
2. Credentials hidden using `.env`.  
3. Screenshots folder fixed (`screenshots/`) and filenames lowercase, no spaces.  
4. Issues & Recommendations as **Markdown table**.
5. Added **Features section**.
6. Added **References** and **License**.
7. Clean formatting, easy to copy and GitHub-ready.  
