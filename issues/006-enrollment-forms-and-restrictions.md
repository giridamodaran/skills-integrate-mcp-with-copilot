# 006 — Enrollment forms and restrictions

**Summary**
Implement server-side enrollment forms and restriction flows: allow students to enroll (or admins to enroll students), show last-entry info, and prevent duplicate admission numbers.

**Motivation**
Ayushmanas provides `enroll.php`, `enrollpro.php`, and `enroll_restr.php` flows that handle restricted enrollments and last-entry tracking.

**Acceptance criteria**
- Enrollment endpoint/form with validation (unique admission number, required fields).
- Admin and student enroll flows with appropriate permissions.
- Last-entry tracking persisted in DB.

**Estimate**: Medium

**Labels**: backend, forms
