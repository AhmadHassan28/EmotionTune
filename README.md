# 🎵 EmotionTune

**EmotionTune** is an AI-powered web app that detects emotions from images
and recommends mood-based music.

## 🚀 Features
- Capture or upload image
- Detect emotion using pretrained DeepFace model
- Recommend songs based on emotion
- Track user history (MongoDB)
- Dockerized full-stack deployment

## 🧠 Tech Stack
- FastAPI (Backend)
- DeepFace (AI Model)
- React (Frontend)
- MongoDB Atlas (Database)
- Docker + Cloud Run (Deployment)

## ⚙️ Folder Structure
backend/ → FastAPI backend  
frontend/ → React frontend  
model/ → pretrained model  

## 🏁 How to Run (Local)
```bash
cd backend
python -m venv venv
.\venv\Scripts\activate
pip install -r app/requirements.txt
uvicorn app.main:app --reload
