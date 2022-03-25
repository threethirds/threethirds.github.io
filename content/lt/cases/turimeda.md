# EndoArt: Aortos aneurizmos segmentavimo ir stebėjimo sistema

## Kliento iššūkis

[Turimeda](https://www.turimeda.com/) yra ankstyvosios stadijos MedTech startuolis, kuris nori matuoti ir stebėti vidaus organus be varginančių rankinio ženklinimo pastangų. Pirmasis jų produktas skirtas *abdominalinės aortos aneurizmai* - gyvybei pavojingai būklei, kai aorta, pagrindinė kraujagyslė, išsiplečia ir gali plyšti. Turimeda siekia sukurti priemonių rinkinį, kuris padėtų gydytojams stebėti būklės vystymąsi laikui bėgant pagal reguliariai atliekamas kompiuterinės tomografijos nuotraukas. Mūsų užduotis buvo sukurti algoritmą, kuris iš kompiuterinės tomografijos nuotraukų apskaičiuotų tikslius aortos matmenis.

## Mūsų sprendimas

- Sukūrėme *PyTorch* pagrįstą **gilųjį neuroninį tinklą**, skirtą aortos aneurizmai segmentuoti, kurį apmokėme savo vidinėje debesijos infrastruktūroje.
- Sukūrėme **specializuotus 3D algoritmus**, kurie rekonstruotos aortos 3D tinklelyje randa orientaciniams taškus ir išmatuoja reikiamus dydžius.
- Savo algoritmą įdiegėme kaip žiniatinklio paslaugą debesijos infrastruktūroje, taip pat supakavome jį kaip atskirą *Docker* konteinerį skirtą vietiniam diegimui.

## Poveikis

- Per 12 mėnesių sukūrėme prototipą, pasiekėme standartinį šios srities **Dice indeksą 0,9**, atlikdami nematytų pacientų kompiuterinės tomografijos tyrimų testą.
- Šiuo metu prototipas testuojamas trijose Lietuvos nacionalinėse ligoninėse, siekiant pasirengti klinikiniams tyrimams.