# KareerHub 🎯

**KareerHub** is an AI-integrated placement assistance web platform that empowers students to prepare for careers with personalized support. It includes resume analysis, mock interviews, a smart chatbot, and structured study material. Built using **React.js**, **Flask**, and **MongoDB**, KareerHub bridges the gap between college education and career readiness.

## 🚀 Features

- 🔐 **Google OAuth Authentication**
- 📝 **Resume Upload & AI Feedback**
- 🤖 **AI-Powered Chatbot**
- 🎤 **Mock Interview Simulation**

## 🛠️ Tech Stack

**Frontend**:  
- React.js  
- HTML, CSS, JavaScript  
- Bootstrap  

**Backend**:  
- Flask (Python)  
- MongoDB (Database)

**AI/ML**:  
- Google PaLM (Generative AI)  
- Text classification for resume insights

## 📁 Project Structure

```plaintext
KareerHub/
├── client/                 # React frontend
│   ├── public/
│   └── src/
├── server/                 # Flask backend
│   ├── app.py
│   ├── resume_analysis.py
│   ├── chatbot/
│   └── config/
└── README.md
```

## 💡 Key Modules

- **Resume Analyzer**: Uses ML to provide actionable feedback on uploaded resumes.
- **Chatbot**: Built on Google’s PaLM for intelligent query resolution.
- **Mock Interview**: Offers AI-driven questions and feedback.
- **Study Materials**: Curated content from top universities and educators.

## 🧪 How to Run Locally

1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/KareerHub.git
   cd KareerHub
   ```

2. **Start Backend (Flask)**
   ```bash
   cd server
   pip install -r requirements.txt
   python app.py
   ```

3. **Start Frontend (React)**
   ```bash
   cd client
   npm install
   npm start
   ```

## 🧠 Future Scope

- Mobile app (React Native)
- GPT-4 integration
- Auto resume formatting
- Admin panel enhancements

## 📄 License

This project is licensed under the MIT License.

