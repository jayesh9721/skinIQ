# SkinIQ: Early-Access Landing Page

The pre-launch landing page for **SkinIQ**, a skin-intelligence app idea. It explains why most skincare routines fail and collects early-access sign-ups for the waitlist.

## What the page covers
- **The problem:** products that conflict (e.g. retinol + AHA), misleading "clean" labels, hormonal breakout cycles, ignoring UV and humidity, unreliable progress photos, and repeat buying of products that already failed
- **How SkinIQ works:** a routine scanner that flags ingredient conflicts with red / amber / green severity, a daily "skin forecast" based on UV and humidity, and the other core features
- **Waitlist sign-up:** "Reserve My Spot", free to join

## How it's built
- A single, dependency-free `index.html` (HTML, CSS, vanilla JavaScript)
- Mobile-first layout, tuned for readability on small screens
- Waitlist form posts to a **Google Apps Script** web app that writes sign-ups to Google Sheets, so no backend is needed

## Run locally
Open `index.html` in a browser, or serve it:
```bash
python3 -m http.server 8000
```

## License
MIT, see [LICENSE](LICENSE).
