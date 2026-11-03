# Študijné poznámky – Manažment cieľov v softvérovom projekte

Tím 5 · Adam Svitek, Nikolas Knapík · streda 13:00 – 14:00

Tieto poznámky sú na **pochopenie a naučenie sa témy**, nie na čítanie počas prezentácie. Krátky text, ktorý sa hovorí nahlas, je v súbore `Poznamky_k_prezentacii_ciele.md` a v poznámkach rečníka v `Manažment cieľov – prezentácia.pptx`.

Najprv je **téma v kocke** – vysvetlenie od nuly, aby si vedel, o čo vôbec ide. Potom ku každému slajdu:

- **Hlavná myšlienka** – jedna veta, ktorú si musí publikum zapamätať.
- **Čo povedať** – body v poradí, v akom idú na slajde.
- **Vysvetlivky** – pozadie a pojmy, aby si vedel, *prečo* to tak je, a vedel to povedať aj inými slovami.
- **Ak sa niekto spýta** – pravdepodobné otázky a krátke odpovede.
- **Prechod** – veta, ktorou sa dostaneš na ďalší slajd.

Na konci je slovník pojmov, otázky k celej téme a ťahák na jednu stranu.

Rozdelenie: **Adam** slajdy 1–5 a 11, **Nikolas** slajdy 6–10. Celková dĺžka asi 6:45 (limit je 7:00).

---

## Téma v kocke – o čo vlastne ide

### Problém, ktorý téma rieši

Softvérový tím je skoro vždy zaneprázdnený: robí úlohy, zatvára tickety, nasadzuje nové verzie. Otázka je, **či tá práca niečomu pomáha**. Dá sa ľahko stať, že tím pol roka usilovne pracuje, všetky úlohy sú „hotové“, a používateľom sa aj tak nič nezlepšilo. Manažment cieľov je o tom, ako tomu zabrániť:

1. **ako cieľ správne zapísať** – aby každý vedel, čo znamená „uspeli sme“,
2. **ako ho sledovať** – aby sme počas projektu videli, či sa k nemu blížime,
3. **ako s ním zaobchádzať, keď sa projekt mení** – kedy cieľ podržať a kedy ho zmeniť.

Tretí bod je jadro našej témy. V softvéri sa skoro všetko mení: zákazník si to rozmyslí, príde nový zákon, zistíme, že používatelia sa správajú inak, než sme čakali. Keď cieľ nikdy nemeníme, robíme niečo, čo už nikto nepotrebuje. Keď ho meníme stále, nemáme žiadny smer a každý neúspech sa dá „vyriešiť“ premenovaním cieľa.

### Hlavná otázka prezentácie

*Ako stanoviť a priebežne riadiť ciele, aby tím vedel meniť postup a pritom nestratil účel projektu?*

### Odpoveď v troch vetách

1. **Cieľ je zmena pre používateľa, nie hotová úloha.** Hotový formulár je výstup; to, že sa študenti objednajú sami, je výsledok. Úspech meriame výsledkom.
2. **SMART a OKR sú dve pomôcky, ktoré sa dopĺňajú.** SMART kontroluje, či je jeden cieľ dobre napísaný. OKR určuje, čo je teraz prioritou a podľa akých výsledkov spoznáme pokrok.
3. **Smer držíme stabilný, cestu flexibilnú.** Úlohy a plán sa môžu meniť často. Samotný cieľ meníme len vtedy, keď na to máme dôkaz, keď to schváli ten, kto cieľ vlastní, a keď pôvodný cieľ ostane zapísaný.

### Príklad, ktorý ide celou prezentáciou

Vymyslený **rezervačný systém konzultácií pre študentov**. Dnes sa študenti často nevedia objednať sami a volajú alebo píšu administrátorovi, ktorý ich rezervácie vybavuje ručne. Chceme, aby sa objednali sami.

| Úroveň | V našom príklade |
|---|---|
| Účel produktu | menej ručnej práce pre administrátora |
| Cieľ | študent sa objedná sám, bez pomoci |
| Meradlo | podiel rezervácií dokončených bez pomoci |
| Východisko → cieľová hodnota | 60 % → 85 % (modelové čísla) |
| Úloha / iniciatíva | nový rezervačný formulár |
| Ochranná metrika | nesmú vzniknúť dvojité rezervácie |

Všetky čísla sú **vymyslené**. Na slajdoch to tak je označené a tak to treba aj povedať. Nikdy netvrdíme, že sme niečo merali.

### Ako to súvisí s témou 1

Pri komunikácii sme hovorili, že správa nestačí odoslať – musí ju niekto pochopiť a vedieť podľa nej konať. Pri cieľoch je to podobné: úlohu nestačí dokončiť – musí niečo zmeniť. V oboch témach ide o to, nepomýliť si **aktivitu** (poslal som, urobil som) s **účinkom** (pochopili, zlepšilo sa).

---

## Slajd 1 – Manažment cieľov v softvérovom projekte · Adam · 15 s

**Hlavná myšlienka:** Predstavíme sa a položíme otázku, na ktorej stojí celá téma: keď je úloha hotová, je splnený aj cieľ?

**Čo povedať**
- Kto sme: tím 5, Adam Svitek a Nikolas Knapík.
- Téma: manažment cieľov v softvérovom projekte.
- Úvodná otázka: keď je úloha hotová, je splnený aj cieľ? (Odpoveď je „nie nutne“ – ukážeme na slajde 3.)

**Vysvetlivky**
- Obrázok na slajde je **terč s tromi krokmi**, ktoré k nemu vedú. Kroky = iterácie (šprinty). Ide o myšlienku celej prezentácie: cieľ je v strede a stojí, cesta k nemu sa skladá z menších krokov a dá sa upravovať.
- **Manažment cieľov** nie je samostatná oblasť v PMBOK ako komunikácia. Je to skôr spôsob, ako sa do projektu premieta stratégia: od účelu produktu cez dlhodobé ciele až po cieľ jedného šprintu.

