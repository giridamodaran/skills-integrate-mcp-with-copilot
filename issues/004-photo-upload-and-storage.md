# 004 — Photo upload and storage

**Summary**
Add a secure photo upload endpoint and file storage for student profile pictures, with thumbnailing and references in student records.

**Motivation**
Ayushmanas stores photos under `images/student` and displays them in profiles.

**Acceptance criteria**
- Authenticated upload endpoint that accepts image types and enforces size/type limits.
- Files saved to a `static/uploads` (or `images/student`) directory with unique filenames.
- Student profiles reference uploaded filenames and display images in UI.
- Basic protection against overwrites and dangerous file types.

**Estimate**: Small

**Labels**: backend, file-upload, security
