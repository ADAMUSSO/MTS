# Manažment komunikácie – vysvetľujúca verzia (poznámky na prezentovanie)

Tím 5 · Adam Svitek, Nikolas Knapík · streda 13:00 – 14:00

Druhá verzia prezentácie k téme 1 (súbor `Manažment komunikácie – vysvetľujúca prezentácia.pptx`). Pôvodná verzia stavia na prieskumoch a číslach; táto namiesto nich vysvetľuje tému na príkladoch a prirovnaniach (export dát, tichá pošta, telefonát/list/knižnica, riadiaca veža), aby ju pochopil aj niekto, kto ju nepozná. Jediné „číslo“ je počet komunikačných spojení n·(n−1)/2 – slúži ako ilustrácia, nie ako meranie.

Rozdelenie rovnaké ako v pôvodnej: Adam slajdy 1–5 a záver, Nikolas slajdy 6–14. Pri pokojnom tempe vychádza okolo 8:00 – 8:15; ak treba skrátiť, najľahšie sa dá vynechať slajd 7 (komunikačný plán), jeden z príkladov PMO (12–14) alebo pri slajde 4 povedať iba ľavú časť.

## 1. Úvodný slajd · 15 s · Adam

Dobrý deň, sme tím 5, Adam Svitek a Nikolas Knapík. Naša téma je manažment komunikácie v softvérovom projekte a kancelária projektového manažmentu. Dnes to nechceme ukazovať cez čísla, ale vysvetliť tak, aby ste si z toho odniesli, ako komunikácia v projekte naozaj funguje – a kde sa kazí.

## 2. O čom dnes budeme hovoriť · 20 s · Adam

Celá prezentácia odpovedá na jednu otázku: ako zabezpečiť, aby si ľudia v projekte naozaj rozumeli, a akú rolu v tom má kancelária projektového manažmentu, skrátene PMO. Pôjdeme v troch krokoch: najprv si vysvetlíme, čo komunikácia vlastne je, potom ako ju v projekte riadiť a nakoniec, čo robí PMO, keď projektov je viac.

## 3. Rovnaké slová, iný obraz v hlave · 45 s · Adam

Začnime príkladom. Klient napíše do ticketu: chceme jednoduchý export dát. V hlave má účtovníčku, ktorá raz mesačne potrebuje tabuľku faktúr v Exceli. To je zámer. Do ticketu ho ale zakóduje iba do troch slov. Ticket je kanál a šumom je tu to, že chýba príklad aj kontext. Vývojár si to dekóduje po svojom a urobí CSV cez API – technicky správne, ale pre účtovníčku nepoužiteľné.

Zachráni to až spätná väzba: keď sa niekto spýta „myslíte takto?“ a ukáže návrh. Preto hovoríme, že komunikácia nekončí odoslaním.

## 4. Prečo je to v softvérovom projekte ťažké · 40 s · Adam

Prečo je to práve v softvéri také ťažké? Prvý dôvod vidíte vľavo. Keď sú v tíme traja ľudia, majú medzi sebou tri spojenia. Pri piatich je ich desať a pri ôsmich už dvadsaťosem.

Druhý dôvod: softvér nie je vidieť. A tretí: každý hovorí iným jazykom – biznis o cieľoch, vývojár o riešení a vedenie o peniazoch a termínoch.

## 5. Správny kanál pre správnu správu · 40 s · Adam

Keď už vieme, že správa sa môže cestou pokaziť, ďalšia otázka je, akým kanálom ju poslať. Interaktívna komunikácia je ako telefonát – stretnutie, hovor alebo demo, kde sa obe strany môžu hneď pýtať. Push je ako list do schránky – pošlem e-mail alebo report, ale to, že ho niekto dostal, ešte neznamená, že ho prečítal. Pull je ako knižnica – wiki alebo backlog, kde si človek informáciu nájde sám, keď ju potrebuje.

Pravidlo je jednoduché: čím je správa nejasnejšia alebo citlivejšia, tým živší kanál potrebuje. Stav buildu stačí na dashboarde, ale spor o priority e-mailom nevyriešime.