**Prechod:** „Celá prezentácia odpovedá na jednu otázku.“

---

## Slajd 2 – O čom dnes budeme hovoriť · Adam · 20 s

**Hlavná myšlienka:** Ideme v troch krokoch: čo je cieľ, ako ho sformulovať a ako s ním pracovať, keď sa projekt mení.

**Čo povedať**
- Otázka: *Ako stanoviť a priebežne riadiť ciele, aby tím vedel meniť postup a pritom nestratil účel projektu?*
- Tri kroky:
  1. **Čo je cieľ – a čo ním nie je** (cieľ vs. úloha, výstup vs. výsledok).
  2. **Ako cieľ sformulovať** – SMART a OKR.
  3. **Ako s cieľom pracovať, keď sa projekt mení** – horizonty, kedy cieľ meniť, tri situácie.

**Vysvetlivky**
- V otázke sú dve slová, ktoré sa zdanlivo bijú: **„meniť postup“** a **„nestratiť účel“**. To je napätie celej témy – stabilita vs. flexibilita. Abstrakt sa pýta presne na toto: do akej miery majú byť ciele pevné a kedy ich upraviť.
- Poradie ide od jedného cieľa (čo to je), cez jeho zápis (SMART, OKR), po život cieľa v čase (zmeny).

**Prechod:** „Začnime príkladom, ktorý nás bude sprevádzať celý čas.“

---

## Slajd 3 – Formulár je hotový. Je cieľ splnený? · Adam · 45 s

**Hlavná myšlienka:** Úloha môže byť hotová a cieľ nesplnený – úspech meriame tým, čo sa zmenilo pre používateľa, nie počtom hotových úloh.

**Čo povedať** (slajd ide zľava doprava, štyri karty)
1. **Účel** – prečo produkt existuje? → menej ručnej práce pre administrátora.
2. **Cieľ** – aký stav chceme dosiahnuť? → študent sa objedná sám, bez pomoci.
3. **Meradlo** – ako spoznáme pokrok? → podiel rezervácií dokončených bez pomoci.
4. **Úloha** – čo urobíme? → nový rezervačný formulár.
- Potom spodné dve karty: formulár je nasadený (úloha splnená ✓), ale študenti stále volajú administrátorovi (cieľ nesplnený ✗).
- Pointa: úspech meriame zmenou pre používateľa.

**Vysvetlivky**
- **Účel (vízia)** odpovedá na *prečo*. Mení sa zriedka – roky.
- **Cieľ** je *stav*, ktorý chceme dosiahnuť. Nie je to činnosť. „Urobiť formulár“ nie je cieľ, „študent sa objedná sám“ je cieľ.
- **Meradlo (metrika, ukazovateľ)** je číslo, na ktorom vidíme, ako sa k cieľu blížime. Bez meradla sa o cieli nedá rozhodnúť, či je splnený.
- **Úloha (iniciatíva)** je to, čo tím *robí*, aby sa cieľ naplnil. Je to *hypotéza*: „myslíme si, že nový formulár pomôže“. Môže sa ukázať, že nepomôže.
- Prečo je úloha vpravo zvýraznená zelenou: tímy sa na ňu prirodzene sústredia najviac, lebo je najkonkrétnejšia. Slajd ukazuje, že je to len posledný článok reťaze.
- **Prečo sa to deje v praxi:** hotové úlohy sa ľahko počítajú (Jira to ukáže sama), zmenu správania používateľov treba merať. Preto tímy a vedenie často sledujú to, čo je ľahké, namiesto toho, čo je dôležité.

**Ak sa niekto spýta**
- *„Nie je ten formulár proste zle navrhnutý? Stačí ho opraviť.“* – Možno áno, ale to zistíme iba vďaka tomu, že meriame cieľ. Keby sme sledovali iba úlohy, formulár by bol „hotový“ a nikto by sa ďalej nepýtal.
- *„Prečo by nemohol byť cieľ ‚dodať formulár‘?“* – Môže to byť míľnik projektu, ale nehovorí nič o hodnote. Zákazník neplatí za formulár, ale za to, že sa študenti vedia objednať.

**Prechod:** „Tomuto rozdielu sa hovorí výstup a výsledok.“

---

## Slajd 4 – Výstup nie je výsledok · Adam · 35 s

**Hlavná myšlienka:** Výstup je to, čo sme vytvorili; výsledok je zmena, ktorú to prinieslo. Jasný cieľ pomáha, ale úzky cieľ môže uškodiť – preto pridávame ochrannú metriku.

**Čo povedať**
- Vľavo **výstup (output)**: nový formulár, 30 automatizovaných testov, 20 uzavretých úloh v Jire.
- Vpravo **výsledok (outcome)**: viac študentov dokončí rezerváciu samo, administrátor trávi menej času rezerváciami, používatelia nachádzajú menej chýb.
- Dole vľavo: **prečo jasný cieľ pomáha** – konkrétny cieľ usmerní pozornosť a úsilie lepšie než „urobte maximum“ (Locke a Latham, 2002).
- Dole vpravo: **kde má hranice** – keď sledujeme iba jedno číslo, tím ho zlepší aj na úkor kvality. Preto pridáme ochrannú metriku (Ordóñez a kol., 2009).

