# Lab Test Calculator

A lightweight, mobile-friendly progressive web app prototype with offline caching after its first successful load.

## Files
- `index.html`: interface and calculation logic.
- `manifest.webmanifest`: installable app metadata.
- `sw.js`: offline cache service worker.
- `icon.svg`, `icon-192.png`, `icon-512.png`: app icons.

## Run locally
Open `index.html` in a modern browser to test calculations. Browser offline installation and service-worker caching require hosting over HTTPS or localhost.

## Deploy as a website / installable app
1. Upload all four files to the root of a static hosting project.
2. Enable HTTPS.
3. Open the URL in Chrome on Android and choose Install app / Add to Home screen.
4. Test offline mode after the first successful load.

Suitable static hosts include GitHub Pages, Cloudflare Pages, or Netlify. Use a repository and account you control.

## Android store path
For Google Play, package the hosted PWA with a trusted Android packaging workflow such as a Trusted Web Activity. Set up signing keys, privacy disclosures, store assets, and testing. Review current Google Play requirements before submission. This source package is not itself an APK.

## Clinical validation checklist before public release
- Have a qualified laboratory professional independently verify every equation, unit, intended population, and limitation.
- Add citations/references and version/date to each formula record.
- Build automated tests with known input/output examples, boundary cases, unit checks, and zero-denominator checks.
- Have a medical/laboratory reviewer approve clinical language.
- Test on current Android Chrome, desktop Chrome/Firefox/Edge/Safari, small screens, and offline mode.
- Publish a privacy policy and support contact. This prototype does not send values to a server, but hosting analytics or future features could change that.
- Do not use as a medical device or for patient-care decisions until appropriate regulatory, clinical, and legal review is complete.

## Important
The app is a development prototype, not a clinically validated medical device. eGFR and other calculations have population and method limitations. Confirm the formulas against current authoritative guidance and local laboratory SOPs before release.
