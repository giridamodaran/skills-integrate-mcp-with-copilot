# 008 — Admin delete and management tools

**Summary**
Provide admin-only endpoints and UI to delete student profiles, manage activities, and perform bulk operations (export/import simple CSV).

**Motivation**
Ayushmanas includes `deladmin.php` and related confirm flows; admins need safe management tools.

**Acceptance criteria**
- Admin-restricted delete with confirmation and audit logging.
- Activity management endpoints (create/update/delete activity metadata).
- Optional CSV export of students/activities.

**Estimate**: Medium

**Labels**: backend, admin, maintenance
