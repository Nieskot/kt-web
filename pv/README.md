# Dokumentacja robocza wiki Krainy Twórców

To jest punkt wejścia do dokumentacji. Jeśli instrukcja w innym pliku przeczy temu dokumentowi lub `JAK-EDYTOWAC.md`, nie stosuj jej w ciemno — sprawdź datę i zgłoś rozbieżność.

## Pliki bieżące — używaj ich do edycji

- **`JAK-EDYTOWAC.md`** — główna, aktualna procedura edycji.
- **`SZABLONY-WPISOW/ODCINEK.js.txt`** — wzór rekordu odcinka do `public/js/wiki-search-index.js`.
- **`SZABLONY-WPISOW/ROZDZIAL.js.txt`** — wzór rekordu rozdziału.
- **`SZABLONY-WPISOW/SEZON.js.txt`** — wzór rekordu sezonu.
- **`SZABLONY-WPISOW/WZORY-WPISOW-DO-INDEKSU.md`** — porównanie pól i relacji rekordów.
- **`SZABLONY-HTML/`** — szablony stron, które trzeba skopiować tylko przy tworzeniu nowej fizycznej podstrony.
- **`SZABLON-OPISU-ODCINKA.md`** — materiał pomocniczy do opracowania opisu; nie jest źródłem danych wiki.
- **`../tools/validate-wiki.js`** — kontrola techniczna przed publikacją.
- **`../tools/generate-catalog.js`** — generuje statyczny katalog odcinków i listę haseł wyszukiwarki.
- **`../tools/generate_sitemap.py`** — generator mapy witryny.

## Zasady

1. Źródłem danych wiki jest `public/js/wiki-search-index.js`.
2. Mechanizm prezentacji danych znajduje się w `public/js/catalog-sync.js`.
3. `public/` to zawartość publikowanej strony; `pv/` to dokumentacja robocza; `tools/` to narzędzia developerskie.
