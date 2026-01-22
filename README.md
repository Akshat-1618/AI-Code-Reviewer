# 🤖 AI Code Reviewer

An AI-powered web application that reviews your code like a senior software engineer.  
Built using the MERN stack and powered by Google Gemini AI, this tool helps developers improve code quality, performance, security, and maintainability.

---

## 🌐 Live Demo

🔗 **Live URL:**  
👉 https://ai-code-reviewer-one-hazel.vercel.app/

---

## 🚀 Features

- 🧠 AI-based professional code review  
- ⚡ Powered by Google Gemini AI  
- ✨ Syntax-highlighted code editor  
- 📋 Markdown-rendered AI feedback  
- 🔍 Detects bugs, performance issues & bad practices  
- 🛡️ Secure backend with environment variables  
- 🌍 Deployed and accessible worldwide  

---

## 🛠️ Tech Stack

### Frontend

- ⚛️ React (Vite)  
- 🔗 Axios  
- 🎨 PrismJS (Syntax Highlighting)  
- 🧾 React Simple Code Editor  
- 📝 React Markdown  

### Backend

- 🟢 Node.js  
- 🚂 Express.js  
- 🤖 Google Gemini AI API  
- 🔐 CORS  
- 🌱 dotenv  

### Deployment

- ▲ Frontend: Vercel  
- ☁️ Backend: Render  

---

## 📂 Project Structure

```bash
AI-Code-Reviewer/
├── Frontend/
│ ├── src/
│ │ ├── App.jsx
│ │ ├── main.jsx
│ │ └── styles
│ └── index.html
│
├── Backend/
│ ├── src/
│ │ ├── routes/
│ │ ├── controllers/
│ │ └── services/
│ ├── app.js
│ └── server.js
```
---

## ⚙️ How It Works

1. User writes or pastes code in the editor  
2. Frontend sends code to backend API  
3. Backend forwards it to Gemini AI  
4. Gemini reviews the code and returns feedback  
5. Frontend displays the review in a readable format  

---

## 🧪 Run Locally

### Clone the repository

git clone https://github.com/Akshat-1618/AI-Code-Reviewer.git

---

### Backend Setup

```bash
cd backend
npm install
```

#### Create a `.env` file:

GOOGLE_GEMINI_KEY=your_api_key_here


#### Start backend:

```bash
node server.js
```
---

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 🔐 Environment Variables

| Variable | Description |
|----------|-------------|
| GOOGLE_GEMINI_KEY | Your Google Gemini API key |

---

## 📈 Future Improvements

- User authentication  
- Chat-based code review  
- Code quality scoring  
- Multi-language support  
- Save/download reviews  
- Rate limiting & abuse protection  

---

## 👨‍💻 Author

**Akshat Saxena**  
Software Developer | AI & Full Stack Enthusiast  

---

## ⭐ Support

If you like this project, please consider giving it a ⭐ on GitHub!
