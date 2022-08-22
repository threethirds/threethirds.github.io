---
title: "DI kokybės kontrolei: PET butelių gamyba"
description: "Mes sukūrėme sensorių PET butelių kokybės matavimui ir realaus laiko algoritmą kokybės palaikymui"
---

# Realaus laiko butelių pūtimo kontrolės sistema

## Kliento iššūkis

[FlexBlow](https://flexblow.com/) yra MVĮ, kurios specializacija yra **PET butelių gamyba ir įranga**. Pagrindinis įmonės produktas yra butelių pūtimo mašina, kurią galima lanksčiai perkonfigūruoti, kad būtų galima gaminti įvairių formų butelius. Šiuo metu, siekiant išlaikyti butelių kokybę, visą gamybos procesą turi prižiūrėti žmogus ir koreguoti pūtimo parametrus. Bendrovė "Flexblow" su mumis sudarė sutartį dėl **autonominės butelių kokybės kontrolės sistemos** sukūrimo ir įdiegimo.

## Mūsų sprendimas

Projektui reikėjo trijų komponentų: valdymo jutiklio, valdymo algoritmų ir techninės įrangos, skirtos kokybės kontrolei gamyboje vykdyti.

- **Kontrolės jutiklis.** Paaiškėjo, kad pradinis "FlexBlow" kokybės jutiklis neatitinka užduoties, todėl ėmėmės vadovauti projektuojant ir įsigyjant naujo jutiklio dalis. Kartu su trečiosios šalies elektronikos paslaugų teikėja "Elskaifa" sukūrėme nestandartinį nebrangų jutiklį, galintį atlikti iki 1 mln. tikslių matavimų per sekundę.
- **Valdymo programinė įranga.** Sukūrėme realaus laiko uždarojo ciklo MPC tipo valdymo sistemą, kuri sklandžiai integruojama į "FlexBlow" mašinas ir tiesiogiai komunikuoja su Siemens S7 mikrovaldikliu.
- **Techninė įranga.** Kartu su "FlexBlow" komanda dirbome kurdami tokią techninės įrangos konfigūraciją, kuri be pakeitimų būtų integruota į esamą įrangą.

## Poveikis

- Mūsų sistema buvo sėkmingai ištestuota gamybos metu FlexBlow gamykloje ir šiuo metu ruošiama nuolatiniam naudojimui.