## 6. Riadenie komunikácie je cyklus troch krokov · 40 s · Nikolas

Teraz k tomu, ako komunikáciu v projekte riadiť. Podľa PMBOK sú to tri kroky a každý sa dá zhrnúť jednou otázkou. Plánovanie: kto čo potrebuje vedieť, kedy a ako? Riadenie: deje sa to naozaj – vznikajú reporty, prebehne demo, zapisujú sa rozhodnutia? A monitorovanie: pomáha to? Napríklad zistíme, že náš týždenný report nikto nečíta – tak ho zmeníme. To, čo zistíme, sa vracia do plánu, takže je to cyklus, nie jednorazová úloha.

## 7. Komunikačný plán môže byť jednoduchá tabuľka · 35 s · Nikolas

Ako vyzerá komunikačný plán? Nemusí to byť hrubý dokument. Často stačí takáto tabuľka: kto, čo potrebuje vedieť, ako často, akým kanálom a kto za to zodpovedá. Sponzor chce raz za dva týždne vedieť stav, riziká a čo má rozhodnúť. Klient chce každý šprint vidieť demo. Tím rieši úlohy denne a prevádzka potrebuje vedieť, čo a kedy sa nasadí.

Dôležité je začať od ľudí, nie od nástrojov – až potom vyberáme Teams alebo Jiru. A plán má mať aj eskalačnú cestu: keď sa niečo zasekne, každý vie, komu to povedať a dokedy.

## 8. Každý v projekte hovorí trochu iným jazykom · 35 s · Nikolas

Každý v projekte hovorí o tom, čo sám rieši: klient o cieľoch, vývojár o technickom riešení, vedenie o peniazoch a termínoch. Preto projekt potrebuje prekladateľov.

Hore: klient povie, že chce, aby si zákazník vedel sám stiahnuť faktúru. Product Owner to preloží do konkrétnej úlohy – tlačidlo Stiahnuť PDF pri faktúre. Dole opačný smer: vývojár povie, že platobný modul má technický dlh. Vedeniu to nič nepovie, tak projektový manažér to preloží do dopadu – bez dvoch týždňov na opravu bude každá zmena platieb pomalšia a rizikovejšia. Keď tento preklad chýba, vznikajú bariéry, ktoré ukážeme teraz.

## 9. Tri typické bariéry a ako ich obísť · 40 s · Nikolas

Prvá bariéra je nejasné zadanie – klient povie „veď je jasné, čo chceme“, ale jasné je to iba jemu. Pomáhajú akceptačné kritériá s konkrétnym príkladom, prototyp a demo.

Druhá je technický text pre vedenie. Veta „padá nám migrácia databázy“ sponzorovi nič nepovie. Povieme radšej dopad a čo treba rozhodnúť: vydanie sa posunie o týždeň, potrebujeme vaše áno.

Tretia je chýbajúca spätná väzba. Pomôže zopakovať zadanie vlastnými slovami a prostredie, kde sa nikto nebojí povedať zlú správu. Inak vzniká melónový report – zelený navonok a červený vo vnútri.

## 10. Kancelária projektového manažmentu · 40 s · Nikolas

Tretia časť je kancelária projektového manažmentu, skrátene PMO. Je to útvar, ktorý zjednocuje, ako sa v organizácii riadia projekty, a podporuje ich metodikou, nástrojmi a ľuďmi. Každý projekt má svojho manažéra, PMO stojí nad nimi a vidí všetky projekty naraz.

Čo konkrétne robí? Prvé je spoločný jazyk – rovnaké šablóny a rovnaký význam stavu projektu. V reportoch sa stav často hlási farbou ako na semafore: zelená znamená, že ide podľa plánu, oranžová, že je tam riziko, a červená, že treba rozhodnutie vedenia. PMO určí, kedy je projekt naozaj zelený, aby „zelená“ znamenala v každom projekte to isté. Druhé sú zdieľaní ľudia – PMO má prehľad, kto na čom robí, aby si projekty nebrali toho istého človeka naraz. Tretie je jeden prehľad – vedenie dostane porovnateľné správy zo všetkých projektov na jednom mieste. A štvrté sú poučenia – čo sa naučil jeden projekt, ďalší už nemusí opakovať.

