Veriessay-AI

Veriessay-AI is an AI-powered admissions essay analysis platform designed to evaluate essays for AI-generated content, writing quality, linguistic patterns, and overall authenticity.

The system combines a FastAPI backend, React + TypeScript frontend, local text-analysis services, and an admissions-essay dataset.

🚀 Features
AI-generated text detection
Essay scoring and analysis
Sentence-level analysis
Text pattern analysis
Explainable detection results
Essay history
Reports dashboard
Metrics overview
Segment-level analysis
Local model analysis
Admissions essay dataset
React-based modern dashboard
🏗️ Architecture
Veriessay-AI/
│
├── backend/
│   ├── app/
│   │   ├── api/
│   │   ├── core/
│   │   ├── db/
│   │   ├── schemas/
│   │   └── services/
│   ├── requirements.txt
│   └── run.py
│
├── dataset/
│   ├── admissions_essay_dataset.csv
│   ├── admissions_essay_dataset.json
│   ├── DATASET_CARD.md
│   └── dataset processing scripts
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── services/
│   │   ├── styles/
│   │   └── types/
│   ├── package.json
│   └── vite.config.ts
│
├── package.json
├── start.bat
├── start.sh
└── prompt.md
🧠 Backend

The backend is built with Python and FastAPI.

Main responsibilities:

REST API
Essay processing
Text analysis
AI-content analysis
Scoring
Database management
Analysis result generation
Backend services
local_model_analyzer.py
scoring_engine.py
text_analyzer.py
🎨 Frontend

The frontend uses:

React
TypeScript
Vite
CSS

Main UI modules include:

Essay submission
Detection dashboard
Results dashboard
Essay history
Reports
Metrics
Sentence highlighting
Segment analysis
Settings
Help
📊 Dataset

The dataset/ directory contains admissions essay data used for analysis and experimentation.

It includes:

CSV datasets
JSON datasets
Human-written essay data
Dataset documentation
Dataset generation scripts
Dataset variation generation
⚙️ Installation
1. Clone the repository
git clone https://github.com/AshrithGowda-codes/Veriessay-AI.git
cd Veriessay-AI
2. Backend setup
cd backend
python -m venv venv

Activate the environment on Windows:

venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt
3. Start backend
python run.py
4. Frontend setup

Open another terminal:

cd frontend
npm install
npm run dev

The Vite development server will provide the frontend URL in the terminal.

🪟 Windows Quick Start

You can also use:

start.bat

to start the project using the provided startup script.

🔬 Project Goal

Veriessay-AI aims to provide an explainable essay-analysis system rather than relying only on a single binary "AI / Human" prediction.

The system analyzes multiple signals and presents interpretable results to help users understand why an essay received a particular score.
