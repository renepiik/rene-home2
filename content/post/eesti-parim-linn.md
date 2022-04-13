---

title: Eesti parim linn
slug: eesti-parim-linn
author:
date: '2022-04-04'
categories:
  - Varia
draft: true

---

Arvestades, et aina rohkem on Eestisse tekkinud kaugtöö võimalusi, eriti informaatika valdkonnas, tuli huvi uurida, millises linnas on kõige optimaalsem elada.
Arvesse tuleks võtta seda, kui kiirelt saab sellest linnast kõigisse teistesse (kaalutud suuremate linnade suunas), kinnisvara hindu, rahvaarvu, keskmist palka jm.

## Arvutus

Eestis on 47 linna, mistõttu kasutan linnade tähistamiseks indeksit $i\in I = \{ 0,\dots,46 \}$.
Tähistame keskmist ruutmeetri hinda (kinnisvara hind) tähega $r_i$, keskmist palka tähega $k_i$, linna $L_i$ (ajalist) kaugust linna $L_j$ sümboliga $d(L_i, L_j)$ ja viimaks rahvaarvu tähega $p_i$.
Lisaks tähistame kõigi linnade keskmise
 - ruutmeetri hinna $\overline{r}$;
 - keskmise palga $\overline{k}$;
 - rahvaarvu $\overline{p}$;
 - kauguse teistest linnadest $\overline{d}$.
Linna indeksiga $i$ üldine skoor avaldub kujul
\[
S_i = \frac{k_i p_i \overline{r} \overline{dd}}{\overline{k} \overline{p} r_i \sum_{j\in I} d(L_i,L_j) }.
\]
Keskmine palk mängib siin positiivset rolli, sest see peaks näitama piirkonna üldist heaolu taset.
Mida kõrgem keskmine palk, seda paremad lasteaiad ja koolid, seda rohkem väikeettevõtjaid, seda paremad restoranid ja baarid jne.


