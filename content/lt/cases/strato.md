# Modulinių namų planavimas

## Kliento iššūkis

[strato.homes](https://strato.homes/) yra novatoriškas startuolis, kuris projektuoja ir stato **modulinius namus** vos per tris mėnesius nuo įsigijimo iki įsikėlimo. Dalis jų vizijos - **DI planuotojas**, kuris sukurtų išplanavimo brėžinius pagal pirkėjo pasirinkimus ir jų modulinės sistemos nustatytus inžinerinius apribojimus. Mums buvo pavesta sukurti šio dirbtinio intelekto planuotojo prototipą.

## Mūsų sprendimas

Mūsų sprendimą sudaro trys pagrindiniai komponentai:

1. Grindų plano generavimo algoritmas, kuriame planavimas formuluojamas kaip **tiesinio programavimo** ir **apribojimų programavimo** uždavinys ir sprendžiamas naudojant *coin-or* ir *ortools* įrankius. Planavimo apribojimus nustatėme glaudžiai bendradarbiaudami su strato.homes architektais, todėl mūsų algoritmas gali generuoti racionalius planus tūkstančiams skirtingų konfigūracijos variantų. Taip pat tyrinėjome skatinamojo mokymosi ir sąlyginio variacinio kodavimo metodus, tačiau nustatėme, kad šiame etape jie yra nepraktiški.
2. Didelio intensyvumo skaičiavimams skirta **debesijos infrastruktūra**.
3. **Žiniatinklio paslauga** ir **vartotojo sąsaja**, skirta rezultatams tirti.

## Poveikis

- Per **7 mėnesius** sukūrėme veikiantį planuoklio prototipą, todėl strato.homes galėjo greitai įvertinti šio metodo potencialą.
- Padrąsinta mūsų prototipo, strato.homes toliau plečia funkcijų rinkinį ir tikimės, kad netrukus planuotojas bus naudojamas strato.homes klientų.