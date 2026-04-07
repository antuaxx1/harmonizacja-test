# Harmonizacja – repo pod Netlify

To jest gotowa statyczna strona do badania harmonizacji melodii przygotowana pod **Netlify Forms**.

## Co jest w środku
- `index.html` – główna strona z formularzem Netlify
- `assets/styles.css` – styl
- `assets/app.js` – logika formularza
- `audio/` – tutaj wrzucasz pliki MP3
- `pdf/` – tutaj wrzucasz pliki PDF

## Jak dodać pliki
Wrzucaj pliki dokładnie tak:
- `audio/melodia1.mp3`
- `audio/melodia2.mp3`
- ...
- `audio/melodia10.mp3`

- `pdf/melodia1.pdf`
- `pdf/melodia2.pdf`
- ...
- `pdf/melodia10.pdf`

## Jak uruchomić na Netlify z repo
1. Zaloguj się do Netlify.
2. Importuj repo `antuaxx1/harmonizacja-test`.
3. Build command zostaw puste.
4. Publish directory ustaw na `.`
5. Deploy.

## Gdzie będą odpowiedzi
Po deployu Netlify wykryje formularz `harmonization-survey`.
Odpowiedzi znajdziesz w panelu:
- Site configuration / Forms
- lub Forms / Submissions

## Co zapisuje każde zgłoszenie
- `respondent_type`
- `session_id`
- `submitted_at`
- odpowiedzi dla melodii 1–10
- komentarze dla melodii 1–10
- `submission_summary`
- `submission_json`

## Ważne
Jeśli po deployu zmienisz strukturę formularza, zrób nowy deploy, żeby Netlify ponownie wykryło pola.
