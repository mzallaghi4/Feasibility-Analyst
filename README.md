# Feasibility Analyst
**Professional project feasibility and cost analysis.**

Feasibility Analyst is a web-based financial analysis tool designed for analysts to evaluate project viability.
It supports cost estimation, revenue forecasting, financing modeling, and advanced feasibility metrics (NPV, IRR, payback, Monte Carlo simulation). 
The application is fully bilingual (English/Persian) with RTL support.

## Features
- Project definition and management
- CAPEX/OPEX estimation
- Revenue forecasting with seasonality
- Cash flow and financial statement generation
- Feasibility metrics: NPV, IRR, MIRR, Payback, ROI, Break-even
- Sensitivity analysis, scenario planning, Monte Carlo simulation
- PDF/Excel report export
- Role-based access control
- Persian (Farsi) and English UI with Jalali calendar
- Dockerized deployment and CI/CD

## Tech Stack
**Backend:** Python 3.12, FastAPI, SQLAlchemy 2.0, Alembic, Pydantic v2, PostgreSQL, Redis, Celery  
**Frontend:** React 18, TypeScript, Vite, MUI, Recharts, TanStack Query, i18next  
**DevOps:** Docker, GitHub Actions, Nginx, pre-commit, Ruff, Black, mypy, ESLint, Prettier

## Installation

### Prerequisites
- Docker & Docker Compose
- Node.js 20+ (for local frontend dev)
- Python 3.12+ (for local backend dev)

### Quick Start with Docker
```bash
git clone https://github.com/your-org/feasibility-analyst.git
cd feasibility-analyst
cp .env.example .env
docker-compose up --build





#### LICENSE
Copyright © 2026 Iran Finance. All rights reserved.

No permission to use, copy, modify, distribute, sublicense, or sell this software is granted by this notice.

Contact the rights holder to request authorization. The repository author is Mehdi Zallaghi.
