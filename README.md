# 🔮 Gemini AI Clone

A **Gemini AI Clone** – a conversational chatbot built using modern web technologies and Gemini API integration. This project features a **web-based interface** and a **Chrome extension**, enabling users to interact with an AI assistant in real-time for various tasks like answering questions, generating responses, and assisting with productivity.

🔗 **Live Demo:** [Gemini Clone](https://geminiclone-1.netlify.app/)

---

## 🚀 Features

* ✨ **Real-time Chat Interface**
* 🔗 **Integrated with Gemini API** (for intelligent responses)
* 🧠 **Context-aware conversation**
* 🌐 **Chrome Extension** version included
* 📱 **Responsive UI** (desktop & mobile friendly)
* 🎨 Clean and minimal user interface

---

## 🖥️ Tech Stack

| Frontend           | Backend / API          | Extension       |
| ------------------ | ---------------------- | --------------- |
| HTML, CSS, JS      | Gemini API (Google AI) | Manifest V3, JS |
| React.js           | Axios / Fetch API calls| Chrome APIs     |

---

## 📂 Project Structure

```
gemini-clone/
│
├── public/
│   └── index.html
│
├── src/
│   ├── assets/
│   ├── components/
│   │   └── ChatBox.jsx
│   ├── App.js
│   └── index.js
│
├── chrome-extension/
│   ├── manifest.json
│   ├── popup.html
│   └── popup.js
│
├── .env (for API key)
├── README.md
└── package.json
```

---

## 🧠 How It Works

1. **User** enters a prompt or question.
2. **Frontend** sends the input to Gemini API using `fetch()` or `axios`.
3. **API Response** is received and displayed in the chat window.
4. **Chrome Extension** mirrors the same flow in a browser popup.

---

## 🔐 Environment Variables

Create a `.env` file in the root with your Gemini API key:

```env
REACT_APP_GEMINI_API_KEY=your_gemini_api_key
```

---

## 🧪 Setup & Run Locally

```bash
# Clone the repo
git clone https://github.com/Aman73800/GEMINI-AI.git
cd GEMINI-AI

# Install dependencies
npm install

# Start the development server
npm start
```

---

## 💡 Future Improvements

* 🎙️ Support for voice commands
* 💾 Conversation history saving
* 🎨 Enhanced chat styling
* 🌙 Dark mode toggle

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Aman Yadav**  
🔗 [LinkedIn](https://linkedin.com/in/aman-yadav-583076239) | 👥 [GitHub](https://github.com/Aman73800) | 🌐 [Live Project](https://geminiclone-1.netlify.app/)
