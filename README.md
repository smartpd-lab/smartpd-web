# SmartPD v0.4 — Guided capture + experimental manual marking

Static bilingual (English/Chinese) mobile-friendly website. Phone QR workflow, computer camera alternative, three-second capture, local image preview, manual 4-point marking, and **uncorrected** experimental 2D PD estimate.

## Privacy
No image uploads, no remote APIs, no analytics. Camera image and results remain in current browser memory. Clear and retake or close the tab to discard. Mask payment card data before using the camera.

## Critical accuracy warning
The result is `85.60 * pupil_pixel_distance / card_pixel_width`, **NOT a validated pupillary distance**. Card placed on forehead is in a different depth plane than pupils; lens distortion, face pose, image perspective, pupil localization, and near gaze all create errors. Not suitable for ordering glasses. Manual markers are not automated iris/pupil detection. An optician should verify any PD used for prescription eyewear. Demo imagery is illustrative.

## Deploy
Upload all files **inside this folder** into repository root `smartpd-lab/smartpd-web`, overwriting existing files. GitHub Pages: Settings > Pages > Deploy from branch `main` / root. HTTPS required for camera on mobile. No paid services.

## Future v0.5
Automated quality gates and landmark detection; card corner detection, camera/depth error analysis, validated fixation protocol, repeatability and comparison against professional pupillometer readings. No claims of clinical accuracy before validation.
