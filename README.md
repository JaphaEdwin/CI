# Align Tech Intake (Tesla-inspired UI)

This is a **GitHub Pages–friendly** version of your Corporate Identity Intake form.
- Minimal, premium layout inspired by high-end product sites.
- Tech-innovation graphics (no cars).
- Live completion indicator, step navigation, autosave to localStorage.
- Exports JSON so you can test without a backend.

## Files
- `index.html` (everything is in one file)

## Run locally
Just open `index.html` in your browser, or serve it:
- VS Code → Live Server
- or `python -m http.server 8000` then open `http://localhost:8000`

## Deploy on GitHub Pages
1. Create a repo
2. Add `index.html`
3. Repo Settings → Pages → Deploy from branch → `/ (root)`

## Submission / Email to iyundhue@gmail.com
GitHub Pages is static, so it **cannot send emails by itself**.

You have two clean options:
### Option A) Your own backend (recommended)
- Set `SUBMIT_ENDPOINT` in `index.html` to your API (e.g. `https://yourdomain.com/api/intake`)
- Your backend sends the email to **iyundhue@gmail.com**

### Option B) Formspree (fast testing)
- Create a Formspree form and get an endpoint like: `https://formspree.io/f/XXXXXXX`
- Set `SUBMIT_ENDPOINT` to that URL.
- In Formspree settings, configure notifications to email **iyundhue@gmail.com**.

## Notes
- Demo mode: if `SUBMIT_ENDPOINT` is empty, submit will download a JSON file.
- Required field highlighting happens on submit.
- A spam honeypot is included.
Generated: 2026-02-12


## Freepik imagery
This template does **not** bundle Freepik images (license varies). Search for `FREEPIK_PLACEHOLDER` in `index.html` and replace the placeholder background with your licensed Freepik image URLs/files.
