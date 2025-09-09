

<h1 align="center">🤖 AI-Powered Code Reviewer</h1>
<p align="center">Real-time AI feedback on your code using Google Gemini API</p>

![React](https://img.shields.io/badge/Frontend-React-blue)
![Node.js](https://img.shields.io/badge/Backend-Node.js-green)
![Express](https://img.shields.io/badge/Framework-Express-lightgrey)
![Gemini](https://img.shields.io/badge/AI-Gemini-orange)
![Tailwind](https://img.shields.io/badge/Styling-TailwindCSS-blueviolet)
![License](https://img.shields.io/badge/License-MIT-yellow)



An AI-powered code review tool that analyzes your code in real time, identifies errors or bad practices, and suggests corrections with explanations. Built using **Gemini AI**, this tool provides instant feedback to help developers write clean, efficient, and maintainable code.

---

## 🙏 Acknowledgements

This project was created by following the tutorial:

[Build an AI Code Reviewer using Gemini API](https://www.youtube.com/watch?v=J-S-zdfyCDo&t=2640s).


---

## 🚀 Features

- 🖥 **Two-Panel Interface**
  - **Left:** Write or paste your code.
  - **Right:** AI-generated review, including:
    - Error detection
    - Issue explanation
    - Corrected version of your code
    - Suggested improvements

- 🤖 **AI-Powered Analysis**
  - Uses **Google Gemini AI** for natural language feedback and code correction.

- 🔍 **Error Detection & Suggestions**
  - Syntax errors
  - Logical issues
  - Code style improvements
  - Best practice recommendations

- 📜 **Supports Multiple Languages**
  - Python, JavaScript, Java, C++, and more.

---

## 🛠 Tech Stack

- **Frontend:** React / Vite
- **Backend:** Node.js + Express
- **AI Model:** Google Gemini API
- **Styling:** Tailwind CSS
- **Deployment:** Vercel / Render

---

## 📂 Project Structure
BackEnd/
```bash
├── node_modules/
├── src/
├── .env
├── .gitignore
├── package.json
├── package-lock.json
├── server.js
```

FrontEnd/
```bash
├── node_modules/
├── public/
├── src/
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
├── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/itz-anas/AI_Code_Reviewer.git
```

### 2️⃣ Setup Backend
```bash
cd BackEnd/
npm install
```

## Create a .env file in the BackEnd folder:
```bash
GEMINI_API_KEY=your_gemini_api_key_here
PORT=5000
```

### Start backend server:
```bash
npx nodemon (for nodemon user)
```
### 3️⃣ Setup Frontend
```bAH
cd FrontEnd/
npm install
npm run dev
```
## Environment Variables
For BackEnd:
```bash
GEMINI_API_KEY=your_gemini_api_key_here
PORT=5000
```
## 🖥 Usage

Open the frontend in your browser.
Paste or type your code in the left panel.
Click Review.
View AI-generated feedback, corrected code, and improvement tips in the right panel.

## 📸 Interface Preview
Left Panel (Code Input)	Right Panel (AI Review)
Write/Paste your code	See errors & fixes

## 📬 Connect with Me  

<p align="left">
  <a href="https://www.linkedin.com/in/mohammedanas16/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin" />
  </a>
  <a href="https://github.com/itz-anas" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github" />
  </a>
  <a href="mailto:infodeveloper.mail@gmail.com">
    <img src="https://img.shields.io/badge/Email-red?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
 
</p>
