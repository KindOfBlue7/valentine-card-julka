## Valentine Card – GitHub Pages

Static walentynkowa stronka z pytaniem:

> **Czy zostaniesz moją walentynką???**

Po kliknięciu **Tak** znika wybór i pojawia się główny GIF w środku, a wokół karty pojawiają się dodatkowe GIFy.

Pliki GIF powinny znaleźć się w folderze `static`:

- **`static/valentine1.gif`** – główny GIF w środku
- **`static/valentine2.gif`**
- **`static/valentine3.gif`**
- **`static/valentine4.gif`**
- **`static/valentine5.gif`**

Jeśli nazwy plików będą inne, zaktualizuj atrybuty `src` w `index.html`.

### Jak uruchomić GitHub Pages

1. Utwórz nowe repozytorium na GitHub i wrzuć do niego zawartość tego folderu.
2. Upewnij się, że główna gałąź nazywa się **`main`** (lub zmień ją w workflow w `.github/workflows/deploy.yml`).
3. W repo na GitHub:
   - Wejdź w **Settings → Pages**.
   - Ustaw **Source** na **GitHub Actions**.
4. Przy każdym `git push` na `main` workflow `Deploy to GitHub Pages` zbuduje i wdroży stronę.

