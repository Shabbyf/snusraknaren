# Snusräknaren

En liten webbapp för att sluta snusa eller röka. Tryck **Avstod** när du låter bli och **Tog en** när du tar en. Appen räknar vad du sparar, mäter pauserna mellan varje och belönar längre pauser med nivåer, rekord och streaks.

- Ingen inloggning. All data sparas på telefonen (IndexedDB).
- Fungerar offline och kan installeras på hemskärmen.
- Export och import av historiken som JSON under inställningarna.

## Installera
- **iPhone:** öppna sidan i Safari → Dela → Lägg till på hemskärmen.
- **Android:** öppna sidan i Chrome → ⋮ → Installera app.

## Filer
- `index.html` – hela appen (HTML, CSS, JS, inga beroenden)
- `manifest.json` – appnamn, ikoner, helskärm
- `sw.js` – service worker för offline
- `icons/` – appikoner