## 11. Tri typy PMO sa líšia tým, koľko kontrolujú · 40 s · Nikolas

PMO nie je jedno – rozlišujeme tri typy podľa toho, koľko kontroly majú. Podporné PMO je ako poradca: ponúka šablóny, školenia a rady, ale nikoho do ničoho nenúti. Hodí sa pri pár projektoch so skúsenými manažérmi, no keď nemá autoritu, nikto ho nepočúva.

Riadiace PMO je ako rozhodca s pravidlami: vyžaduje spoločnú metodiku a jednotné reporty a kontroluje ich. Dáva zmysel, keď si projekty delia ľudí alebo vedenie chce porovnateľný prehľad, ale ľahko z neho vznikne byrokracia.

Direktívne PMO je ako kapitán – projekty priamo riadi a manažéri patria pod neho. Pri strategických a veľmi rizikových projektoch dáva zmysel, no je drahé a môže sa stať úzkym hrdlom.

## 12. Príklad 1: tri reporty a každý je iný · 35 s · Nikolas

Ukážeme si každý typ PMO na jednom vymyslenom príklade. Prvý: malá firma má tri projekty a skúsených manažérov. Každý však píše report po svojom a „zelený“ znamená u jedného „ideme podľa plánu“, u druhého „zatiaľ to nehorí“. Vedenie dostane tri reporty a nevie ich porovnať.

Tu stačí podporné PMO. Dá jednu šablónu reportu a vysvetlí, čo znamená zelená, oranžová a červená – a skúsení manažéri ju radi prevezmú, lebo im to uľahčí prácu. Riadiace PMO by fungovalo tiež, ale povinné kontroly by boli zbytočná byrokracia. A direktívne PMO by bolo strieľanie kanónom na vrabce.

## 13. Príklad 2: jeden tester a tri projekty · 35 s · Nikolas

Druhý príklad: firma má tri projekty a jedného bezpečnostného testera. Každý manažér ho plánuje, akoby bol iba jeho, a všetky tri termíny padnú na ten istý týždeň.

Podporné PMO by iba poradilo plánovať skôr – ale konflikt by to nevyriešilo. Direktívne PMO by to vyriešilo, no pri troch projektoch je to zbytočne drahé. Riadiace PMO zavedie spoločný kalendár zdieľaných ľudí a pravidlo, že o prioritách rozhodne vedenie podľa podkladov od PMO.

## 14. Príklad 3: strategický projekt so zákonným termínom · 35 s · Nikolas

Tretí príklad: banka musí do zákonného termínu prejsť na nový platobný systém. Robia na ňom traja dodávatelia, každý komunikuje s bankou zvlášť a na rozhodnutia sa čaká týždne. Ak termín nestihnú, hrozí pokuta.

Podporné PMO tu nepomôže – problém nie je vo formáte reportu, ale v tom, že nikto nerozhoduje. Riadiace PMO by aspoň ukázalo, kde to viazne, ale rozhodovanie by zostalo rozdrobené. Direktívne PMO prevezme riadenie celého programu: jeden manažér, spoločné denné stretnutie a rozhodnutia v ten istý deň. Je to drahé, ale pri takomto projekte sa to oplatí. Typ PMO teda vyberáme podľa problému.

## 15. Čo si z toho odniesť · 30 s · Adam

Na záver tri myšlienky. Prvá: komunikácia znamená porozumenie – správa splnila účel, až keď ju príjemca pochopí a vie podľa nej konať. Druhá: komunikáciu treba riadiť vedome – naplánovať podľa potrieb ľudí, priebežne riadiť a kontrolovať, či funguje. A tretia: PMO drží celok pokope – zjednocuje jazyk a prehľad naprieč projektmi a jeho typ vyberáme podľa problému.

A ak si máte zapamätať jednu vetu: nástroje ani porady komunikáciu samy nezaručia – zaručia ju ľudia, ktorí si overujú, že si rozumejú. Ďakujeme a tešíme sa na otázky.

## 16. záložný slajd – Referencie

Záložný slajd so zdrojmi, z ktorých sme vychádzali.
