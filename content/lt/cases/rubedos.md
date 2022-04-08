# Padėklų aptikimo ir lokalizavimo sistema

![Pallet detection results](/images/strato.png)

## Kliento iššūkis

[Rubedos](https://rubedos.com) yra MVĮ, kurios specializacija - **mobilioji robotika**. 2021 m. ji pradėjo kurti autonominio krautuvo platformą, kurios tikslas - autonomiškai nustatyti paletės buvimo vietą pakrovimo zonoje ir perkelti ją į tikslinę vietą. Bendrovė "Rubedos" su mumis sudarė sutartį, kad sukurtume padėklų aptikimo ir lokalizavimo algoritmus, kurie pagal stereovaizdą ir LIDAR įvesties duomenis nustatytų padėklus, jų orientaciją ir vietą.

## Mūsų sprendimas

- Padėklų aptikimo sistema pagrįsta gatavų **konvoliucinių neuroninių tinklų**, ansambliu, pritaikytu prie "Rubedos" GPU varomos VIPER stereokameros apribojimų. Sistema gali aptikti įvairius padėklus iš įvairių kampų, atstumų ir apšvietimo sąlygų.
- Padėklų vietos nustatymui sukurėme specialią klasikinė mašininės regos sistemą, kuri sujungia **LIDAR** ir **stereo kameros** duomenų srautus. Sistema gali sėkmingai dirbti su daugelio tipų padėklais ir užstojimais.
- Sprendimas įdiegtas keliose sandėlio vietose ir krautuve, o su krautuvo valdymo paketu (kurį sukūrė "Rubedos") bendrauja standartiniais robotų operacinės sistemos (ROS) protokolais.
- Mes valdėme visą algoritmų kūrimo apimtį - nuo **duomenų rinkimo ir anotavimo** paslaugų subrangos iki algoritmų **mokymo debesyje** ir diegimo "Rubedos" infrastruktūroje.

## Poveikis

- Per **penkis mėnesius** pristatėme visą padėklų aptikimo ir lokalizavimo algoritmų rinkinį.
- Naudojant mūsų sprendimą, "Rubedos" autonominis krautuvo prototipas sėkmingai **įveikė bandymus** didelės logistikos įmonės sandėlyje.
- Tęsiame bendradarbiavimą, siekdami iki 2022 m. pabaigos **įdiegti pirmąją versiją** dideliame logistikos centre.