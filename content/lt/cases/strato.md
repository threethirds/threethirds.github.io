# Modulinių namų planavimas

{{< rawhtml >}}
<video controls autoplay muted playsinline>
    <source src="/video/strato.mp4" type="video/mp4">
    <img src="/images/strato.png" alt="Strato UI">
</video>
{{< /rawhtml >}}

## Kliento iššūkis

[strato.homes](https://strato.homes/) yra novatoriškas startuolis, kuris projektuoja ir stato **modulinius namus** vos per tris mėnesius nuo įsigijimo iki įsikėlimo. Dalis jų vizijos - **DI planuotojas**, kuris sukurtų išplanavimo brėžinius pagal pirkėjo pasirinkimus ir jų modulinės sistemos nustatytus inžinerinius apribojimus. Mums buvo pavesta sukurti šio dirbtinio intelekto planuotojo prototipą.

## Mūsų sprendimas

Mūsų sprendimą sudaro trys pagrindiniai komponentai:

1. Grindų plano generavimo algoritmas, kuriame planavimas formuluojamas kaip **tiesinio programavimo** ir **apribojimų programavimo** uždavinys. Planavimo apribojimus nustatėme glaudžiai bendradarbiaudami su strato.homes architektais, todėl mūsų algoritmas gali generuoti racionalius planus tūkstančiams skirtingų konfigūracijos variantų.
2. Didelio intensyvumo skaičiavimams skirta **debesijos infrastruktūra**.
3. **Žiniatinklio paslauga** ir **vartotojo sąsaja**, skirta rezultatams tirti.


## Poveikis

- Per **7 mėnesius** sukūrėme veikiantį planuoklio prototipą, todėl strato.homes galėjo greitai įvertinti šio metodo potencialą.
- Padrąsinta mūsų prototipo, strato.homes toliau plečia AI planuotojo pavadinto [strato.vip](https://strato.vip) funkcijų rinkinį.