**Vysvetlivky**
- **Output vs. outcome** je bežné rozlíšenie v produktovom manažmente. Niekedy sa pridáva tretia úroveň **impact** (dopad na organizáciu – napr. ušetrené peniaze). Na prezentácii ju nespomíname, ale ak sa niekto spýta: impact = prečo na výsledku záleží firme.
- **Locke a Latham (2002)** – dvaja psychológovia, ktorí 35 rokov skúmali, ako ciele ovplyvňujú výkon (tzv. *goal-setting theory*). Hlavné zistenia:
  - Konkrétne a náročné ciele vedú k lepšiemu výkonu ako neurčité „urobte, čo sa dá“.
  - Fungujú cez štyri mechanizmy: usmernia **pozornosť**, zvýšia **úsilie**, **vytrvalosť** a prinútia hľadať **stratégiu**.
  - Ale iba za podmienok: ľudia musia cieľ **prijať**, musia dostávať **spätnú väzbu** o pokroku a musia mať **schopnosti**. Pri **novej a zložitej úlohe** je lepší *cieľ učenia* („zisti, prečo ľudia odchádzajú z formulára“) než výkonový cieľ („zvýš na 85 %“).
- **Ordóñez a kol. (2009), „Goals Gone Wild“** – kritická reakcia na nadšenie z cieľov. Úzko nastavené ciele môžu:
  - vytlačiť všetko, čo sa nemeria (kvalitu, bezpečnosť, spoluprácu),
  - podporiť zbytočné riskovanie alebo dokonca podvádzanie, aby sa číslo splnilo.
  - Pozor: je to *working paper* (pracovný článok), nie experiment. Netvrdí, že ciele škodia vždy – iba že treba dávať pozor.
- S tým súvisí **Goodhartov zákon**: „Keď sa meradlo stane cieľom, prestane byť dobrým meradlom.“ Príklad zo softvéru: keď je cieľom „100 % pokrytie testami“, tím napíše testy, ktoré síce prejdú cez každý riadok, ale nič neoveria.
- **Ochranná metrika (guardrail)** = číslo, ktoré sa nesmie zhoršiť, kým zlepšujeme hlavný cieľ. U nás: žiadne dvojité rezervácie. Bez nej by sa dalo „zlepšiť“ dokončenie rezervácie tak, že vypneme kontrolu obsadenosti – študenti by sa objednávali rýchlejšie, ale dvaja na ten istý termín.

**Ak sa niekto spýta**
- *„Nie sú tie testy a uzavreté úlohy tiež dôležité?“* – Sú, ale sú to prostriedky. Hovoria, že tím pracuje, nie že pracuje na správnej veci.
- *„Ako viete merať, či používatelia nachádzajú menej chýb?“* – Napríklad počet nahlásených chýb od používateľov na počet nasadení alebo za mesiac. Dôležité je mať definíciu (čo je chyba, aká závažnosť) a nemeniť ju počas merania.

**Prechod:** „Ako taký cieľ napísať tak, aby bolo jasné, kedy sme uspeli? Prvá pomôcka je SMART.“

---

## Slajd 5 – SMART: vieme, kedy sme uspeli? · Adam · 45 s

**Hlavná myšlienka:** SMART je kontrolný zoznam piatich otázok, ktorý z neurčitého želania urobí cieľ, pri ktorom vieme povedať, či sme ho splnili.

**Čo povedať**
- Vľavo hore neurčitý cieľ: „Zlepšiť rezervačný systém.“ Kedy je hotový? Nikto nevie.
- Pod ním ten istý cieľ podľa SMART: „Do konca 8-týždňového pilotu zvýšime podiel rezervácií, ktoré študent dokončí bez pomoci, zo 60 % na 85 %.“
- Vpravo písmená:
  - **S – Specific (konkrétny):** čo a pre koho – samostatná rezervácia študenta.
  - **M – Measurable (merateľný):** východisko 60 % → cieľ 85 %.
  - **A – Achievable (dosiahnuteľný):** 85 % je zatiaľ predpoklad – overí ho pilot. (Preto je oranžovou.)
  - **R – Relevant (relevantný):** šetrí čas administrátora, teda plní účel produktu.
  - **T – Time-bound (časovo ohraničený):** vyhodnotíme na konci pilotu.
- Čísla sú modelové.

**Vysvetlivky**
- **Pôvod:** George T. Doran, 1981, krátky článok v časopise *Management Review*. Pôvodne písmená znamenali **S**pecific, **M**easurable, **A**ssignable (dá sa prideliť konkrétnemu človeku), **R**ealistic, **T**ime-related. My používame dnes rozšírenú verziu (napr. ako ju opisuje americká inštitúcia CDC). Ak sa niekto spýta na rôzne verzie, toto je odpoveď – nie je to chyba, skratka sa časom menila.
- Doran sám písal, že nie každý cieľ musí spĺňať všetkých päť písmen a nie každý musí byť vyjadrený číslom.
- **Baseline (východisko)** = hodnota pred zmenou (60 %). Bez neho nevieme, či 85 % je veľké zlepšenie, alebo či sme tam už takmer boli.
- **Prečo je A oranžové:** to je najslabšie miesto nášho cieľa a priznávame to. Číslo 85 % sme si vymysleli. V reálnom projekte by sme ho mali overiť – pozrieť sa, prečo ľudia dnes neuspejú, koľko z toho vieme ovplyvniť, a vyskúšať to na malej skupine (pilot). Napísať číslo nestačí na to, aby bol cieľ dosiahnuteľný.
- **Pilot** = vyskúšanie zmeny v menšom rozsahu (napr. na jednej fakulte) pred nasadením pre všetkých.
- **Čo SMART nerieši:** je to pomôcka na *zápis jedného cieľa*. Nehovorí, ktorý cieľ je dôležitejší, ako ciele prepojiť medzi tímami, ani ako často ich prehodnocovať. Preto potrebujeme aj OKR a pravidlá pre zmeny.

