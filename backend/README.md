# Backend

Planned Python and FastAPI service; no endpoints or database models are implemented.
- app/api/v1/endpoints/: future versioned HTTP route handlers.
- app/core/: settings and cross-cutting concerns.
- app/db/: connection and session configuration.
- app/models/: future persistence models.
- app/repositories/: data access separated from HTTP.
- app/schemas/: Pydantic request and response validation.
- app/services/: application behavior and orchestration.
- migrations/versions/: future Alembic history.
- tests/unit/: isolated behavior.
- tests/integration/: API and persistence boundaries.
Agree on contracts, units, timestamp semantics, validation, and access control before implementation. Never place credentials or private health records in the repository.