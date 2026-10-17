# SmartPD v0.3 — bilingual guided capture

Static English-first / Chinese-switchable prototype. Includes desktop QR code to the published GitHub Pages URL, phone/computer guidance, card-on-forehead illustrated instructions, front-camera preference, three-second countdown and local photo preview.

## Deployment
Upload all five files (`index.html`, `style.css`, `app.js`, `smartpd-qr.png`, `README.md`) to the **root** of `smartpd-lab/smartpd-web` on the `main` branch. GitHub Pages should use `main` / `(root)`.

## Testing
Open `https://smartpd-lab.github.io/smartpd-web/` on a phone, tap Start camera, allow camera access, then capture. Test language switch and QR code from a computer screen. Desktop webcams are also supported.

## Important limitations
No actual PD measurement, face detection, card detection, automated positioning validation, or demo video yet. The illustration is instructional, not a verified optical geometry reference. Arm's length and looking at a near phone do not establish distance PD. The card's forehead plane is not the pupil plane. No prescription-ready output. No image uploads or analytics are implemented in these files; verify deployment and third-party browser behavior before public testing. Avoid showing unmasked payment cards.
