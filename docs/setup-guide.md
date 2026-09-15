# AURA Fraud Detecting System — Setup Guide

> AURA Security Brain is a fictional banking cybersecurity and fraud-detection platform developed for the IBM BOB Hackathon. It demonstrates transaction risk analysis, adaptive authentication, anomaly detection, security alerts, incident management, and audit tracking
## Prerequisites

Before you begin, ensure you have the following installed:
* [ ]	Python 3.11+
* [ ]	Node.js 18+
* [ ]	npm 9+
* [ ]	PostgreSQL 14+ (or Docker Desktop)
* [ ]	Git

## Environment Variables

Copy `.env.example` to `.env` and fill in the values:

```bash
cp .env.example .env
```

| Variable | Description | Required |
|---|---|---|
DATABASE_URL |	PostgreSQL connection string	| Yes
SECRET_KEY | Secret key used for protected sessions |	Yes
DEMO_PASSWORD	| Password for the demo applications	| Yes
FRONTEND_URL |	Frontend application URL |	Yes

## Installation

```bash
# 1. Clone the repository
git clone https://github.com/maitriyee16/bob-ai-hackathon-FinGuard.git
cd bob-ai-hackathon-FinGuard

# 2. Install backend dependencies
[your command — e.g.: pip install -r requirements.txt]

# 3. Install frontend dependencies (if applicable)
[your command — e.g.: cd frontend && npm install]

# 4. Set up the database (if applicable)
[your command — e.g.: python manage.py migrate]
```

## Running the Application

```bash
# Start the backend
[your command — e.g.: uvicorn app.main:app --reload]

# Start the frontend (in a separate terminal, if applicable)
[your command — e.g.: cd frontend && npm run dev]
```

The application will be available at: `http://localhost:[PORT]`

## Running Tests

```bash
[your test command — e.g.: pytest tests/ -v]
```

## Quick Demo (Optional)

If you have a demo script or sample data to showcase the project quickly:

```bash
[e.g.: python demo/seed_demo_data.py]
[e.g.: open http://localhost:8000/demo]
```

## Troubleshooting

| Issue | Solution |
|---|---|
| [e.g., `ModuleNotFoundError`] | [e.g., Run `pip install -r requirements.txt` again] |
| [e.g., Database connection refused] | [e.g., Ensure PostgreSQL is running: `docker compose up db`] |
| [e.g., watsonx.ai 401 error] | [e.g., Check `WATSONX_API_KEY` in your `.env` file] |
