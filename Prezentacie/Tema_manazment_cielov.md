# Manažment cieľov v softvérovom projekte – téma v skratke

Tím 5 · Adam Svitek, Nikolas Knapík · streda 13:00 – 14:00

Krátke vysvetlenie témy na naučenie. Ide v rovnakej logike ako prezentácia: **čo je cieľ → ako ho zapísať → ako s ním pracovať, keď sa projekt mení**. Celý čas používame jeden vymyslený príklad: **rezervačný systém konzultácií pre študentov**. Čísla v ňom sú modelové.

---

## O čo v téme ide

Softvérový tím je stále zaneprázdnený: robí úlohy, zatvára tickety, nasadzuje nové verzie. Z toho ešte nevyplýva, že tá práca niečomu pomáha. Tím môže mať všetky úlohy hotové, a používateľom sa aj tak nič nezlepší.

Manažment cieľov rieši, **kam má práca smerovať, ako spoznáme, že sme tam došli, a čo robiť, keď sa po ceste niečo zmení**. V softvéri sa totiž mení skoro všetko: požiadavky, pravidlá, poznatky o používateľoch. Ťažisko témy je preto v napätí medzi dvomi vecami:

- keď cieľ **nikdy nemeníme**, robíme niečo, čo už nikto nepotrebuje,
- keď ho **meníme stále**, nemáme žiadny smer a každý neúspech sa dá „vyriešiť“ premenovaním cieľa.

**Hlavná otázka:** Ako stanoviť a priebežne riadiť ciele, aby tím vedel meniť postup a pritom nestratil účel projektu?

---

## 1. Čo je cieľ – a čo ním nie je

Cieľ je **stav, ktorý chceme dosiahnuť**, nie činnosť. Najlepšie to vidno na reťazi štyroch pojmov:

| Pojem | Otázka | V príklade |
|---|---|---|
| **Účel** | Prečo produkt existuje? | menej ručnej práce pre administrátora |
| **Cieľ** | Aký stav chceme dosiahnuť? | študent sa objedná sám, bez pomoci |
| **Meradlo** | Ako spoznáme pokrok? | podiel rezervácií dokončených bez pomoci |
| **Úloha** | Čo urobíme? | nový rezervačný formulár |

Úloha je len **stávka**: myslíme si, že nový formulár pomôže. Keď je formulár hotový, ale študenti stále volajú administrátorovi, **úloha je splnená a cieľ nie**.

S tým súvisí rozdiel medzi **výstupom a výsledkom**:
- **výstup (output)** = čo sme vytvorili: formulár, testy, uzavreté úlohy,
- **výsledok (outcome)** = čo sa zmenilo pre používateľa: viac študentov sa objedná samo.

Úspech meriame výsledkom. Tímy sa však radšej pozerajú na výstupy, lebo hotové úlohy sa dajú ľahko spočítať.

**Prečo ciele vôbec stanovovať.** Psychológovia **Locke a Latham (2002)** zhrnuli desaťročia výskumu a zistili, že **konkrétny a náročný cieľ** vedie k lepšiemu výkonu než „urobte, čo sa dá“. Cieľ usmerní pozornosť a zvýši úsilie aj vytrvalosť. Platí to však len vtedy, keď ľudia cieľ prijmú a dostávajú spätnú väzbu. Pri úplne novej a zložitej úlohe je lepší **cieľ učenia** („zistime, prečo študenti nedokončia rezerváciu“) než hneď číslo.

**Kde majú ciele hranice.** **Ordóñez a kol. (2009)** upozorňujú, že príliš úzky cieľ vytlačí všetko, čo sa nemeria, napríklad kvalitu. Keď sa sleduje iba jedno číslo, ľudia ho zlepšia aj nesprávnym spôsobom. Preto k cieľu pridávame **ochrannú metriku**, teda niečo, čo sa nesmie zhoršiť. V príklade: *nesmú vzniknúť dvojité rezervácie*.

---

## 2. Ako cieľ zapísať: SMART a OKR

### SMART – je jeden cieľ jasný?

SMART je kontrolný zoznam piatich písmen. Neurčitý cieľ *„Zlepšiť rezervačný systém“* sa nedá vyhodnotiť, lebo nikto nevie, kedy je hotový. Podľa SMART ho prepíšeme takto:

> Do konca 8-týždňového pilotu zvýšime podiel rezervácií, ktoré študent dokončí bez pomoci, zo 60 % na 85 %.

- **S – Specific (konkrétny):** čo a pre koho, tu samostatná rezervácia študenta.
- **M – Measurable (merateľný):** z akej hodnoty na akú, teda zo 60 % (**východisko**, baseline) na 85 %.
- **A – Achievable (dosiahnuteľný):** je to reálne? 85 % je zatiaľ len predpoklad a overí ho až pilot.
- **R – Relevant (relevantný):** pomáha to účelu? Áno, šetrí to prácu administrátora.
- **T – Time-bound (s termínom):** dokedy? Do konca pilotu.

SMART **kontroluje iba to, ako je cieľ napísaný**, nie či je múdry. Aj nezmyselný cieľ môže byť „správne SMART“. SMART tiež nehovorí, ktorý cieľ je dôležitejší. Pôvodne skratku navrhol Doran (1981) s trochu inými slovami, napríklad *Assignable* a *Realistic*.

