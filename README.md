# JuriForge

A Firebase-based legal management platform built for lawyers, featuring two distinct AI-powered chatbots — a Gemini API-integrated LLM assistant and a custom NLP-based in-app navigation/Q&A bot.

## 👥 Team

Led a team of 4 as part of this project.

## ✨ Features

- **Legal Case & Client Management** — Centralized platform for lawyers to manage cases, clients, and documentation
- **Gemini API Chatbot** — LLM-powered assistant integrated via Google's Gemini API for legal query handling and conversational assistance
- **NLP Q&A & Navigation Chatbot** — A separate, custom-built NLP chatbot that helps users navigate the app and get quick answers, independent of the Gemini-based LLM bot
- **Firebase Backend** — Real-time database, authentication, and hosting powered by Firebase

## 🛠️ Tech Stack

- **Backend/Database:** Firebase (Firestore, Auth, Hosting)
- **AI/LLM:** Google Gemini API
- **NLP:** Custom-built NLP model for Q&A and navigation
- <!-- Add your frontend framework here, e.g. React / Flutter / etc. -->

## 🏗️ Architecture

JuriForge integrates two separate chatbot systems:
1. **Gemini-powered chatbot** — Handles open-ended legal queries and conversational assistance using Google's LLM
2. **NLP navigation/Q&A chatbot** — A rule-based/ML NLP system dedicated to helping users navigate the platform and answering common questions, kept separate from the LLM chatbot for faster, more predictable responses

## 🚀 Getting Started

### Prerequisites
- Node.js (or relevant runtime)
- Firebase account and project setup
- Gemini API key

### Installation
```bash
git clone https://github.com/<your-username>/juriforge.git
cd juriforge
# install dependencies (adjust based on your stack)
npm install
```

### Configuration
Create a `.env` file in the root directory and add:
```
FIREBASE_API_KEY=your_firebase_api_key
FIREBASE_PROJECT_ID=your_project_id
GEMINI_API_KEY=your_gemini_api_key
```

### Run locally
```bash
npm start
```

## 📸 Screenshots
<!-- Add screenshots or a demo GIF/video link here -->

## 📄 License
<!-- Add your license here, e.g. MIT -->

## 🙋‍♀️ Author
**Gauri Kulkarni**
- LinkedIn: [linkedin.com/in/gaurikulkarni0806](https://linkedin.com/in/gaurikulkarni0806)
- Email: gaurikulkarni0806@gmail.com
