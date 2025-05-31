# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

  # Karyatra: Job Tracking Modulation and Resource Recommendation

Karyatra is an AI-powered job application tracking system developed as a web app and Chrome extension. It streamlines job searches, analyzes skill gaps using NLP, and recommends personalized learning resources.

## 🎯 Objectives

- Automate job data collection from various portals.
- Identify missing skills from resumes using NLP.
- Recommend upskilling content (LeetCode, Forage, etc.) via SerpAPI.
- Integrate chatbot and voice assistant for guidance.

## 🧱 System Architecture

- **Frontend**: Vite + React, TailwindCSS, Web Speech API
- **Chrome Extension**: JavaScript, HTML5, Manifest V3, Selenium
- **Backend**: Flask/FastAPI, Python, SQLite/Firebase
- **AI & NLP**: spaCy, OpenRouter AI, Regex
- **APIs**: SerpAPI, Google OAuth, SimpleGmail

## 📦 Key Modules

1. **Authentication & Dashboard**: Secure login, track applications
2. **Chrome Extension**: Bookmark and scrape job data
3. **Email Parsing**: Extract job status from Gmail
4. **Skill Gap Analyzer**: Compare resume & job description
5. **Resource Recommendation**: Suggest tutorials & practice platforms
6. **Chatbot & Voice Assistant**: AI support for job seekers

## 📊 Implementation Highlights

- **Skill Analysis**: Uses spaCy NER and POS tagging.
- **Voice & Chat UI**: STT and TTS APIs for accessibility.
- **Recommendation Engine**: SERP queries for upskilling content.
- **Cloud Integration**: Firebase for real-time data.

## 🚀 Results

- Job scraping: 3–5s/post
- Skill analysis: <1s
- Chatbot response: ~1s
- Voice assistant latency: ~2–4s

## 🔍 Observations

- ~95% scraping accuracy on standard sites
- Bookmark integration boosted organization
- Skill gap insights aided preparation

## 🧪 Tools & Technologies

- Frontend: React, TailwindCSS, Web APIs
- Backend: Python, Flask/FastAPI, SQLite, Firebase
- NLP: spaCy, Regex
- APIs: OpenRouter AI, SerpAPI, Google OAuth

## 📈 Future Scope

- LinkedIn/GitHub OAuth for resume import
- ML-based resume analyzer
- Real-time push notifications
- Mobile app support
- Peer job-search collaboration features

 📄 License

This project is licensed under the MIT License.




