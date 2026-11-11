# Pancerny Kanion – aplikacja na iPhone (PWA)

Gra w jednym pliku `index.html` + manifest, service worker (tryb offline) i ikony.

## Publikacja na GitHub Pages
1. Zaloguj się na github.com → **New repository** → nazwa np. `pancerny-kanion`, ustaw **Public** → **Create repository**.
2. Kliknij **uploading an existing file** (albo **Add file → Upload files**) i przeciągnij **zawartość** tego folderu: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` i cały folder `icons`. Kliknij **Commit changes**.
3. **Settings → Pages** → *Source*: **Deploy from a branch** → *Branch*: **main**, folder **/ (root)** → **Save**.
4. Po 1–2 minutach gra jest pod adresem `https://TWOJA-NAZWA.github.io/pancerny-kanion/`.

## Instalacja na iPhonie
1. Otwórz ten adres w **Safari**.
2. **Udostępnij** (kwadrat ze strzałką) → **Do ekranu początkowego** → **Dodaj**.
3. Uruchamiaj grę z ikony – działa na pełnym ekranie i bez internetu.

## Aktualizacja gry
Wgraj nowy `index.html` do repozytorium (Add file → Upload files → Commit). Po minucie uruchom aplikację z internetem – pobierze nową wersję (czasem trzeba ją zamknąć i otworzyć drugi raz).
Jeśli zmienisz ikony lub `sw.js`, podbij w `sw.js` numer `VERSION` (np. `kanion-v2`).
