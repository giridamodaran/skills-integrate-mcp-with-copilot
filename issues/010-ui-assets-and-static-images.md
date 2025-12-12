# 010 — Add UI assets and static images

**Summary**
Collect and add static UI assets (logo, background, CSS templates) and ensure consistent placement under `static/` so server-rendered pages and static frontend can reuse them.

**Motivation**
The Ayushmanas repo references `images/` and `images/background/logo.png`; we should centralize our assets for dashboards and profile photos.

**Acceptance criteria**
- `static/images` contains logo, background, and placeholder student images.
- Templates reference these assets consistently.
- Basic CSS theme to match Mergington branding.

**Estimate**: Small

**Labels**: frontend, assets
