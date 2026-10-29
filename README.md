# Sanskritam Daily

A one-page website for a daily Sanskrit course. A scheduled task posts one lesson a day.

- `index.html` – the site (no build step).
- `data/day-NNN.json` – one lesson per day: video, explanation, examples, words, quiz (with answers) and the audio path.
- `data/latest.json` – the newest published day, e.g. `{"day": 2, "updated": "2026-10-30"}`.
- `data/progress.json` – quiz results the teacher recorded after the learner replied in the chat; shown on every device.
- `audio/day-NNN.mp3` – listen-and-repeat audio for each day.

Published with GitHub Pages. The `gh-pages` branch mirrors `main`; both are updated on every post.
