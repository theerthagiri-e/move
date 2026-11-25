# Move — hourly movement breaks for people who sit all day

A free, single-file web app that reminds you every hour to move. It guides you through short desk stretches, a home strength circuit, bike or walk sessions, optional heel care, and a simple South Indian diet tracker.

**Live demo:** https://theerthagiri-e.github.io/move/

Built in one evening with [Claude](https://claude.ai) as a personal tool. Shared in case it helps you too.

## What it does

- **Hourly break alarm:** sound, desktop notification and a flashing tab title. You can snooze or skip.
- **4–5 minute breaks:** eye reset (20-20-20), chin tucks, a rotating mobility stretch, plus strength moves on strength days.
- **Weekly structure:** Mon/Wed/Fri strength (circuit spread across the day's breaks), Tue/Thu/Sat continuous bike or walk session, Sun rest.
- **Progression by week:** weeks 1–2 are easier, weeks 3–4 add rounds, week 5+ adds dumbbells (optional) and interval cues.
- **Animated stick-figure guides** with form cues for all 21 exercises. Everything is low-impact, with no jumping.
- **Optional heel routine** (plantar fasciitis): morning towel stretch, night bottle roll.
- **Diet tab:** protein tracker with common Indian foods, water count, daily checklist, hotel-meal counter, and reminders at 5:30 PM, 8:45 PM and 11 PM.
- **Progress:** 7-day history and a weekly weight and waist chart.

## Privacy

- No account, no server, no analytics, no external requests.
- Everything is stored in your browser's `localStorage` and never leaves your device.
- Use **Settings → Export backup** to save a JSON copy.

## Run it

- **Online:** open the GitHub Pages link above.
- **Offline:** download `index.html` and open it in Chrome or Edge. The sound works everywhere. For desktop notifications, serve it locally:

  ```
  python -m http.server 8765
  # then open http://localhost:8765/
  ```

Keep the tab open and the computer awake. A browser can't alarm while the machine is asleep. Your data is tied to the address you open it from, so stick to one.

## Disclaimer

This is not medical advice. Exercises, protein and water targets are general starting points and may not suit you. If you have heart, blood pressure, diabetes, kidney or joint conditions, are pregnant, or are new to exercise, check with a doctor first. Stop any movement that causes sharp pain, dizziness or chest discomfort.

## Licence

MIT. Use it, change it, share it.
