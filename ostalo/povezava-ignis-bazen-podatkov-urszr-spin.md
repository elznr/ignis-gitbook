---
description: Postopek dela IGNIS - Datapool - SPIN
---

# Povezava IGNIS - URSZR Bazen podatkov - SPIN

V tem sklopu sta povezavi pravzaprav dve. Povezava z URSZR bazen podatkov (Datapool) in povezava s SPIN sistemom.

&#x20;

Ko dispečer prevzame klic ReCO, se podatki iz Datapool prenesejo v IGNIS. Dispečer iz seznama (WebPLK dogodki) izbere ustrezen dogodek (prikazani so dogodki zadnjih 24 ur). Ob izbiri se prenesejo vsi podatki, ki jih je že vnesel operater na ReCO (naslov, dogodek, prijavitelj, št. prijavitelja, posebnosti lokacije...). To prihrani delo dispečerju v enoti, saj mu ni potrebno ponovno pridobivati podatke in jih pisati na roke. **Pogoj, da se podatk nahajajo v Datapool je, da vas operater ReCO aktivira preko njihovega sistema WebPLK.**&#x20;

<figure><img src="../.gitbook/assets/image (154).png" alt=""><figcaption><p><strong>Izbira Datapool (WebPLK) dogodka</strong></p></figcaption></figure>

Ko je intervencija zaključena in vodja izpolni in zaključi poročilo pa se podatki prenesejo v SPIN. S tem pa odstranimo dvojno delo vodje, saj mu ni potrebno še enkrat vnašati enake podatke ročno v SPIN. Podatke v SPIN samo preveri in dogodek zaključi. S tem tudi ni potrebno klicanje ReCO ob koncu intervencije in mu narekovati ure (če imate tak način dela, kot smo ga včasih imeli na GBL), saj s tem prenosom vse podatke že dobi. Ponavadi pokličemo ReCO in vprašamo če potrebuje še kakšne druge podatke, v večini ima vse.



Med aktivno intervencijo se v živo prenašajo časi (izvoz, prihod, odhod, vrnitev, zaključek), prav tako za dodatne enote, če imamo te pravice.



Ko zaključimo poročilo se prenesejo naslednji podatki:

1\.      časi (izvoz, prihod, odhod, vrnitev, zaključek)

2\.      število sodelujočih gasilcev (vodje naj ažurno pregledajo/popravijo gasilce na vozilih v 4. koraku)

3\.      opis intervencije

4\.      stroški intervencije

5\.      oddaljenost km

6\.      uporabljena vozila enote

7\.      aktivnosti enote

&#x20;

Za uspešen prenos podatkov mora vodja NUJNO izbrati ustrezen dogodek SPIN v 6. koraku.

<figure><img src="../.gitbook/assets/image (113).png" alt=""><figcaption></figcaption></figure>

V primeru, da dogodek prevzame dispečer ob začetku intervencije, bo ta dogodek že samodejno izbran (s pogojem, da je v tem trenutku dejansko odprt SPIN dogodek). Če SPIN dogodka ni na seznamu, pomeni da ni odprt in vam ga morajo na ReCO odpreti - zaenkrat še ni avtomatsko.

Trenutno je dogodek v SPIN še vedno potrebno zaključiti ročno, ker se lahko zgodi, da SPIN zahteva kakšno specifiko, ki jo v IGNIS nimamo. Delali bomo na tem, da bo v prihodnosti možno zaključiti SPIN dogodek direktno v IGNIS.

&#x20;

**Pred pričetkom je potrebno nekaj zadev povezati s SPIN sistemom (za uspešen prenos) in sicer:**

1\. VOZILA -> Seznam vozil -> Uredi. Za vsako vozilo izberemo SPIN vozilo in SPIN vrsta vozila.

2\. Za pravilen obračun stroškov, je potrebno pri vozilih vnesti cenik (€/uro in €/km). Cenik za gasilce vnesemo mi. Trenutno je GZS cenik in sicer **Urna postavka 6:00 - 18:00** 20.00€, **Urna postavka 18:00 - 6:00** 25.00€, **Urna postavka nedelje in prazniki** 29.00€. Če imate drugačne cene sporočite.

3\. ENOTA -> Zaposleni -> Uredi. Za vse vodje izberemo SPIN vodja.
