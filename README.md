# Rodzina na Plus — publiczna polityka prywatności

Ten katalog jest przygotowany jako **minimalny publiczny artefakt**, który można opublikować osobno od prywatnego repozytorium aplikacji.

## Co zawiera

- `index.html` — publiczna wersja polityki prywatności gotowa do hostowania

## Rekomendowany model publikacji

- główne repo aplikacji: **GitHub Private**
- osobne repo tylko dla polityki prywatności: **GitHub Public**
- hostowanie polityki: **GitHub Pages**

## Szybki scenariusz

1. utwórz osobne publiczne repo, np. `rodzina-na-plus-privacy`
2. wrzuć do niego tylko zawartość tego katalogu
3. włącz GitHub Pages dla gałęzi `main`
4. użyj wygenerowanego URL jako publicznej polityki prywatności w Google Play Console

## Uwaga

Nie publikuj całego repo aplikacji, jeśli projekt ma pozostać prywatny. Publiczne powinno być wyłącznie repo lub hosting zawierające samą politykę prywatności.

## Synchronizacja przy wydaniach

Przy każdej publikacji aplikacji:

1. zaktualizuj `docs/PRIVACY_POLICY.md` w prywatnym repo,
2. przenieś aktualną wersję HTML z tego katalogu do publicznego repo `rodzina-na-plus-privacy`,
3. sprawdź publiczny URL `https://mmalmon.github.io/rodzina-na-plus-privacy/`,
4. upewnij się, że treść zgadza się z dokumentami `docs/DATA_SAFETY.md` i `docs/PLAY_CONSOLE_VALUES.md`.

