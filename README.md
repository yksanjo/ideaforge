# IdeaForge - AI-Powered Project Idea Generator

<p align="center">
  <img src="https://img.shields.io/badge/Python-FastAPI-00d4aa?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/AI-Ideas-7c3aed?style=for-the-badge&logo=openai" alt="AI">
</p>

AI-powered project idea generator using LLMs to create innovative project ideas based on market trends and gaps.

## 🌟 Features

- **AI-Powered Generation** - Generate creative project ideas using LLM
- **Market Analysis** - Analyze trends and find opportunities
- **Tech Stack Recommender** - Get modern tech stack suggestions
- **MVP Builder** - Generate MVP feature lists
- **Competition Research** - Analyze similar existing projects
- **Save & Export** - Save ideas locally or export to Markdown

## 🚀 Quick Start

```bash
cd backend
pip install -r requirements.txt
python -m uvicorn app.main:app --reload

cd ../frontend
python -m http.server 8080
```

## 🔌 API Endpoints

- `POST /api/ideas/generate` - Generate AI ideas
- `GET /api/ideas` - Get saved ideas
- `POST /api/analyze` - Run market analysis

---

Built with ⚡ for developers seeking inspiration
