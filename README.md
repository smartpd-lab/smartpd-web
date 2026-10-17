# SmartPD v0.5 — Experimental assisted measurement

- v0.4 design, bilingual interface, webcam capture, QR.
- Experimental optional MediaPipe Face Mesh iris-center suggestions (internet connection required).
- User MUST mark both upper card corners first, then click auto-detect. If detection fails, continue manual four-point marking.
- Auto suggestions must be visually checked. No automatic card corner detection yet.
- Save multiple independent trial estimates, show mean and range. Data held in page memory, not persisted.
- 85.60 mm * pupil pixel span / card top-edge pixel span is an UNCORRECTED ratio, NOT validated for eyewear prescriptions.
- No server upload of images. MediaPipe model and scripts are fetched from third-party CDN.

## Deploy
Upload the **contents** of smartpd-v0.5/ to the root of GitHub repository main branch. Wait for Pages green check, hard refresh Ctrl+Shift+R.
