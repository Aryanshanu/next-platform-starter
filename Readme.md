# Sahayak AI - Educational Platform
AI-Powered Teaching Assistant for Multi-Grade Classrooms

🚀 Elevating education with AI agents – Automating lesson planning, worksheet generation, and personalized feedback to empower teachers in diverse classrooms.

# Key Highlights
✅ 6 Specialized AI Agents – Textbook analysis, visual aids, voice interaction, grading, lesson planning, and feedback
✅ Multi-Grade Magic – Generates differentiated worksheets from a single textbook page
✅ Voice-First – Hands-free operation for busy teachers
✅ PWA Ready – Works offline in low-connectivity areas
✅ Accessible – WCAG-compliant UI with screen reader support

# Tech Stack
Backend: FastAPI + Python
AI: Google Gemini (RAG-enhanced)
Frontend: PWA (HTML5/CSS3/JS)
Database: Firestore
Deployment: Cloud Run / Firebase

# Why Sahayak?
Teachers in multi-grade classrooms (common in rural/underfunded schools) juggle 4-5 grade levels simultaneously. Sahayak’s AI agents:

⏱ Save 10+ hours/week on lesson planning

✍️ Auto-generate grade-specific worksheets

🎨 Create blackboard-friendly visuals

🗣 Answer curriculum questions via voice

#  Hackathon Focus
🔹 Agentic Architecture: Collaborative AI agents with specialized roles
🔹 Gemini Integration: RAG-powered textbook analysis + worksheet generation
🔹 Real-World Impact: Designed with teachers from rural Indian schools


###### 🚀  Installation Guide
Prerequisites
Python 3.8+

Google Cloud Account (for Gemini API & Firestore)

Firebase Project (Authentication)

# Step 1: Clone & Setup

bash
git clone https://github.com/your-repo/sahayak-ai.git
cd sahayak-ai
python -m venv venv
source venv/bin/activate  # Windows: `venv\Scripts\activate`

# Step 2: Install Dependencies
bash
pip install -r requirements.txt

# Step 3: Configure Secrets
Create .env file from the template:

bash
cp .env.example .env
Add your keys:

# .env
GOOGLE_API_KEY=your_gemini_key
FIREBASE_CREDENTIALS=path/to/firebase.json

#  Configure Firebase
Download your Firebase serviceAccount.json from:
Firebase Console → Project Settings → Service Accounts

Place it in /sahayak-ai/auth/

# Step 4: Run the Backend
bash
python main.py
➔ API Docs: http://localhost:8000/docs

Firebase Errors: Ensure serviceAccount.json has Firestore + Auth permissions

# Step 5: Launch Frontend

Frontend: Open templates/index.html in browser → "Install as PWA"

PWA Install: Click "Add to Home Screen" (Chrome/Edge)


Demo Credentials: test@example.com / demo123