**Ak sa niekto spýta**
- *„Prečo práve 85 %?“* – Je to modelový predpoklad. V reálnom projekte by sme ho odvodili z baseline, známych prekážok a pilotu.
- *„Nie je SMART zastaraný?“* – Je starý, ale stále užitočný ako kontrola formulácie. Nikto netvrdí, že je to celá metodika riadenia.
- *„Čo keď cieľ nejde vyjadriť číslom?“* – Doran to pripúšťa. Potom aspoň presne opíšeme, ako spoznáme, že je splnený (napr. „administrátor potvrdí, že nové rezervácie nemusí opravovať“).

**Prechod:** (Adam odovzdáva Nikolasovi) „SMART skontroluje jeden cieľ. Ale čo keď máme viac cieľov a treba vedieť, čo je prioritou? Na to je OKR – Nikolas.“

---

## Slajd 6 – OKR: kam smerujeme a ako spoznáme pokrok · Nikolas · 45 s

**Hlavná myšlienka:** OKR delí cieľ na smer (Objective) a niekoľko merateľných výsledkov (Key Results); činnosti sú až pod nimi a môžu sa meniť.

**Čo povedať**
- **Objective – smer:** „Rezervovanie konzultácie je pre študentov samostatné a spoľahlivé.“
- **Key Result 1:** samostatne dokončené rezervácie 60 % → 85 %.
- **Key Result 2:** čas administrátora na 100 rezervácií 120 → 60 min.
- **Iniciatívy** – čo skúsime: jednoduchší formulár, jasná správa pri obsadenom termíne, test prototypu s používateľmi. Môžu sa meniť.
- **Ochranná podmienka:** žiadne dvojité rezervácie.
- Pointa: Key Result meria zmenu, nie aktivitu – „spustiť nový formulár“ je iniciatíva, nie Key Result.

**Vysvetlivky**
- **OKR = Objectives and Key Results.** Vymyslel ich Andy Grove v Inteli v 70. rokoch, do Googlu ich v roku 1999 priniesol John Doerr a odtiaľ sa rozšírili. Zdroje, z ktorých vychádzame: príručka Google re:Work a dokumentácia Microsoft Learn.
- **Objective** je kvalitatívny – slovami, motivujúci, hovorí *kam*. Nemá v sebe číslo.
- **Key Results** sú kvantitatívne – 2 až 4 čísla, ktoré dokazujú, že sa k Objective blížime. Typicky „z X na Y“.
- **Iniciatívy** sú projekty a úlohy, ktorými chceme KR pohnúť. To sú *naše stávky* – ak niektorá nefunguje, vymeníme ju za inú. Preto „môžu sa meniť“.
- Prečo dva KR a nie jeden: jeden pohľad by mohol klamať. KR1 meria študentov, KR2 meria administrátora (účel produktu). Ak by KR1 rástol, ale KR2 nie, niečo nesedí – napríklad študenti sa objednajú sami, ale administrátor potom rezervácie aj tak opravuje.
- **Najčastejšia chyba pri OKR:** písať do KR úlohy („spustiť formulár“, „napísať 30 testov“). Potom je OKR iba to-do list s iným názvom. Test: dá sa KR splniť bez toho, aby sa používateľom niečo zlepšilo? Ak áno, nie je to dobrý KR.
- **Záväzné vs. ambiciózne OKR:** Google rozlišuje *committed* (musíme splniť na 100 %) a *aspirational* (náročné; dosiahnuť okolo 70 % sa považuje za dobrý výsledok). Pozor: 70 % neplatí pre všetko. Pri ochrannej podmienke „žiadne dvojité rezervácie“ by 70 % splnenia bolo nezmyselné.
- **Cyklus:** OKR sa často nastavujú na štvrťrok, ale nemusí to tak byť. U nás je to 8-týždňový pilot.

**Ak sa niekto spýta**
- *„Aký je rozdiel medzi KR a KPI?“* – KPI je ukazovateľ, ktorý sledujeme stále (napr. počet rezervácií za týždeň). KR je ukazovateľ, ktorý chceme v danom období zámerne **zmeniť** z hodnoty X na Y. KPI sa môže stať KR, keď sa rozhodneme ho zlepšiť.
- *„Prečo sú iniciatívy oddelené?“* – Aby sme si nepomýlili prácu s výsledkom. Keď iniciatíva nefunguje, vymeníme ju a cieľ ostáva.

**Prechod:** „Musíme si teda medzi SMART a OKR vybrať?“

---

## Slajd 7 – SMART a OKR sa nevylučujú, dopĺňajú sa · Nikolas · 35 s

**Hlavná myšlienka:** SMART a OKR riešia iné otázky – OKR určí smer a priority, SMART spresní každý Key Result.

**Čo povedať** (tabuľka po riadkoch)
- **Pýta sa:** SMART – je tento jeden cieľ jasný a overiteľný? OKR – čo je teraz prioritou a ako spoznáme pokrok?
- **Pracuje s:** SMART – jedným cieľom a piatimi kritériami. OKR – smerom a 2–4 merateľnými výsledkami.
- **Riziko:** SMART – formálne správny, ale nedôležitý cieľ. OKR – Key Results, ktoré iba premenujú úlohy.
- Dole: spolu – OKR určí smer a priority, SMART spresní každý Key Result. Malému tímu s jedným cieľom môže stačiť SMART a pravidelná dohoda.

**Vysvetlivky**
- **Formálne správny, ale nedôležitý cieľ:** „Do 30. 11. zvýšime počet farieb v rozhraní z 5 na 8.“ Je konkrétny, merateľný, dosiahnuteľný, s termínom – a nikomu to nepomôže. SMART kontroluje formu, nie či je cieľ múdry. Písmeno R to má chytiť, ale v praxi sa často odbije.
- **Ako sa kombinujú:** Objective povie smer. Každý KR si potom skontrolujeme cez SMART – je konkrétny? merateľný? dosiahnuteľný? relevantný k Objective? s termínom? Náš KR1 je vlastne SMART cieľ zo slajdu 5.
- **Prečo nie vždy OKR:** OKR je proces – nastavovanie, priebežné kontroly, hodnotenie. Pri malom tíme s jedným jasným cieľom je to zbytočná administratíva. OKR sa oplatí, keď treba **zosúladiť** viac tímov alebo vybrať z viacerých priorít.
- Toto porovnanie je **naša analýza** z definícií, nie výsledok nejakého výskumu, ktorý by dokazoval, že jedno je lepšie.

