# 009 — Multiple enrollment tables and last-entry tracking

**Summary**
Design a clean schema for per-activity enrollment lists (instead of extra1/extra2/extra3 tables) and implement a `last_entry` tracking mechanism.

**Motivation**
Ayushmanas uses multiple `extra` tables and a `last_entry` table; we should model enrollments as relations and provide last-entry metadata.

**Acceptance criteria**
- Enrollment table that links students to activities (many-to-many) with timestamps.
- `last_entry`/audit metadata stored per student enrollment or as a separate table.
- Migration and sample data script.

**Estimate**: Small

**Labels**: db, schema
