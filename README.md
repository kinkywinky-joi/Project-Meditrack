# MediTrack

Website for **MediTrack**, a medication companion (mobile app and smart medicine box) that helps elderly patients take the right medicine at the right time and keeps their families informed.

*Track. Remind. Stay healthy.*

## What is on the page

- Hero with an interactive phone mock-up
- The problem, with a cited WHO adherence statistic
- Features, each with a short explanation pop-up
- **Live demo**: a sped-up clock runs a day of doses. The patient's phone reminds (text, voice and beep, in English, Hindi or Marathi), doses can be taken or skipped, and the family's phone receives missed-dose, refill and daily-summary messages. Medicines can be added, removed and refilled.
- Weekly pill-box planner
- How it works, About, FAQ and a contact form
- Light and dark themes, responsive down to phone width, reduced-motion support

## Project structure

```
index.html     page structure (the demo is marked LIVE DEMO SECTION)
styles.css     design tokens at the top, demo styles marked "Live demo"
script.js      page behaviour and the liveDemo function
images/
  logo.png     MediTrack logo
```

No build step and no dependencies. Fonts (Fraunces, Manrope) load from Google Fonts.

## Run locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

then visit http://localhost:8000.

## Publish with GitHub Pages

1. Push this repository to GitHub.
2. Open **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.

## Notes

- The contact form validates in the browser only. Connect it to a backend or a form service to receive submissions.
- The demo runs entirely in the browser. Nothing is stored or sent. Voice alerts use the device's built-in speech, so a device without a Hindi or Marathi voice shows the text only.
- Statistic: WHO, *Adherence to Long-Term Therapies: Evidence for Action*, 2003.

## Credits

Student venture from DPGU SPR, Pimpri, Pune, developed under the Wadhwani Foundation venture programme.
