
# 🏋️ FitBuddy – AI Fitness Plan Generator using Gemini Models

FitBuddy is a web-based application that uses AI to generate personalized 7-day workout plans and nutrition/recovery tips based on a user's goal (weight loss, muscle gain, general wellness). Users can also submit feedback to refine their plan, and an admin view shows all users with their original and updated plans.

**Tech Stack:** FastAPI · Google Gemini (1.5 Pro & Flash) · SQLite + SQLAlchemy · HTML/CSS + Jinja2 · Python · Uvicorn

**Project Type:** Group Project  
**Class:** II BSc Computer Science (2025–26)  
**College:** Tiruppur Kumaran College for Women  

## 📂 Project Phases
1. [Brainstorming & Ideation Phase](Phase-1-Brainstorming/README.md)
2. [Requirement Analysis Phase](Phase-2-Requirements/README.md)
3. [Project Design Phase](Phase-3-Design/README.md)
4. [Project Planning Phase](Phase-4-Planning/README.md)
5. [Project Development Phase](Phase-5-Development/README.md)
6. [Project Testing Phase](Phase-6-Testing/README.md)
7. [Project Documentation Phase](Phase-7-Documentation/README.md)
8. [Project Demonstration Phase](Phase-8-Demonstration/README.md)

## ▶️ Quick Start
```bash
git clone [https://github.com/BenaRafi/FitBuddy-.git](https://github.com/BenaRafi/FitBuddy-.git)
cd FitBuddy-
python -m venv venv
venv\Scripts\activate          # Windows  (Linux/Mac: source venv/bin/activate)
pip install -r requirements.txt
# create .env file:  GOOGLE_API_KEY=your_gemini_api_key_here
uvicorn app.main:app --reload
