# SmartPD v0.2a
Mobile-first capture workflow prototype. No PD measurement or prescription output.

## Run locally
From this folder: `py -m http.server 8000` then open `http://localhost:8000` on the same computer.

## Phone test
Host the folder on an HTTPS static site (such as GitHub Pages). Opening a desktop's `http://192.168...` address on a phone will generally not grant camera access because it is not a secure context. Use the HTTPS URL on the phone. No backend, analytics or image upload is included.

## Privacy
Photos are held only in browser memory as temporary object URLs; do not use sensitive cards. Photos are not transmitted by the supplied code. Browser/device behavior should be tested before public launch.

## Roadmap
Add demo video; automatic face/card detection; fixation protocol; calibrated optics; independent reference validation. No medical/prescription claims.
