# Fajt Klub – strona na GitHub Pages

Pliki: `index.html` (strona), `data.json` (zawodnicy i walki), ten plik.

## Jednorazowe uruchomienie (ok. 10 minut)

1. Załóż darmowe konto na https://github.com (zarejestruj się).
2. Kliknij **+** w prawym górnym rogu → **New repository**. Nazwa: `fajt-klub`, widoczność **Public**, kliknij **Create repository**.
3. Na stronie nowego repozytorium kliknij **uploading an existing file**, przeciągnij `index.html` i `data.json` (README możesz pominąć), kliknij **Commit changes**.
4. Wejdź w **Settings** → **Pages**. W polu „Branch” wybierz `main` i `/ (root)`, kliknij **Save**.
5. Po 1–2 minutach u góry strony Pages pojawi się adres: `https://TWOJA-NAZWA.github.io/fajt-klub/`. To jest link dla wszystkich, bez logowania.

## Jak dodawać zawodników i walki

1. Otwórz stronę → zakładka **Logowanie** → wpisz hasło admina.
2. Dodaj zawodników, walki, wyniki, liczby osób. Widzisz to tylko u siebie.
3. Kliknij **Pobierz data.json**.
4. W repozytorium na GitHubie kliknij **Add file → Upload files**, przeciągnij nowy `data.json` (ta sama nazwa, zastąpi stary), **Commit changes**.
5. Po minucie wszyscy widzą zmiany po odświeżeniu strony.

Jeśli zmieniłeś coś na komputerze, a potem chcesz zacząć od wersji z GitHuba, kliknij **Wyczyść szkic**.

## Własna domena (opcjonalnie)

Settings → Pages → **Custom domain**, wpisz domenę i u rejestratora domeny dodaj rekord DNS według podpowiedzi GitHuba (rekord CNAME na `TWOJA-NAZWA.github.io`).

## Ważne ograniczenia

- Hasło admina jest w kodzie strony i zamyka tylko panel. Prawdziwą ochroną jest to, że zmiany trafiają na stronę dopiero, gdy Ty wgrasz `data.json` na swoje konto GitHub. Nikt inny tego nie zrobi.
- Obstawianie to punkty zapisane w przeglądarce gracza (jeden głos na walkę na przeglądarkę). Nie ma wspólnych głosów ani blokady po IP. Liczby osób na zawodników wpisujesz ręcznie w zakładce Obstawianie.
- Żeby zmienić hasło, trzeba przeliczyć jego skrót w `index.html` (stała `HASH` i liczba w funkcji `okPw`). Poproś mnie, a podam gotowe wartości.
