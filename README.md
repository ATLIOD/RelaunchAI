# RelaunchAI

Monorepo scaffold with a Python backend and a Next.js frontend.

## Project Structure

- `backend/` — FastAPI service
- `frontend/` — Next.js application

## Backend (Python)

```bash
cd backend
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

Backend will run at `http://localhost:8000` and exposes `GET /health`.

## Frontend (Next.js)

```bash
cd frontend
npm install
npm run dev
```

Frontend will run at `http://localhost:3000`.