**Ak sa niekto spýta**
- *„Tak čo je lepšie?“* – Nie je to otázka lepšieho. Je to ako pýtať sa, či je lepšia mapa alebo kontrolný zoznam pred cestou. OKR je mapa (kam ideme), SMART kontroluje, či je každá zastávka jasne označená.
- *„Dokazuje niečo, že SMART alebo OKR fungujú?“* – Výskum Lockeho a Lathama ukazuje, že konkrétne ciele pomáhajú. Že práve SMART alebo OKR sú najlepšie v každom softvérovom tíme, nedokazuje nikto – to netvrdíme.

**Prechod:** „Teraz vieme cieľ napísať. Ako s ním ale žiť počas projektu, keď sa veci menia?“

---

## Slajd 8 – Cieľ drží smer, plán sa môže meniť · Nikolas · 40 s

**Hlavná myšlienka:** Ciele majú rôzne horizonty; čím je cieľ dlhodobejší, tým je stabilnejší – a čím nižšie ideme, tým viac sa smie meniť.

**Čo povedať** (schody zhora nadol)
- **Účel produktu** – menej ručnej práce pre administrátora – roky.
- **Product Goal** – samostatná a spoľahlivá rezervácia – mesiace.
- **Sprint Goal** – študent vidí voľné termíny a dokončí rezerváciu – 2 týždne.
- **Práca v šprinte** – UI, API, kontrola súbehu, testy – mení sa denne.
- Šípka vpravo: hore stabilnejšie (mení sa zriedka), dole flexibilnejšie (mení sa často).
- Scrum: rozsah práce v šprinte sa môže upraviť, ak tým neohrozíme Sprint Goal.

**Vysvetlivky**
- **Scrum** je najrozšírenejší agilný rámec. Práca sa delí na **šprinty** – krátke obdobia (najviac mesiac, často 2 týždne), po ktorých je hotová použiteľná časť produktu.
- **Product Goal** (Scrum Guide 2020) = dlhodobý cieľ produktu. Je to „záväzok“ k Product Backlogu (zoznamu všetkého, čo sa má urobiť). Tím pracuje na jednom Product Goal naraz.
- **Sprint Goal** = jeden cieľ šprintu, prečo je ten šprint užitočný. Je to záväzok k Sprint Backlogu (úlohám šprintu).
- **Čo hovorí Scrum Guide o zmenách:** počas šprintu sa nerobia zmeny, ktoré by ohrozili Sprint Goal. Ale rozsah práce sa môže spresniť a dohodnúť s Product Ownerom. Ak sa Sprint Goal stane úplne zbytočným, šprint môže zrušiť **iba Product Owner**. (Na slajde to už nie je, ale je to dobrá odpoveď na otázku.)
- **Kontrola súbehu** = aby si dvaja študenti v tú istú chvíľu nezarezervovali ten istý termín. To je technická úloha, ktorá chráni ochrannú metriku zo slajdov 4 a 6.
- **Hlavná pointa slajdu:** stabilita a flexibilita sa nevylučujú – každá patrí na inú úroveň. Abstrakt sa pýta, či majú byť ciele pevné alebo flexibilné. Odpoveď: **závisí od úrovne**. Účel skoro pevný, práca veľmi flexibilná.
- Schéma je náš model. Scrum nehovorí o „účele produktu“ ako o samostatnej úrovni a Product Goal nemusí byť to isté ako OKR firmy.

**Ak sa niekto spýta**
- *„Môže sa Sprint Goal počas šprintu zmeniť?“* – Nie je určený na prepisovanie. Mení sa rozsah práce, aby sa Sprint Goal dosiahol. Ak už nemá zmysel, Product Owner zruší šprint a začne sa nový.
- *„Čo keď nepoužívame Scrum?“* – Princíp platí aj tak: dlhodobý cieľ, cieľ najbližšieho obdobia a konkrétna práca. Scrum je len najznámejší príklad, kde sú tieto úrovne pomenované.

**Prechod:** „Niekedy však treba zmeniť aj samotný cieľ, nielen prácu. Ako to spoznať?“

---

## Slajd 9 – Pred zmenou cieľa si položíme štyri otázky · Nikolas · 40 s

**Hlavná myšlienka:** Cieľ nemeníme z pocitu, ale po štyroch otázkach – a ako často ho prehodnocujeme, závisí od toho, koľko toho ešte nevieme.

**Čo povedať**
1. **Je cieľ stále dôležitý?** Rieši ešte skutočnú potrebu používateľov?
2. **Meriame správne?** Nie je chyba v dátach, definícii alebo malej vzorke?
3. **Zlyhal cieľ, alebo cesta?** Zlé riešenie → meníme iniciatívu, nie cieľ.
4. **Kto rozhodne a zapíše?** Vlastník cieľa schváli zmenu, starý cieľ ostane v histórii.
- Škála dole: **pevnejší cieľ** pri zmluve, zákonnom termíne, bezpečnosti; **pravidelná revízia** napr. na konci každého šprintu; **častá revízia** pri novom produkte, keď nepoznáme používateľov.

