# TIAGO — Medicine Reminder Demo

An English-language, responsive front-end prototype for a medicine adherence website.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. Use sample details to explore the demo.

## Publish using GitHub Pages
1. Create a GitHub repository named `tiago`.
2. Upload `index.html`, `README.md`, and `.nojekyll` to the repository root.
3. Open **Settings → Pages**.
4. Under build/deployment, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
5. After deployment, the site URL is usually `https://YOUR-USERNAME.github.io/tiago/`.

## Important limitations
- Demo login only: no real OTP or account verification.
- No WhatsApp API integration and no WhatsApp messages are sent.
- Data is stored in localStorage in this browser/device; there is no secure cloud database.
- Browser notification permission does not create reliable scheduled background reminders.
- Do not enter real patient or sensitive health information.
- Follow the prescription and clinician/pharmacist instructions. The site does not prescribe medicines or decide doses.