### OKR – kam smerujeme a ako spoznáme pokrok?

OKR (**Objectives and Key Results**) používa napríklad Google. Má tri vrstvy:

- **Objective** = smer, povedaný slovami, bez čísla: *Rezervovanie konzultácie je pre študentov samostatné a spoľahlivé.*
- **Key Results** = 2–4 čísla, ktoré dokazujú pokrok:
  - samostatne dokončené rezervácie: 60 % → 85 %,
  - čas administrátora na 100 rezervácií: 120 → 60 min.
- **Iniciatívy** = čo skúsime, napríklad jednoduchší formulár alebo test prototypu. Tieto sa **môžu meniť**.

Najčastejšia chyba je zapísať do Key Results úlohy. *„Spustiť nový formulár“* nie je Key Result, ale iniciatíva. **Key Result meria zmenu, nie aktivitu.**

### SMART a OKR sa dopĺňajú

| | SMART | OKR |
|---|---|---|
| Pýta sa | Je tento jeden cieľ jasný a overiteľný? | Čo je teraz prioritou a ako spoznáme pokrok? |
| Riziko | formálne správny, ale nedôležitý cieľ | Key Results, ktoré iba premenujú úlohy |

**OKR určí smer a priority, SMART spresní každý Key Result.** Malému tímu s jedným cieľom však často stačí samotný SMART a pravidelná dohoda. Plné OKR sa oplatí, keď treba zosúladiť viac priorít alebo tímov.

---

## 3. Ako s cieľom pracovať, keď sa projekt mení

### Ciele majú rôzne horizonty

| Úroveň | Príklad | Ako často sa mení |
|---|---|---|
| Účel produktu | menej ručnej práce pre administrátora | roky |
| **Product Goal** (dlhodobý cieľ v Scrume) | samostatná a spoľahlivá rezervácia | mesiace |
| **Sprint Goal** (cieľ jedného šprintu) | študent vidí voľné termíny a dokončí rezerváciu | 2 týždne |
| Práca v šprinte | UI, API, testy | denne |

**Čím vyššie, tým stabilnejšie. Čím nižšie, tým flexibilnejšie.** Stabilita a flexibilita sa teda nevylučujú, každá patrí na inú úroveň. To je odpoveď na otázku z abstraktu, či majú byť ciele pevné, alebo flexibilné.

Scrum Guide (2020) to hovorí priamo: počas šprintu sa môže upraviť rozsah práce, ak tým neohrozíme Sprint Goal. Keď Sprint Goal stratí zmysel, šprint môže zrušiť iba Product Owner.

### Kedy zmeniť samotný cieľ – štyri otázky

Toto je **náš vlastný návrh** (syntéza), nie prevzatá metodika:

1. **Je cieľ stále dôležitý?** Rieši ešte skutočnú potrebu?
2. **Meriame správne?** Nie je chyba v dátach, v definícii alebo v malej vzorke?
3. **Zlyhal cieľ, alebo cesta?** Ak zlyhalo riešenie, meníme iniciatívu, nie cieľ.
4. **Kto rozhodne a zapíše?** Zmenu schváli vlastník cieľa a pôvodný cieľ ostane v histórii.

Ako často ciele prehodnocovať, závisí od toho, **koľko toho ešte nevieme**:
- pri zmluve, zákonnom termíne alebo bezpečnosti držíme cieľ **pevnejšie**,
- pri novom produkte, keď nepoznáme používateľov, ho revidujeme **častejšie**.

Agilný manifest síce víta zmeny, ale z toho nevyplýva, že cieľ treba meniť pri každej požiadavke.

### Tri situácie, tri rozhodnutia

| Situácia | Čo prestalo platiť | Rozhodnutie |
|---|---|---|
| **A** Nový formulár nepomohol, študenti nevidia voľné termíny. | riešenie | **ponechať cieľ**, zmeniť riešenie |
| **B** Škola zaviedla povinné schvaľovanie každej rezervácie. | samotná potreba | **upraviť cieľ**: samostatná žiadosť a rýchle schválenie |
| **C** Tím mešká, potreba sa nezmenila. | plán | **upraviť plán**: zúžiť rozsah alebo otvorene preplánovať |

Čo sa nesmie: **potichu znížiť číslo, aby report vyzeral zelene.** Pôvodný cieľ aj odchýlka musia ostať zapísané. Je to rovnaký „melónový report“ ako pri téme 1: zelený navonok, červený vnútri.

---

## Celá téma v troch vetách

1. **Cieľ je zmena, nie úloha.** Úspech meriame tým, čo sa zmenilo pre používateľa, nie počtom hotových úloh.
2. **SMART a OKR sa dopĺňajú.** OKR dáva smer a priority, SMART spresní, kedy sme uspeli.
3. **Stabilný smer, flexibilná cesta.** Plán meníme často, cieľ iba s dôkazom, vlastníkom a záznamom.

> Pevný cieľ neznamená nemenný navždy. Flexibilný cieľ neznamená bez zodpovednosti.
