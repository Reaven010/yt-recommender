# 🚀 AI YouTube Recommender Agent

An advanced, agentic YouTube recommendation engine built with **CrewAI**, **FastAPI**, and **Next.js**. This application uses a specialized crew of AI agents to search, analyze transcripts, and rank the best YouTube videos for any given topic.

![Galaxy Background](https://www.reactbits.dev/backgrounds/galaxy)

## 🌟 Features

- **Agentic Workflow**: Four specialized agents (Search, Transcript Extractor, Content Analyst, and Evaluator) collaborate to find the highest quality content.
- **Deep Analysis**: Automatically extracts and summarizes video transcripts to understand the actual content before recommending.
- **Real-time Feedback**: Watch the agents' "thoughts" and reasoning steps live in the frontend Activity Log.
- **Premium UI**: Interactive 3D Galaxy background from React Bits with a sleek, modern dashboard.

## 🏗️ Architecture

- **Frontend**: Next.js 15, Tailwind CSS, Lucide React, OGL (3D Galaxy).
- **Backend**: FastAPI (Python), CrewAI (Agent Orchestration).
- **LLM**: Google Gemini 1.5 Flash / 2.0 Flash.
- **Tools**: Google YouTube Data API, YouTube Transcript API.

## 🛠️ Installation & Setup

### 1. Prerequisites
- Python 3.10+
- Node.js 18+
- [Google AI Studio API Key](https://aistudio.google.com/)
- [YouTube Data API v3 Key](https://console.cloud.google.com/)

### 2. Backend Setup
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: .\venv\Scripts\activate
pip install -r requirements.txt
```

Create a `backend/.env` file:
```env
GOOGLE_API_KEY=your_gemini_api_key
YOUTUBE_API_KEY=your_youtube_api_key
```

### 3. Frontend Setup
```bash
cd frontend
npm install
```

Create a `frontend/.env.local` file:
```env
NEXT_PUBLIC_API_URL=http://localhost:8001
```

## 🚀 Running the App

### Start Backend
```bash
cd backend
uvicorn main:app --reload --port 8001
```

### Start Frontend
```bash
cd frontend
npm run dev
```

Visit `http://localhost:3000` to start exploring!

## 🚢 Deployment

### Backend (Render/Railway)
- Root: `backend`
- Build: `pip install -r requirements.txt`
- Start: `uvicorn main:app --host 0.0.0.0 --port $PORT`

### Frontend (Vercel)
- Root: `frontend`
- Build: `npm run build`
- Environment Variable: `NEXT_PUBLIC_API_URL` (Point to your deployed backend)

## 📜 Credits

- **[No-as-a-Service](https://github.com/hotheadhacker/no-as-a-service)**: Special thanks to [Salman Qureshi (hotheadhacker)](https://github.com/hotheadhacker) for the satirical API used to handle system errors with style.

---
Built with ❤️ by [Reaven010](https://github.com/Reaven010)


## Daily Activity Log
- [2026-07-29 21:40:15] Automated activity update (1/10)
- [2026-07-29 21:40:23] Automated activity update (2/10)
- [2026-07-29 21:40:27] Automated activity update (3/10)
- [2026-07-29 21:40:30] Automated activity update (4/10)
- [2026-07-29 21:40:33] Automated activity update (5/10)
- [2026-07-29 21:40:37] Automated activity update (6/10)
- [2026-07-29 21:40:42] Automated activity update (7/10)
- [2026-07-29 21:40:46] Automated activity update (8/10)
- [2026-07-29 21:40:49] Automated activity update (9/10)
- [2026-07-29 21:40:56] Automated activity update (10/10)
- [2026-07-30 21:04:04] Automated activity update (1/10)
- [2026-07-30 21:04:07] Automated activity update (2/10)
- [2026-07-30 21:04:10] Automated activity update (3/10)
- [2026-07-30 21:04:13] Automated activity update (4/10)
- [2026-07-30 21:04:16] Automated activity update (5/10)
- [2026-07-30 21:04:19] Automated activity update (6/10)
- [2026-07-30 21:04:22] Automated activity update (7/10)
- [2026-07-30 21:04:25] Automated activity update (8/10)
- [2026-07-30 21:04:28] Automated activity update (9/10)
- [2026-07-30 21:04:31] Automated activity update (10/10)
- [2026-07-31 10:21:48] Automated activity update (1/10)
- [2026-07-31 10:21:51] Automated activity update (2/10)
- [2026-07-31 10:21:54] Automated activity update (3/10)
- [2026-07-31 10:21:57] Automated activity update (4/10)
- [2026-07-31 10:22:00] Automated activity update (5/10)
- [2026-07-31 10:22:03] Automated activity update (6/10)
- [2026-07-31 10:22:06] Automated activity update (7/10)
- [2026-07-31 10:22:09] Automated activity update (8/10)
- [2026-07-31 10:22:12] Automated activity update (9/10)
- [2026-07-31 10:22:15] Automated activity update (10/10)
- [2026-08-01 12:39:47] Automated activity update (1/10)
- [2026-08-01 12:39:50] Automated activity update (2/10)
- [2026-08-01 12:39:53] Automated activity update (3/10)
- [2026-08-01 12:39:56] Automated activity update (4/10)
- [2026-08-01 12:39:59] Automated activity update (5/10)
- [2026-08-01 12:40:02] Automated activity update (6/10)
- [2026-08-01 12:40:05] Automated activity update (7/10)
- [2026-08-01 12:40:08] Automated activity update (8/10)
- [2026-08-01 12:40:12] Automated activity update (9/10)
- [2026-08-01 12:40:16] Automated activity update (10/10)
- [2026-08-02 00:58:22] Automated activity update (1/10)
- [2026-08-02 00:58:25] Automated activity update (2/10)
- [2026-08-02 00:58:28] Automated activity update (3/10)
- [2026-08-02 00:58:30] Automated activity update (4/10)
- [2026-08-02 00:58:33] Automated activity update (5/10)
- [2026-08-02 00:58:36] Automated activity update (6/10)
- [2026-08-02 00:58:39] Automated activity update (7/10)
- [2026-08-02 00:58:42] Automated activity update (8/10)
- [2026-08-02 00:58:45] Automated activity update (9/10)
- [2026-08-02 00:58:47] Automated activity update (10/10)
- [2026-08-03 00:00:02] Automated activity update (1/10)
- [2026-08-03 00:00:10] Automated activity update (2/10)
- [2026-08-03 00:00:15] Automated activity update (3/10)
- [2026-08-03 00:00:20] Automated activity update (4/10)
- [2026-08-03 00:00:24] Automated activity update (5/10)
- [2026-08-03 00:00:28] Automated activity update (6/10)
