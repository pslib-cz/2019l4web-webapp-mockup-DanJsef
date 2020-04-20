# Hledání min

## Pravidla

- odkrýt všechna políčka bez min
- klepnutí na políčko odkryje pole
- pokud hráč klikne na políčko s minou, prohrál
- pokud políčko neobsahuje minu, objeví se číslo které označuje počet min v okolí
- pokud v okolí políčka není mina odkryjí se všechna políčka v okolí, až po po políčka která v okolí mají minu

## Ovládání

- levé tlačítko: odkrévá políčka
- pravé tlačítko: označuje políčka praporkem, případně praporek z políček opět odstraňuje

## Struktura

- HTML je složeno ze dvou tabulek:

1. table.all - tvoří rámeček a hlavičku s ukazatelem počtu min a času řešení
2. table.field - tvoří hrací pločíka

## Dostupné classy pro hrací pole

- closed - neodkryté pole
- found - nalezená mina (vlaječka)
- mine_exploded - mina, která explodovala
- mine_show - odkryté ostatní miny
- uncover - odkryté pole
