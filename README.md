# Taiwan Night Market Chinese · 台灣夜市華文

A beginner Mandarin web app themed around Taiwan's night markets — built for teaching a study partner.

- **Find the Four Tones** — pitch-contour cards with Taiwan-voice audio
- **Greetings & courtesy**, **Numbers & ordering**
- **Food vocabulary** — night-market snacks, signature dishes, drinks & desserts, each with pinyin, English, and a "Say it" pronunciation tip
- **Ordering options** — sugar (甜度), ice (冰塊) and spice (辣度) levels, the real Taiwan way
- **My Vocabulary** — a Kotoba-style spaced-repetition trainer: add your own words and review them daily on a memory curve
- Streak, daily goal, points, favourites

## Run it

Just open `index.html` in a browser, or visit the GitHub Pages site.

It's a single self-contained `index.html` (HTML/CSS/JS) plus the `assets/` illustrations. The Three.js lantern scene loads from a CDN (needs internet); it falls back to a warm gradient offline. Audio uses the browser's built-in Chinese voice (a Taiwan `zh-TW` voice is preferred).

## Data

Per-learner progress (streak, points, words, custom vocabulary) is saved in the browser and synced to a Supabase table so the teacher can see it. The embedded Supabase URL + publishable key are public by design (an anon/publishable key). The progress table uses a permissive policy suitable for a small private class.
