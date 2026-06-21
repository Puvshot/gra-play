# Gra Play

Publiczne repozytorium do uruchamiania testowej wersji gry z projektu `Puvshot/gra`.

## Adres gry

Docelowy adres po włączeniu GitHub Pages:

```text
https://puvshot.github.io/gra-play/
```

## Jak włączyć GitHub Pages

W repozytorium `Puvshot/gra-play`:

1. Wejdź w `Settings`.
2. Wejdź w `Pages`.
3. W sekcji `Build and deployment` wybierz `Deploy from a branch`.
4. Wybierz branch `main` oraz folder `/(root)`.
5. Kliknij `Save`.

Po chwili GitHub powinien opublikować stronę pod adresem:

```text
https://puvshot.github.io/gra-play/
```

## Ważne

To repo zawiera publiczny build testowy, nie prywatne źródła projektu.

Aktualna wersja jest statycznym playable PoC odwzorowującym minimalną pętlę gry:

```text
zgłoszenie → wybór jednostki → wynik interwencji
```

Docelowo build powinien być generowany automatycznie z prywatnego repo `Puvshot/gra`, ale to wymaga dodatkowej konfiguracji tokena albo innego mechanizmu publikacji między repozytoriami.
