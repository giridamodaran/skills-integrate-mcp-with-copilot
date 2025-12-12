# 001 — Add authentication and role-based access

**Summary**
Add user authentication and role-based access control (STUDENT, FACULTY, ADMIN) so pages and API endpoints are protected and users see role-appropriate UI.

**Motivation**
Our FastAPI app currently has no authentication; the Ayushmanas project includes login and role routing which we should replicate to control access and enable admin/faculty actions.

**Acceptance criteria**
- Users can register/login with email+password.
- Roles supported: `STUDENT`, `FACULTY`, `ADMIN`.
- Protected endpoints and pages require a valid session or token.
- Admin-only endpoints are restricted to the ADMIN role.
- End-to-end tests for login/logout and role-restricted access exist.

**Implementation notes**
- Use FastAPI `Depends` with OAuth2 password flow or session cookies.
- Store hashed passwords (bcrypt) and roles in DB.

**Estimate**: Medium

**Labels**: enhancement, auth, backend
