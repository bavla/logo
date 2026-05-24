# <img src="../docs/logo.png" width=80 alt="logo"/> einstein

<hr />

V članku Smith, David; Myers, Joseph Samuel; Kaplan, Craig S.; Goodman-Strauss, Chaim: [An aperiodic monotile](https://escholarship.org/uc/item/3317z9z9). Combinatorial Theory (2024) Volume 4, Issue 1, #6 je bil opisan tlakovec "**einstein**".
21. in 22. maja 2026 sem v logu razvil podporo za opis prikazov tlakovanj s prikazom na zaslonu pa tudi opisom v Postscriptu in SVG.

Rešitev sem preizkusil v tolmaču [FMSlogo](../info.md).  Primer tlakovanja iz članka 

<img src="./tilingXY.png" width=500 alt="einstein"/>

sem opisal v programu [einsteinEx1.lgo](../code/einsteinEx1.lgo). V FMSlogu naprej naložimo (z izbiro file/load) knjižnico  [einstein](https://github.com/bavla/logo/blob/main/code/einstein.lgo) in nato še sam program einsteinEx1.lgo. Sliko dobimo na zaslonu. Pri sestavljanju opisa si lahko pomagamo s prikazom tlakovca einstein v [različnih legah](./einsteinTiles.pdf).

Dobljeno sliko lahko obenem tudi shranimo ali v obliki Postscript ali v obliki SVG. Za PS je to prikazano v programu [einsteinEx1PS.lgo](../code/einsteinEx1PS.lgo). Za prikaz, v FMSlogu naprej naložimo (z izbiro file/load) knjžnici  [Logo2PS](https://github.com/bavla/logo/blob/main/code/Logo2PS.lgo) in [einstein](https://github.com/bavla/logo/blob/main/code/einstein.lgo) ter nato še sam program einsteinEx1PS.lgo. Sliko dobimo na zaslonu in na datoteki einsteinEx1.eps. To si lahko ogledamo v Acrobat readerju in shranimo v obliki [PDF](./einsteinEx1g.pdf).

Skoraj enak program [einsteinEx1SVG.lgo](../code/einsteinEx1SVG.lgo) pa shrani sliko na datoteko v obliki [SVG](./einsteinEx1.svg).

Če ne želimo šestkotniške mreže, zakomentiramo (predenj postavimo podpičje ; ) ukaz  grid  v ukazu  runPS oziroma  runSVG. [PDF](./einsteinEx1.pdf)

  * Batagelj V.: [Logo to Postscript](https://github.com/bavla/logo/blob/main/docs/1997-Batagelj-Logo_to_Postscript.pdf). Eurologo, 1997.
  * Batagelj V.: [Logo to SVG](https://github.com/bavla/logo/blob/main/docs/2001-Batagelj-Logo_to_SVG.pdf). Eurologo, 2001.
   
<hr />

[logo](../README.md)

