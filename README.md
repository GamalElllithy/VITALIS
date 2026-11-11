# VITALIS
## Beyond Monitoring. Toward Health Autonomy.

VITALIS is a health-monitoring and decision-support software prototype shaped around long-duration space missions. It aims to organize health observations, establish personalized baselines, analyze trends, surface explainable signals, assess data quality, and support offline-first use.

## Problem and proposed solution

Long-duration missions can involve constrained connectivity, limited access to in-person care, and individual variation. Teams need a coherent way to review observations and trends while understanding data quality and provenance. VITALIS proposes a modular system for health context, observations, trends, and transparent signals. The problem framing remains provisional and should be refined through documented research.

## Main system components

- Frontend: planned React interface for health context, observations, trends, signals, and mission views.
- Backend: planned versioned API and persistence layer.
- Analytics: research and analysis area for baselines, trends, data quality, and explainable signal exploration.
- Offline support: planned local availability, storage, and synchronization behavior.
- Shared contracts and documentation: agreements and decisions for cross-component work.

## Planned technology stack

- Frontend: React, TypeScript, Vite, Tailwind CSS, React Router, Recharts, Lucide React.
- Backend: Python, FastAPI, Pydantic, SQLAlchemy, PostgreSQL, Alembic.
- Analytics: Python, Pandas, NumPy, SciPy, Jupyter; scikit-learn only if later justified.
- Offline: PWA, Service Workers, IndexedDB, Dexie.js, and a synchronization queue.
- Development: Git, GitHub, VS Code, Pytest, Vitest, and Playwright.

These are planned technologies, not installed or wired into a runnable application.

## Repository structure

- frontend/: client application organization and tests.
- backend/: API, persistence boundaries, migrations, and tests.
- analytics/: research notebooks, package, and validation tests.
- data/: documented locations for research, working, processed, and demonstration data.
- contracts/: shared schemas and integration agreements.
- docs/: architecture, API, data, research, design, team, safety, decisions, and testing documentation.

## Current development status

Repository foundation only. This setup contains documentation and placeholders; it has no React application, API implementation, database models, analytics algorithms, or deployment configuration. The application is not currently runnable.

## Safety and data notice

VITALIS is a prototype for decision support, not a medical diagnostic system. It does not diagnose or treat and does not replace qualified medical professionals. Future signals must be presented as patterns or deviations with clear limitations and human review. Do not commit personal health information, credentials, or data without documented source and usage permission. Clearly label synthetic demonstrations; never present them as research evidence.