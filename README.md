# Kiaan's Gujarati Quest

A static, account-free Gujarati practice game made from Amit's supplied Gujarati practice workbook for Kiaan.

## Games
- Quick quiz: 10 questions, category selection.
- Match lab: pair four terms and translations.
- Type it out: Romanized Gujarati recall, forgiving capitalization, whitespace and punctuation.
- Color switch: male, female and neutral color forms as recorded in the workbook.
- Time travel: past, present and future forms from the workbook table.
- Word atlas: reference for phrases, colors, body parts, verbs, relatives, numbers, days, animals and names, plus grammar notes.

Points and streaks are kept only in the browser's local storage. There are no accounts, analytics, cookies, ads, or external network dependencies. A small service worker caches the app for later offline use after the first successful visit.

Source transcription is in `content.json`, generated browser-ready copy in `content.js`. Some workbook entries contain unusual spellings or conflicting forms. Those are generally preserved rather than silently standardized; the quiz's present-tense forms follow the workbook verb table literally.

## Run

Serve this directory with any static HTTP server, for example `python3 -m http.server 8787`, then open http://localhost:8787/.
