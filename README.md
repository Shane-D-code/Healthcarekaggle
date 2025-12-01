# Healthcare LLM Analytics Platform

AI-powered healthcare data analysis platform with multi-agent system, React dashboard, and intelligent insights generation.

## Quick Start

```bash
git clone https://github.com/Shane-D-code/Healthcarekaggle.git
cd Healthcarekaggle
chmod +x setup_all.sh
./setup_all.sh
```

Architecture
AI Engine: Multi-agent LLM system with Gemini integration

Frontend: React dashboard with real-time analytics

Backend: Python FastAPI + Java processing

Data: Health tracking and trend analysis

Components
AI System (/AI)
Multi-agent reasoning engine

Pattern analysis and insights

Session memory and observability

API integrations

Frontend (/FrontEnd)
React dashboard with Tailwind CSS

Real-time health metrics visualization

Interactive charts and analytics

Responsive design

Backend (/health-backend-java)
FastAPI data processing

Health data models

Multi-agent coordination

REST API endpoints

Setup
Prerequisites
Python 3.8+

Node.js 16+

Java 11+

Individual Setup
# AI System
./setup_ai.sh

# Frontend
./setup_frontend.sh

# Backend
./setup_backend.sh

Copy
Environment Variables
# Required API keys
GEMINI_API_KEY=your_key_here
OPENAI_API_KEY=your_key_here

Copy
Usage
Start All Services
./start_portal.sh

Copy
bash
Individual Services
# Frontend (port 3000)
cd FrontEnd && npm run dev

# Backend (port 8000)
cd health-backend-java/health-backend && python integrated_main.py

# AI Service
cd AI && python sample_usage.py

Copy
bash
Features
Health Data Analysis: Process and analyze health metrics

AI Insights: Generate intelligent health recommendations

Trend Forecasting: Predict health trends and patterns

Interactive Dashboard: Visualize data with charts and metrics

Multi-Agent System: Coordinated AI agents for comprehensive analysis

Data Format
Upload CSV files with columns:

date, steps, heart_rate, sleep_hours, calories, weight

API Endpoints
POST /upload - Upload health data

GET /insights - Get AI-generated insights

GET /trends - Retrieve trend analysis

POST /chat - Interactive health assistant

Tech Stack
AI: Python, Gemini API, OpenAI

Frontend: React, Vite, Tailwind CSS, Recharts

Backend: FastAPI, Pandas, NumPy

Deployment: Vercel, Docker support
