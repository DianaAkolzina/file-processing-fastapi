# File Processing & Data Handling with FastAPI

A complete backend project showcasing:
- File upload & validation (CSV, JSON)
- Uploading files to AWS S3
- Returning transformed CSVs
- Download endpoints
- Error handling & best practices

## 🧱 Structure

Each route is inside `app/routes/`, and utilities are in `app/utils/`.

## 🚀 Getting Started

1. Clone the repo  
2. Set up `.env` (see `.env.example`)
3. Run:

```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
