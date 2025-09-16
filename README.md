# InnerGlow
AI-powered mental health companion that detects emotions, supports users, and suggests personalized coping strategies.
An empathetic AI companion that detects emotional states from text & voice, provides supportive responses, and escalates to human help during crises.
🌍 Problem Statement
Mental health challenges such as stress, anxiety, and depression are growing worldwide. Access to professional help is often limited due to stigma, cost, and availability. Early detection and timely support can make a life-changing difference.
However, most existing solutions are either limited chatbots with scripted responses or clinical tools not designed for everyday use. There is a need for an AI-powered, ethical, and empathetic mental health companion that bridges this gap.
💡 Solution
InnerGlow is a full-stack AI system that:
Analyzes text & voice to detect emotions and mental-health risks in real time.
Generates empathetic, safe responses powered by NLP and large language models.
Provides personalized coping strategies (not medical advice, but supportive tips).
Escalates to human help if a crisis or suicidal ideation is detected.
Offers a dashboard for insights (trends, emotion tracking, anonymized reports).
🚀 Features
🎯 Minimum Viable Product (MVP)
 Emotion detection from text (multi-label classifier).
 Risk/crisis detection (binary classifier).
 Empathetic AI chatbot with safe responses.
 Web chat interface (React + FastAPI).
 Crisis escalation (emergency contacts/resources).
🌟 Future Enhancements
 Voice input (speech → text via Whisper).
 Sentiment timeline visualization (graphs/charts).
 Personalized recommendation engine.
 Mobile app integration (React Native/Flutter).
 Clinician dashboard for aggregated anonymized trends.
🛠️ Tech Stack
Programming Language: Python 3.11+
AI/ML Frameworks: PyTorch, Hugging Face Transformers, Datasets
ASR (Speech-to-Text): OpenAI Whisper
Backend: FastAPI (REST APIs), Docker
Frontend: React.js (chat UI, visualization)
Database: PostgreSQL (user logs), Redis (cache)
Deployment: AWS/GCP/Render + Docker + Hugging Face Hub
DevOps/MLOps: GitHub Actions, model versioning, experiment tracking (Weights & Biases)
📅 Roadmap (Week 0 → Week 14)
Week 0: Setup tools, repo, documentation, roadmap
Week 1: Hugging Face & Whisper hands-on, baseline ML prototype
Week 2: Data ingestion & exploratory analysis (GoEmotions, DAIC-WOZ)
Week 3: Baseline emotion classifier (TF-IDF + Logistic Regression)
Week 4: Transformer-based emotion classifier (fine-tune DistilBERT/DeBERTa)
Week 5: Risk/crisis detector (binary classifier + rules)
Week 6: Empathetic LLM response generator (LangChain + FLAN-T5/LLaMA)
Week 7: Voice input pipeline (Whisper integration)
Week 8: Backend API (FastAPI, Dockerized)
Week 9: Frontend React chat interface
Week 10: E2E integration + user testing
Week 11: MLOps (CI/CD, model versioning, monitoring)
Week 12: Safety & ethics compliance (consent, escalation flow)
Week 13: Documentation, demo video, polish
Week 14: Load testing, deployment scaling, placement-ready demo
📊 System Architecture (High-Level)
User (text/voice) 
     ↓
Whisper (speech → text)
     ↓
Emotion Classifier (multi-label transformer)
     ↓
Risk Detector (binary classifier + rules)
     ↓
LLM Responder (empathetic reply generator)
     ↓
Backend API (FastAPI + Docker)
     ↓
Frontend (React chat UI + visualizations)
     ↓
Database (PostgreSQL + Redis)
     ↓
Deployment (AWS/GCP + Hugging Face Hub)
⚖️ Ethics & Safety
Not a replacement for therapy or medical diagnosis.
Explicit disclaimer shown to all users.
Crisis detection triggers emergency escalation (hotlines/resources).
Privacy-first design: no unnecessary personal data stored.
📌 Project Vision
InnerGlow is designed as a portfolio-defining, socially impactful AI project that demonstrates:
Advanced ML/NLP techniques.
Full-stack engineering (frontend + backend + ML + deployment).
Responsible AI principles (ethics, safety, transparency).
Real-world application potential in healthcare & wellbeing.
✍️ Journal & Documentation
docs/vision.md → detailed project proposal
docs/journal.md → daily/weekly logs of progress & learnings
CONTRIBUTING.md → guidelines (for professionalism, even if solo)
🏆 Placement Pitch
“I built an AI Mental Health Companion that uses transformers and speech recognition to detect emotions, provides empathetic responses, and safely escalates crises. It’s an end-to-end full-stack AI product demonstrating my expertise in ML, engineering, and ethical AI deployment.”
