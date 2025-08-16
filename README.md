# Personalized-AI-Learning-System
A clean and simple web-based learning platform that allows users to select subjects, study concise notes, take quick quizzes, and track progress. Includes a contact form for feedback and can connect with an Express backend for saving subjects, test scores, and messages.

🖥️ Steps to Run the Project
1. Install Prerequisites
->Install Node.js (from nodejs.org) → this gives you node & npm.
->Install GitHub Desktop (optional, for uploading to GitHub easily).

2. Open the Project
->Unzip the folder personalized-ai-learning-ui-backend.zip.
->Inside it, you’ll see:
->index.html (frontend entry point)
->subjects.html, learn.html, test.html, contact.html
->assets/ (icons, CSS, JS)
->server.js (backend Express server)

3. Run the Backend (Server)
->Open Command Prompt (cmd) in the project folder.
(Tip: type cmd in the folder path bar and hit Enter).
->Run these commands:
    npm init -y
    npm install express cors body-parser
    node server.js
->You should see:
          Server running on http://localhost:5000

4. Open the Frontend
->Simply double-click index.html → it opens in your browser.
Or right-click → Open with → Chrome/Edge.

5. Use the App
->Landing page → Click Get Started.
->Subjects page → Select subjects (saves in backend & localStorage).
->Learning page → Shows notes + progress.
->Test page → Answer quiz → see score → result stored in backend.
->Contact page → Submit feedback → saved in backend.

6. Check Data
->Open browser → http://localhost:5000/api/data
You’ll see all saved subjects, test results, and contact messages in JSON format.
