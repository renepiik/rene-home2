---
title: Ülesanne loenduvuse aksioomidest
author:
date: '2021-12-14'
categories:
  - Topoloogia
tags:
  - Topoloogia
---

Hakkasin kordamise mõttes topoloogiliste omaduste konspekti ülesandeid otsast lahendama. Esimese peatüki esimene ülesanne kõlab seal järgmiselt: "Tõestada, et kui topoloogia mingi baas on loenduv, siis selle topoloogia iga baas sisaldab loenduva baasi."

Esialgu tundus mulle, et selle lause tõestus peaks olema küllaltki lihtne. Tuleks definitsioonidele vaid otsa vaadata, neid natuke kohendada ja lahenduskäik võiks end juba ilmutada. Paraku nii ei juhtunud. Üritasin kaks-kolm päeva seda ülesannet ilma välise abita lahendada ega jõudnud kuhugi. 

Lause tõestus oli aga piisavalt huvitav, et tahtsin seda ka teistega jagada. Praktikumis tehtud märkmete ja ühe ainet juba võtnud tudengi abiga saime ülesandest lõpuks jagu.

**Esialgne plaan**

Ülesande tekstis pole eriti paljust kinni haarata. Meile öeldakse vaid, et antud topoloogiline ruum rahuldab teist loenduvuse aksioomi. Seega oli minu esimene mõte, et ehk võiks tekitada vastuolu esimese loenduvuse aksioomiga, mis väidab, et igal ruumi punktil leidub loenduv baas. Teatavasti järeldub esimene aksioom teisest. Paraku ei kandnud see mõttekäik vilja. 

Segadust tekitas minu jaoks ka see, et üldise topoloogia raames kutsutakse ülimalt loenduvaid hulki lihtsalt loenduvateks. Kui ma üritasin hakata tõestama, et mingil punktil ei leidu loenduvat baasi, arvasin pikalt, et loenduvuse asemel peab leiduma ülimalt lõplik baas. Tegelikult tähendaks see hoopis, et vähim baas mis mingil punktil leidub on suurem kui loenduv (näiteks kontiinumi võimsusega).

**Lahendus**

Vaatleme topoloogilist ruumi $(X, \tau)$, millel leidub loenduv baas $\mathfrak{B} = \{ B_{n}:n\in \mathbb{N} \}$. Fikseerime suvalise topoloogilise baasi $\mathfrak{C}$ ja näitame, et selles sisaldub loenduv baas.

Me näitame seda nii, et eraldame baasist $\mathfrak{C}$ mingi alamkogumi, mille elemendid sobituvad seose $\subset$ järgi baasi $\mathfrak{B}$ elementide vahele. Kuna baasil $\mathfrak{B}$ on vaid loenduv arv liikmeid, siis peab ka selles $\mathfrak{C}$ alamkogumis nii olema.

Selleks defineerime esialgu indeksite hulga
$$
I=\{ (m,n)\in\mathbb{N}^{2}:\exists C\in\mathfrak{C},\hspace{0.2cm} B_{m}\subset C\subset B_{n} \}.
$$ 
Kuna $\mathbb{N}^{2}$ on loenduv, siis ka selle alamhulk $I$ on loenduv. (Räägime siin taas ülimalt loenduvusest.) Moodustame selle järgi loenduva hulga 
$$
\mathfrak{C}^* = \{ C_{mn}:(m,n)\in I \}\subset\mathfrak{C}
$$ 
ja näitame, et $\mathfrak{C}^*$ on ruumi $X$ baas.

Fikseerime suvalise lahtise hulga $U\subset X$, siis peab baasi definitsiooni järgi leiduma mingi $B_{n}\in\mathfrak{B}$ nii, et $B_{n}\subset U$. Kuna $\mathfrak{C}$ on baas ja $B_{n}$ on lahtine hulk, peab leiduma $C\in\mathfrak{C}$ nii, et $C\subset B_{n}$. Viimaks peab sama argumendi najal leiduma üks $B_{m}$ nii, et $B_{m}\subset C$. Leidsime, et suvalise lahtise hulga $U$ korral leidub mingi $ C\in\mathfrak{C}^* $, mis sisaldub hulgas $U$. Järelikult on $ \mathfrak{C}^* $ baas. $\Box$

**Viimaks**

Lindelöfi lemmal (mis väidab, et teisest loenduvuse aksioomist järeldub Lindelöfi omadus) on sarnane tõestus. Seal fikseeritakse suvaline kate ja eraldatakse baasist samuti sobivalt defineeritud indeksite kogumi järgi lahtiseid hulki.

Lihtsate lausete puhul kehtib vist alati üks kahest: see on kas triviaalne või mitu raskusastet keerulisem ühestki teisest teemakohasest ülesandest.