# Nihongo Scan (free version)
Photo/paste Japanese text -> furigana, tap-for-meaning, word list, quizzes, flashcards.
No server, no API key. OCR: Tesseract.js, words+readings: Kuromoji, meanings: JMdict.

## Setup
1. Download `jmdict-eng-common-*.json.zip` from https://github.com/scriptin/jmdict-simplified/releases (latest release).
2. Unzip it, rename the JSON to `jmdict.json`, put it in the `data/` folder.
3. Push to GitHub, then Settings -> Pages -> Deploy from branch `main` (root).
Test locally: `python3 -m http.server` in this folder, open http://localhost:8000

Dictionary: JMdict (c) EDRDG, CC BY-SA 4.0.
