# 002 — Add persistent database backing (MySQL)

**Summary**
Replace in-memory storage with a persistent database. Implement models and migrations for activities, students, enrollments, and admin users (MySQL preferred to match the reference).

**Motivation**
Current data is lost on restart. The Ayushmanas repo uses MySQL tables like `stud_adm`, `stud_id`, `extra1/2/3` which we should model more cleanly.

**Acceptance criteria**
- Database connection configuration (env variables) is added.
- SQLAlchemy (or equivalent) models for Activities, Students, Enrollments, Users exist.
- A simple migration strategy (Alembic or SQL scripts) is included.
- App uses DB for reads/writes; tests demonstrate persistence.

**Estimate**: Large

**Labels**: backend, db, persistence