**Vysvetlivky**
- Tieto otázky sú **náš vlastný návrh** (syntéza), nie prevzatá metodika. Na prezentácii aj v eseji to tak treba povedať – je to práve tá „vlastná myšlienka“, ktorú hodnotitelia chcú vidieť.
- **Otázka 1 – relevantnosť:** svet sa mohol zmeniť (nový zákon, iný zákazník). Ak cieľ nerieši skutočnú potrebu, nemá zmysel ho naháňať.
- **Otázka 2 – meranie:** predtým, než povieme „cieľ nefunguje“, overíme, či čísla nekľamú. Príklady chýb: zmenili sme, čo počítame ako „pokus o rezerváciu“; merali sme cez prázdniny, keď sa nikto neobjednáva; máme iba päť používateľov.
- **Otázka 3 – cieľ vs. cesta:** najdôležitejšia. Väčšinou nefunguje *riešenie*, nie *cieľ*. Keď nový formulár nepomohol, neznamená to, že samostatná rezervácia je zlý cieľ – iba že formulár nebol správna cesta.
- **Otázka 4 – zodpovednosť a história:** zmena musí mať vlastníka (v Scrume Product Owner) a musí byť zapísaná: starý cieľ, dôvod, dátum, kto schválil, nový cieľ. Inak sa dá každý neúspech zamaskovať: „Ciele sme splnili – len sme ich priebežne upravili.“
- **Škála:** frekvenciu revízie odvodzujeme od **neistoty** (koľko nevieme), **ceny zmeny** (koľko stojí zmeniť smer) a toho, ako rýchlo dostaneme **spätnú väzbu**. Pri zákonnom termíne je zmena drahá a potreba známa → pevnejšie. Pri novom produkte nevieme, čo ľudia chcú → revidujeme často, niekedy najprv s cieľom učenia (zistiť) namiesto výkonového cieľa (dosiahnuť číslo).
- Súvis s **Agilným manifestom (2001)**: jeden z jeho princípov hovorí, že vítame zmeny požiadaviek aj neskoro vo vývoji, a iný, že tím pravidelne reflektuje a upravuje svoje správanie. Z toho ale **nevyplýva**, že ciele treba meniť po každej požiadavke.

**Ak sa niekto spýta**
- *„Nie je zmena cieľa iba ospravedlnenie neúspechu?“* – Môže byť, ak nemá dôkazy a záznam. Preto otázky 2 a 4: overiť meranie a zapísať pôvodný cieľ aj odchýlku.
- *„Kto je vlastník cieľa?“* – Ten, kto zodpovedá za výsledok a môže rozhodnúť o prioritách – v Scrume Product Owner, inak napr. sponzor alebo produktový manažér.

**Prechod:** „Ukážme si to na troch situáciách z nášho príkladu.“

---

## Slajd 10 – Príklad: tri situácie, tri rozhodnutia · Nikolas · 50 s

**Hlavná myšlienka:** Meníme to, čo prestalo platiť – riešenie, cieľ alebo plán – a nikdy nie potichu číslo, aby bol report zelený.

**Čo povedať**
- **A – Nový formulár nepomohol.** Rezervácie sa nezlepšili, z rozhovorov vyplýva, že študenti nevidia voľné termíny. → **Zachovať cieľ**, zmeniť riešenie. Potreba platí.
- **B – Prišlo povinné schvaľovanie.** Škola nariadi, že každú rezerváciu musí schváliť administrátor. → **Upraviť cieľ**: samostatná žiadosť a rýchle schválenie.
- **C – Tím mešká.** Integrácia trvá dlhšie, potreba sa nezmenila. → **Upraviť plán**: zúžiť rozsah alebo otvorene preplánovať.
- Čo nesmieme: potichu znížiť cieľovú hodnotu, aby bol report zelený. Pôvodný cieľ aj odchýlka ostanú zapísané.

**Vysvetlivky**
- Každá situácia zodpovedá jednej otázke zo slajdu 9:
  - **A** = otázka 3 (zlyhal cieľ, alebo cesta?). Zlyhala cesta. Pozor: aj tu najprv overiť meranie a nebrať jeden rozhovor ako dôkaz – treba viac používateľov.
  - **B** = otázka 1 (je cieľ stále dôležitý?). Pôvodný cieľ „bez pomoci administrátora“ je teraz nemožný – zákon/pravidlo školy to zakazuje. Cieľ sa musí zmeniť. Upravia sa aj Key Results (napr. čas od žiadosti po schválenie) a staré dáta sa nesmú priamo porovnávať s novými, lebo meriame niečo iné.
  - **C** = nie je to problém cieľa ani potreby, ale kapacity a odhadu. Najprv vyhodiť prácu, ktorá cieľu nepomáha. Ak to nestačí, povedať vlastníkovi cieľa otvorene, že termín nestihneme, a dohodnúť nový.
- Prečo je B oranžovou: je to jediná situácia, kde sa naozaj mení cieľ. Je to výnimka, nie pravidlo.
- **„Zelený report“** – stav projektu sa často hlási farbami semafora (zelená = ide podľa plánu). Spojenie s témou 1: *melónový report*, zelený navonok, červený vnútri. Tu by to bolo, keby sme v situácii C znížili cieľ z 85 % na 70 %, aby report ukázal „splnené“.

**Ak sa niekto spýta**
- *„Prečo v situácii C nemôžeme proste znížiť cieľ?“* – Môžeme, ale iba otvorene: s vlastníkom, so zdôvodnením a so záznamom pôvodnej hodnoty. Zakázané je to robiť potichu – vtedy je to skrývanie problému.
- *„Čo ak sa v situácii A ukáže, že žiadne riešenie nepomáha?“* – Potom sa vraciame k otázke 1: možno je cieľ nereálny alebo študenti chcú niečo iné. Ale až po viacerých pokusoch a s dátami.

**Prechod:** (Nikolas odovzdáva Adamovi) „Na záver zhrnie Adam.“

---

## Slajd 11 – Čo si z toho odniesť · Adam · 35 s

