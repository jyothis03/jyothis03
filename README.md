<div align="center">

# Hey, I'm Jyothis 👋

**Backend Developer** · Python · FastAPI · Node.js · PostgreSQL

[![Email](https://img.shields.io/badge/jyothisb003@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:jyothisb003@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jyothis-b-214437368/)
[![GitHub](https://img.shields.io/badge/jyothis03-181717?style=flat&logo=github&logoColor=white)](https://github.com/jyothis03)

</div>

---

I build backend systems that are modular, well-structured, and actually work.  
Just finished my B.Tech in Computer Science and Design at FISAT, Ernakulam ( 2022-26 )

---

## What I'm building right now

### ⚽ World Cup 2026 AI Prediction App
> FastAPI · Gemini API · Google Search Grounding · React · Redis

AI-powered tactical match predictions for World Cup 2026. Gemini searches for
live injury news, squad form, and H2H records before generating structured
predictions — no stale training data. Two-step grounded generation pipeline
with Redis caching and a real-time community voting layer via WebSockets.

**How it works**
- Static match data (fixtures, venues, team stats) limited to World Cup 2026 is loaded from curated JSON files
- Gemini 2.5 Flash with Google Search grounding fetches live squad news and injuries
- Two-step generation: research call (grounded) → structure call (JSON schema via Pydantic)
- Redis caches predictions per match to avoid redundant API calls

**Planned**
- [ ] Live player & form data via football-data API integration
- [ ] Real-time community prediction voting with WebSockets
- [ ] RAG layer — embed injury reports and press conference transcripts
      into a vector store for deeper contextual grounding

## Projects

### 🧠 AI Quiz & Flashcard Generator
> FastAPI · Gemini API · React · Supabase · PostgreSQL

Accepts uploaded documents or topic prompts and generates quiz questions and
flashcards using Gemini. Streams LLM responses back to the frontend for
responsive UX. 
**How it works**
- Documents are uploaded, chunked intelligently, and passed as context to Gemini
- Gemini generates structured quiz questions and flashcards per chunk which are sent to React frontend
  
**Planned**
- [ ] Spaced repetition algorithm for smarter flashcard review scheduling
- [ ] Multi-document support — generate a unified quiz across several uploads
- [ ] Performance analytics — track scores over time and surface weak topics

demo link: https://www.linkedin.com/posts/jyothis-b-214437368_fastapi-python-backenddevelopment-ugcPost-7468392598114648064-wg4R/?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFswU3ABnHcmx0jgLOlJFPtj_-L8h4rqgUM

---

### 💰 Chit Fund Management System
> Node.js · Express · PostgreSQL · Supabase

Financial backend handling OTP verification, JWT auth, scheduled auction tasks,
and automated email notifications for end-to-end fund management.
High ownership of backend architecture, REST API design, and DB schema.

---

## Stack
Backend    Python · FastAPI · Node.js · Express · Pydantic · JWT · WebSockets
Databases  PostgreSQL · MongoDB · Supabase · Redis
Frontend   React · Streamlit
DevOps     Docker · Git · Render · Vercel · Postman

---

## Certifications

AWS Cloud Practitioner · DevOps Fundamentals (IBM) · Intro to NLP (Infosys) · Intro to AI (Infosys)

---

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=jyothis03&show_icons=true&hide_border=true&theme=default" height="130"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jyothis03&layout=compact&hide_border=true&theme=default" height="130"/>
</div>