**Hlavná myšlienka:** Cieľ je zmena pre používateľa; SMART a OKR sa dopĺňajú; smer držíme stabilný, cestu flexibilnú.

**Čo povedať**
1. **Cieľ je zmena, nie úloha** – úspech meriame zmenou pre používateľa, nie počtom hotových úloh.
2. **SMART a OKR sa dopĺňajú** – OKR dáva smer a priority, SMART spresní, kedy sme uspeli.
3. **Stabilný smer, flexibilná cesta** – plán meníme často, cieľ iba s dôkazom, vlastníkom a záznamom.
- Veta v rámčeku: Pevný cieľ neznamená nemenný navždy. Flexibilný cieľ neznamená bez zodpovednosti.
- **Stav práce:** máme spracované pojmy, SMART, OKR a rozhodovanie pri zmene; v eseji ešte doplníme dôveryhodné meranie a hranice modelového príkladu.

**Vysvetlivky**
- Tri body zodpovedajú trom sekciám prezentácie (01, 02, 03) – ak zabudneš text, choď podľa sekcií.
- **Stav práce** musí zaznieť, lebo podľa podmienok predmetu sa prezentuje *aktuálny stav* projektu (eseje).
- **Dôveryhodné meranie** (čo ešte doplníme) = presne definovať, čo je „pokus o rezerváciu“ a čo „úspech“, ako počítame percento, aby sme porovnávali porovnateľné obdobia a aby sme nevydávali zmenu čísla za dôkaz, že ju spôsobil náš formulár (mohli napr. len pribudnúť voľné termíny).
- **Hranice príkladu** = jeden vymyslený systém nedokazuje, že náš postup funguje všade. Je to ilustrácia, nie výskum.

**Prechod:** „Ďakujeme a tešíme sa na otázky.“

---

## Slajd 12 – Referencie (záložný slajd)

Zdroje a na čo sme ich použili:

| Zdroj | Na čo |
|---|---|
| CDC (2024), SMART Framework | dnešná verzia SMART (slajd 5) |
| Google re:Work (2016), Set goals with OKRs | Objective, Key Results, ambiciózne vs. záväzné, skórovanie (slajd 6) |
| Microsoft Learn, Write effective OKRs | rozdiel Objective / Key Result / iniciatíva (slajd 6) |
| Locke a Latham (2002) | prečo konkrétne ciele pomáhajú a za akých podmienok (slajd 4) |
| Ordóñez a kol. (2009), Goals Gone Wild | kedy ciele škodia, protiargument (slajd 4) |
| Schwaber a Sutherland (2020), Scrum Guide | Product Goal, Sprint Goal, zmeny v šprinte (slajd 8) |
| Doran (1981) | pôvodná verzia SMART (iba ak sa niekto spýta) |
| Agilný manifest (2001) | vítanie zmien a pravidelná reflexia (slajd 9) |

---

## Slovník pojmov

| Pojem | Vysvetlenie jednou-dvoma vetami |
|---|---|
| **Účel / vízia** | Prečo produkt existuje. Mení sa zriedka. |
| **Cieľ** | Stav, ktorý chceme dosiahnuť. Nie činnosť. |
| **Úloha / iniciatíva** | Čo tím urobí, aby sa cieľ naplnil. Je to hypotéza – môže nepomôcť. |
| **Výstup (output)** | Čo sme vytvorili: funkcia, formulár, testy. |
| **Výsledok (outcome)** | Čo sa zmenilo pre používateľa. Podľa toho meriame úspech. |
| **Dopad (impact)** | Prečo na výsledku záleží organizácii (peniaze, čas, riziko). |
| **Metrika / ukazovateľ** | Číslo, na ktorom sledujeme pokrok. |
| **KPI** | Ukazovateľ, ktorý sledujeme priebežne. Nemusí byť cieľom. |
| **Baseline (východisko)** | Hodnota pred zmenou; bez nej nevieme, či sme sa zlepšili. |
| **Cieľová hodnota** | Kam chceme ukazovateľ dostať a dokedy. |
| **Ochranná metrika (guardrail)** | Čo sa nesmie zhoršiť, kým zlepšujeme hlavný cieľ. |
| **SMART** | Specific, Measurable, Achievable, Relevant, Time-bound – kontrola formulácie jedného cieľa. |
| **OKR** | Objectives and Key Results – smer + 2–4 merateľné výsledky. |
| **Objective** | Kvalitatívny smer, slovami, bez čísla. |
| **Key Result (KR)** | Merateľný výsledok „z X na Y“, ktorý dokazuje pokrok k Objective. |
| **Záväzné vs. ambiciózne OKR** | Záväzné treba splniť celé; pri ambicióznych je ~70 % dobrý výsledok. |
| **Goal-setting theory** | Teória Lockeho a Lathama: konkrétne a náročné ciele zlepšujú výkon, za podmienok. |
| **Cieľ učenia** | Cieľ „zistiť / naučiť sa“ namiesto „dosiahnuť číslo“; vhodný pri novej a zložitej úlohe. |
| **Goodhartov zákon** | Keď sa meradlo stane cieľom, prestane byť dobrým meradlom. |
| **Pilot** | Vyskúšanie zmeny v menšom rozsahu pred plným nasadením. |
| **Scrum** | Agilný rámec; práca v krátkych šprintoch s hotovým prírastkom na konci. |
| **Šprint** | Obdobie najviac jedného mesiaca (často 2 týždne) v Scrume. |
| **Product Goal** | Dlhodobý cieľ produktu v Scrume. |
| **Sprint Goal** | Jeden cieľ šprintu – prečo je šprint užitočný. |
| **Product Owner (PO)** | Zodpovedá za hodnotu produktu a poradie práce; jediný môže zrušiť šprint. |
| **Product / Sprint Backlog** | Zoznam všetkej práce na produkte / práce vybranej na šprint. |
| **Definition of Done** | Kedy je prírastok hotový z hľadiska kvality. Nehovorí, či pomohol používateľom. |
| **Kontrola súbehu** | Zabezpečí, aby si dvaja ľudia naraz nezarezervovali ten istý termín. |
| **Vlastník cieľa** | Človek, ktorý za cieľ zodpovedá a schvaľuje jeho zmeny. |
| **Zelený report / melónový report** | Stav hlásený farbou; melón = zelený navonok, červený vnútri. |

---

## Otázky k celej téme (na diskusiu po prezentácii)

**Čo je na celej téme najdôležitejšie?**
Rozlíšiť výstup od výsledku. Keď vieme, že úspech je zmena pre používateľa, zvyšok (SMART, OKR, pravidlá zmien) sú nástroje, ako tú zmenu zapísať, sledovať a ustrážiť.

**Prečo potrebujeme OKR, keď máme SMART?**
Nemusíme vždy. SMART kontroluje formuláciu jedného cieľa, OKR organizuje smer a priority. OKR sa oplatí, keď treba zosúladiť viac priorít alebo tímov. Malému tímu môže stačiť SMART.

**Nie je zmena cieľa iba ospravedlnenie neúspechu?**
Môže byť, ak nemá dôkaz a záznam. Legitímna zmena má dôvod (zmenila sa potreba), overené meranie, schválenie vlastníkom a históriu – pôvodný cieľ aj odchýlka ostanú zapísané.

**Majú byť ciele pevné, alebo flexibilné?**
Závisí od úrovne a od neistoty. Účel a dlhodobý cieľ držíme stabilné, prácu meníme často. Pri zmluve alebo zákonnom termíne pevnejšie, pri novom produkte s neznámymi používateľmi častejšia revízia.

**Čo keď výsledok nie je pod kontrolou tímu?**
Väčšina výsledkov nie je úplne. Pomenujeme, čo tím ovplyvní a čo nie (napr. počet voľných termínov), a sledujeme výsledky spolu s tým, čo sme dodali. Zmenu čísla nevydávame automaticky za dôkaz, že ju spôsobil náš formulár.

**Nevedie meranie k tomu, že ľudia obchádzajú pravidlá?**
Môže – to je Goodhartov zákon a varovanie Ordóñeza a kol. Preto ochranné metriky, viac než jeden KR a nemenné definície počas merania.

**Ako viete, že 85 % je realistických?**
Nevieme, je to modelový predpoklad. V reálnom projekte by sme ho overili baseline, analýzou prekážok a pilotom. Samotné číslo nestačí na splnenie písmena A.

**Môže sa Sprint Goal počas šprintu meniť?**
Mení sa rozsah práce, nie Sprint Goal. Ak cieľ šprintu prestane mať zmysel, Product Owner môže šprint zrušiť.

**Dokazuje váš príklad, že SMART alebo OKR fungujú?**
Nie. Ukazuje, ako sa ciele formulujú a ako sa rozhoduje pri zmene. Na dôkaz účinnosti by sme potrebovali skutočný výskum s dátami.

**Odkiaľ máte príklad?**
Je vymyslený, ale typický – zámerne jednoduchý, aby bolo jasné, čo ilustruje. Rovnaký príklad použijeme aj v eseji.

---

## Ťahák na jednu stranu

| # | Slajd | Jedna veta |
|---|---|---|
| 1 | Úvod | Tím 5, manažment cieľov; je hotová úloha aj splnený cieľ? |
| 2 | O čom budeme hovoriť | Ako riadiť ciele, aby sme menili postup a nestratili účel – čo je cieľ, ako ho napísať, ako s ním žiť. |
| 3 | Formulár je hotový | Účel → cieľ → meradlo → úloha. Formulár hotový, študenti stále volajú. Úloha splnená, cieľ nie. |
| 4 | Výstup nie je výsledok | Output = čo sme urobili, outcome = čo sa zmenilo. Jasný cieľ pomáha (Locke a Latham), úzky škodí (Ordóñez) → ochranná metrika. |
| 5 | SMART | „Zlepšiť systém“ → „do konca pilotu zo 60 % na 85 % bez pomoci“. A je slabé miesto – overí pilot. |
| 6 | OKR | Objective = smer, KR = 60→85 %, 120→60 min, iniciatívy sa menia. KR meria zmenu, nie aktivitu. |
| 7 | SMART a OKR spolu | SMART: je cieľ jasný? OKR: čo je priorita? OKR dá smer, SMART spresní KR. |
| 8 | Horizonty | Účel (roky) → Product Goal (mesiace) → Sprint Goal (2 týždne) → práca (denne). Hore stabilné, dole flexibilné. |
| 9 | Štyri otázky | Je cieľ dôležitý? Meriame správne? Zlyhal cieľ, alebo cesta? Kto rozhodne a zapíše? Revízia podľa neistoty. |
| 10 | Tri situácie | Formulár nepomohol → zmeniť riešenie. Povinné schvaľovanie → zmeniť cieľ. Meškanie → zmeniť plán. Nikdy potichu číslo. |
| 11 | Záver | Cieľ = zmena; SMART + OKR; stabilný smer, flexibilná cesta. Pevný ≠ nemenný, flexibilný ≠ bez zodpovednosti. |

**Ako sa to učiť:** najprv si prečítaj „Tému v kocke“ a zapamätaj si odpoveď v troch vetách. Potom si nakresli na papier príklad s rezerváciami (účel → cieľ → meradlo → úloha) – keď ho vieš, vieš vysvetliť skoro každý slajd. Potom si každý slajd povedz nahlas vlastnými slovami podľa stĺpca „Jedna veta“; kde sa zasekneš, prečítaj si vysvetlivky. Nakoniec si nechaj klásť otázky zo sekcií „Ak sa niekto spýta“.
