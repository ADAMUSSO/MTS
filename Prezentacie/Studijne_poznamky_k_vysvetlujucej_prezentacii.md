# Študijné poznámky – Manažment komunikácie (vysvetľujúca verzia)

Tím 5 · Adam Svitek, Nikolas Knapík · streda 13:00 – 14:00

Tieto poznámky sú na **naučenie sa témy**, nie na čítanie počas prezentácie. Krátky text, ktorý sa hovorí nahlas, je v súbore `Poznamky_k_vysvetlujucej_prezentacii.md` a v poznámkach v pptx. Tu je ku každému slajdu:

- **Hlavná myšlienka** – jedna veta, ktorú si musí publikum zapamätať. Ak zabudneš všetko ostatné, povedz aspoň ju.
- **Čo povedať** – body v poradí, v akom idú na slajde.
- **Vysvetlivky** – pozadie a pojmy, aby si vedel, *prečo* to tak je, a vedel to povedať aj inými slovami.
- **Ak sa niekto spýta** – pravdepodobné otázky a krátke odpovede.
- **Prechod** – veta, ktorou sa dostaneš na ďalší slajd.

Na konci je slovník pojmov, otázky k celej téme a ťahák na jednu stranu.

Rozdelenie: **Adam** slajdy 1–5 a 15, **Nikolas** slajdy 6–14. Celková dĺžka asi 8:00 – 8:15.

---

## Celá prezentácia v troch vetách

1. Komunikácia v projekte znamená **porozumenie**, nie odoslanie správy – a v softvéri je ťažká, lebo ľudí a spojení je veľa, softvér nie je vidieť a každý hovorí iným jazykom.
2. Komunikáciu treba **riadiť** ako cyklus: naplánovať (kto čo potrebuje), robiť (reporty, demá, rozhodnutia) a kontrolovať, či pomáha.
3. Keď je projektov viac, komunikáciu medzi nimi drží **PMO** – a jeho typ (podporné, riadiace, direktívne) vyberáme podľa problému, ktorý má riešiť.

Celá prezentácia je postavená na jednej otázke zo slajdu 2: *Ako zabezpečiť, aby si ľudia v projekte naozaj rozumeli – a ako s tým pomáha PMO?* Každý slajd na ňu odpovedá kúskom. Keď sa stratíš, vráť sa k tejto otázke.

---

## Slajd 1 – Úvodný slajd · Adam · 15 s

**Hlavná myšlienka:** Predstavíme tému a povieme, že ju budeme vysvetľovať na príkladoch, nie na číslach.

**Čo povedať**
- Kto sme: tím 5, Adam Svitek a Nikolas Knapík.
- Téma: manažment komunikácie v softvérovom projekte a kancelária projektového manažmentu (PMO).
- Prístup: nechceme ukazovať prieskumy a percentá, ale vysvetliť, ako komunikácia v projekte naozaj funguje a kde sa kazí.

**Vysvetlivky**
- **Manažment komunikácie** je jedna z oblastí projektového manažmentu podľa PMBOK (popri rozsahu, čase, nákladoch, kvalite, rizikách, ľuďoch atď.). Nejde o „mäkkú zručnosť“ navyše – je to riadená súčasť projektu s vlastným plánom.
- **PMO** (Project Management Office) = kancelária projektového manažmentu. Podrobne na slajdoch 10–14.
- Prečo „vysvetľujúca“ verzia: máme aj pôvodnú prezentáciu postavenú na číslach. Táto stavia na príkladoch a prirovnaniach, aby ju pochopil aj niekto, kto o téme nič nevie.

**Prechod:** „Začneme tým, na akú otázku chceme dnes odpovedať.“

---

## Slajd 2 – O čom dnes budeme hovoriť · Adam · 20 s

**Hlavná myšlienka:** Celá prezentácia odpovedá na jednu otázku a ide v troch krokoch.

**Čo povedať**
- Otázka: *Ako zabezpečiť, aby si ľudia v projekte naozaj rozumeli – a ako s tým pomáha kancelária projektového manažmentu?*
- Tri kroky:
  1. **Čo je komunikácia v projekte** – čo sa deje so správou na ceste od jedného človeka k druhému a prečo je to v softvéri ťažké.
  2. **Ako ju riadiť a sledovať, či funguje** – plán, každodenné riadenie, kontrola.
  3. **Kancelária projektového manažmentu** – čo robí, keď projektov je viac, a aké typy existujú.

**Vysvetlivky**
- Slovo **„naozaj“** je dôležité. Ľudia v projekte si správy posielajú neustále – e-maily, tickety, porady. Problém nie je, že by nekomunikovali, ale že si často *myslia*, že si rozumejú, a nerozumejú. Na to je slajd 3.
- Poradie krokov ide od jedného človeka (správa) cez jeden projekt (riadenie) po celú organizáciu (PMO). Môžeš to tak aj povedať: „od jednej vety, cez jeden projekt, po celú firmu“.

**Prechod:** „Začnime jednou vetou z ticketu.“

---

## Slajd 3 – Rovnaké slová môžu mať iný význam · Adam · 45 s

**Hlavná myšlienka:** Komunikácia nekončí odoslaním správy, ale až keď ju príjemca pochopí a vie podľa nej konať – a to zistíme iba zo spätnej väzby.

**Čo povedať** (slajd ide zľava doprava, päť krokov)
1. **Odosielateľ** má v hlave zámer a kontext → klient má na mysli účtovníčku, ktorá raz mesačne potrebuje tabuľku faktúr v Exceli.
2. **Kódovanie** – zámer zmení na slová → napíše iba „jednoduchý export“.
3. **Kanál a šum** – správa ide e-mailom, chatom, ticketom → jedna veta v tickete, bez príkladu. Šum = to, čo chýba alebo ruší (tu chýba príklad a kontext).
4. **Dekódovanie** – príjemca si to vyloží podľa seba → vývojár urobí CSV súbor cez API. Technicky správne, pre účtovníčku nepoužiteľné.
5. **Spätná väzba** – overí, či sme si rozumeli → „Ukážem vám návrh – myslíte takto?“ Odpoveď ide späť k odosielateľovi.
- Pointa (spodný riadok slajdu): komunikácia končí až porozumením a to zistíme zo spätnej väzby.

**Vysvetlivky**
- Toto je **model odosielateľ – príjemca** (sender–receiver model). Pochádza z teórie informácie (Shannon a Weaver, 1949), kde riešili prenos signálu telefónnou linkou. PMBOK ho preberá a pridáva k nemu potvrdenie a spätnú väzbu. Netreba citovať Shannona – stačí vedieť, že je to klasický model a PMBOK ho používa.
- **Kódovanie** = premena myšlienky na slová, obrázok, dokument. Pri kódovaní sa vždy niečo stratí – človek napíše iba to, čo mu príde podstatné, a zvyšok považuje za „jasný“.
- **Šum** nie je iba hluk. Je to všetko, čo sťažuje pochopenie: chýbajúci kontext, nejasné slová, rôzne jazyky, únava, príliš veľa správ naraz, zlý kanál.
- **Dekódovanie** = príjemca si správu vyloží podľa *svojich* skúseností. Vývojár počuje „export“ a predstaví si technické riešenie (CSV, API), lebo tak rozmýšľa celý deň.
- **CSV** = textový súbor s hodnotami oddelenými čiarkou; dá sa otvoriť v Exceli, ale bežný používateľ s ním často nevie pracovať (zlé kódovanie diakritiky, oddeľovače). **API** = rozhranie, cez ktoré si dáta berie iný program, nie človek. Preto je to pre účtovníčku nepoužiteľné.
- Prečo práve **spätná väzba**: je to jediný krok, kde odosielateľ zistí, či sa jeho zámer dostal na druhú stranu. Bez nej sa chyba ukáže až pri odovzdaní – teda najneskôr a najdrahšie.
- V praxi sa spätná väzba robí cez prototyp, náčrt obrazovky, ukážku výstupu („takto by vyzeral export, sedí to?“) alebo zopakovanie zadania vlastnými slovami.

**Ak sa niekto spýta**
- *„Nie je to chyba klienta, že to napísal zle?“* – Nie je to o vine. Obaja urobili, čo bolo prirodzené. Klientovi to bolo jasné, vývojár to pochopil po svojom. Preto komunikácia potrebuje proces (spätnú väzbu), nie lepších ľudí.
- *„Čo s tým urobiť hneď na začiatku?“* – Do zadania dať konkrétny príklad (akceptačné kritérium, napr. „súbor .xlsx so stĺpcami číslo faktúry, dátum, suma“) a čo najskôr ukázať návrh.

**Prechod:** „Toto sa môže stať v akejkoľvek práci. Prečo je to v softvérovom projekte ešte ťažšie?“

---

## Slajd 4 – Prečo je to v softvérovom projekte ťažké · Adam · 40 s

**Hlavná myšlienka:** Softvérový projekt má tri vlastnosti, ktoré komunikáciu sťažujú: veľa odovzdaní, neviditeľný produkt a rôzne „jazyky“.

**Čo povedať**
1. **Veľa odovzdaní** – každý nový človek pridá spojenie s každým, kto už v tíme je. Informácia ide cez viac rúk a pri každom odovzdaní sa môže skresliť.
   - 3 ľudia = 3 spojenia, 5 ľudí = 10 spojení, 8 ľudí = 28 spojení.
   - Vzorec: n · (n − 1) / 2. Počet spojení rastie rýchlejšie než počet ľudí.
   - Preto pridanie ľudí do meškajúceho projektu často nepomôže.
2. **Softvér nie je vidieť** – kým nie je hotový, každý si ho predstavuje inak. Preto pomáhajú prototypy a demá.
3. **Každý hovorí iným jazykom** – biznis o cieľoch, vývoj o riešení, vedenie o peniazoch a termínoch.

**Vysvetlivky**
- **Prečo n · (n − 1) / 2:** Každý z n ľudí sa môže rozprávať s n − 1 ostatnými. To je n · (n − 1) dvojíc, ale každú dvojicu sme započítali dvakrát (Adam–Nikolas aj Nikolas–Adam), preto delíme dvoma.
  - Overenie: 5 ľudí → 5 · 4 / 2 = 10. 8 ľudí → 8 · 7 / 2 = 28. 10 ľudí → 45. 20 ľudí → 190.
  - Z 5 na 8 ľudí (o 60 % viac ľudí) narastie počet spojení z 10 na 28 (takmer trojnásobok). Rastie to zhruba s druhou mocninou počtu ľudí (kvadraticky).
  - Tento vzorec uvádza aj PMBOK ako ukážku, prečo zložitosť komunikácie rastie s veľkosťou tímu. Je to **ilustrácia**, nie meranie – nie každý sa reálne rozpráva s každým.
- **„Pridanie ľudí do meškajúceho projektu často nepomôže“** je tzv. **Brooksov zákon** z knihy *The Mythical Man-Month* (Fred Brooks, 1975). Originál: „Pridanie ľudí do meškajúceho softvérového projektu ho ešte viac oneskorí.“ Dôvody: noví ľudia sa musia zaučiť (zaberú čas skúseným), pribudnú komunikačné spojenia a nie každá práca sa dá rozdeliť (deväť žien neporodí dieťa za mesiac – príklad z tej knihy). Na slajde je to zámerne zmiernené na „často nepomôže“.
- **Softvér nie je vidieť:** most alebo dom vidno, ako rastie. Softvér je do poslednej chvíle iba kód, ktorému rozumejú vývojári. Klient a vedenie si ho preto predstavujú podľa seba a nezhody sa ukážu neskoro. **Prototyp** (náčrt alebo klikateľný model) a **demo** (ukážka hotovej časti) robia softvér viditeľným skôr.
- **Rôzne jazyky:** podrobne na slajde 8. Tu stačí zmieniť – Nikolas to neskôr rozvinie.

**Ak sa niekto spýta**
- *„Takže veľké tímy nefungujú?“* – Fungujú, ale potrebujú štruktúru: rozdelenie na menšie tímy (napr. Scrum odporúča tímy do 10 ľudí), jasné rozhrania medzi nimi a ľudí, ktorí informácie prenášajú. Čiže presne to, čo riadenie komunikácie robí.
- *„Odkiaľ je ten vzorec?“* – Je to bežná kombinatorika (počet dvojíc z n prvkov) a PMBOK ho používa na počítanie komunikačných kanálov.

**Prechod:** „Keď už vieme, že správa sa môže cestou pokaziť, ďalšia otázka je, akým kanálom ju poslať.“

---

## Slajd 5 – Správny kanál pre správnu správu · Adam · 40 s

**Hlavná myšlienka:** Čím je správa nejasnejšia alebo citlivejšia, tým živší kanál potrebuje.

**Čo povedať** (tri stĺpce)
- **Interaktívna** (⇆) – stretnutie, hovor, demo. Ako telefonát: obe strany sa môžu hneď pýtať. Keď treba niečo vyjasniť, rozhodnúť alebo vyriešiť spor.
- **Push** (→) – e-mail, report, release notes. Ako list do schránky: pošlem to konkrétnym ľuďom. Keď musia niečo vedieť hneď. Ale doručené ešte neznamená prečítané.
- **Pull** (←) – wiki, backlog, dashboard. Ako knižnica: človek si to nájde sám, keď to potrebuje. Funguje, len ak je to aktuálne.
- Pravidlo a príklady dole: stav buildu → dashboard, nová verzia → release notes, spor o priority → stretnutie.

**Vysvetlivky**
- Rozdelenie **interaktívna / push / pull** je priamo z PMBOK (tzv. communication methods).
  - **Push** = odosielateľ informáciu „tlačí“ k príjemcovi. Výhoda: dostane sa ku konkrétnym ľuďom. Nevýhoda: nevieš, či ju prečítali a pochopili.
  - **Pull** = príjemca si informáciu „ťahá“ sám. Vhodné pre veľa ľudí a veľa informácií (dokumentácia, znalostná báza). Nevýhoda: nikto ťa neupozorní a ak je to zastarané, ľudia prestanú veriť.
  - **Interaktívna** = viac strán si vymieňa informácie naraz, v reálnom čase. Najdrahšia (zaberá čas viacerým ľuďom), ale jediná, kde sa nejasnosti vyriešia hneď.
- Pravidlo „čím nejasnejšia správa, tým živší kanál“ vychádza z **teórie bohatosti médií** (media richness theory, Daft a Lengel, 1986). „Bohaté“ médium (osobné stretnutie) prenáša aj tón hlasu, mimiku, umožňuje okamžitú spätnú väzbu a otázky. „Chudobné“ médium (dokument, tabuľka) prenáša iba text. Pre rutinné, jednoznačné správy stačí chudobné médium, pre nejasné a citlivé treba bohaté.
- Pojmy z príkladov:
  - **Build** = zostavenie programu zo zdrojového kódu. „Stav buildu“ = či sa to podarilo (zelený/červený). Je to rutinná, jednoznačná informácia → stačí dashboard.
  - **Release notes** = poznámky k vydaniu: čo je v novej verzii nové a čo sa opravilo. Treba to doručiť konkrétnym ľuďom → push.
  - **Spor o priority** = dvaja ľudia chcú, aby sa robilo niečo iné prvé. E-mailom sa to iba vyostrí → stretnutie.
  - **Dashboard** = prehľadová obrazovka s aktuálnymi údajmi. **Wiki** = zdieľaná dokumentácia (napr. Confluence). **Backlog** = zoradený zoznam úloh, ktoré sa majú urobiť.

**Ak sa niekto spýta**
- *„Nie je najlepšie všetko riešiť stretnutím?“* – Nie, stretnutia sú drahé (hodina × počet ľudí) a pri rutinných veciach zbytočné. Ide o to, zvoliť kanál podľa správy.
- *„Kam patrí chat (Teams, Slack)?“* – Je na hranici. Rýchla otázka a odpoveď je skoro interaktívna; správa do veľkého kanála, ktorú si ľudia prečítajú neskôr, funguje ako push.

**Prechod (odovzdanie Nikolasovi):** „Teraz vieme, čo je komunikácia a akými kanálmi ide. Nikolas vysvetlí, ako ju v projekte riadiť.“

---

## Slajd 6 – Riadenie komunikácie je cyklus troch krokov · Nikolas · 40 s

**Hlavná myšlienka:** Riadenie komunikácie má tri kroky – plánovanie, riadenie, monitorovanie – a tvoria cyklus, nie jednorazovú úlohu.

**Čo povedať**
1. **Plánovanie** – „Kto čo potrebuje vedieť, kedy a ako?“ Na začiatku projektu sa spíše komunikačný plán.
2. **Riadenie** – „Deje sa to naozaj?“ Reporty vznikajú, demo prebehne, rozhodnutia sú zapísané a dostanú sa k ľuďom.
3. **Monitorovanie** – „Pomáha to?“ Pýtame sa ľudí, či majú, čo potrebujú. Ak report nikto nečíta, zmeníme ho.
- Šípka späť: čo zistíme pri monitorovaní, vrátime do plánu.

**Vysvetlivky**
- Tri kroky sú tri procesy z PMBOK (6. vydanie, kapitola 10 – Project Communications Management):
  - **Plan Communications Management** (plánovanie riadenia komunikácie) – výstup je komunikačný plán.
  - **Manage Communications** (riadenie komunikácie) – zbieranie, vytváranie, rozosielanie a ukladanie informácií podľa plánu.
  - **Monitor Communications** (monitorovanie komunikácie) – kontrola, či sa potreby zainteresovaných strán naozaj napĺňajú.
- Prečo **cyklus**: projekt sa mení – pribudnú ľudia, zmení sa sponzor, nový klient chce iné reporty. Plán napísaný na začiatku a zabudnutý v šuplíku po pár týždňoch nesedí. Monitorovanie hľadá, kde plán nesedí, a opravuje ho. Rovnaká logika ako PDCA (Plan–Do–Check–Act) v riadení kvality.
- Príklad s reportom, ktorý nikto nečíta, je typický: tím každý piatok posiela 10-stranový report, sponzor si prečíta iba prvý odsek. Riešenie nie je posielať ho dôraznejšie, ale zmeniť ho (1 strana: stav, riziká, čo treba rozhodnúť).
- Ako zistiť, či komunikácia funguje (ak sa niekto spýta): opýtať sa ľudí (krátky prieskum, retrospektíva), sledovať, či sa rozhodnutia robia včas, či sa tie isté otázky neopakujú, či sa problémy neobjavujú prekvapivo neskoro.

**Ak sa niekto spýta**
- *„Robí sa to aj v agilných projektoch?“* – Áno, len menej formálne. Napr. v Scrume sú pravidelné udalosti (daily, review, retrospektíva) vlastne zabudovaný komunikačný plán a retrospektíva je monitorovanie.

**Prechod:** „Ako taký plán vyzerá v praxi?“

---

## Slajd 7 – Komunikačný plán môže byť jednoduchá tabuľka · Nikolas · 35 s

**Hlavná myšlienka:** Komunikačný plán nemusí byť hrubý dokument – stačí tabuľka „kto, čo, ako často, akým kanálom, kto zodpovedá“, ktorá začína od ľudí, nie od nástrojov.

**Čo povedať** (riadky tabuľky)
- **Sponzor a vedenie** – stav, riziká, čo treba rozhodnúť; raz za 2 týždne; krátky report + stretnutie; zodpovedá projektový manažér.
- **Klient / Product Owner** – čo je hotové, čo sa mení; každý šprint; demo; zodpovedá Product Owner.
- **Vývojári a testeri** – úlohy, blokery, chyby; denne; daily, Jira; celý tím.
- **Prevádzka** – čo a kedy sa nasadí; pri každom vydaní; release notes; tech lead.
- Dve pravidlá dole: **začína sa od ľudí, nie od nástrojov** a plán obsahuje **eskalačnú cestu**.

**Vysvetlivky**
- **Sponzor** = človek (zvyčajne z vedenia), ktorý projekt financuje a má posledné slovo pri veľkých rozhodnutiach. Nepotrebuje detaily, potrebuje vedieť, čo má rozhodnúť.
- **Product Owner** (zo Scrumu) = človek zodpovedný za to, *čo* sa vyvíja a v akom poradí. Spravuje backlog a zastupuje záujmy klienta voči tímu.
- **Šprint** = krátke obdobie (zvyčajne 1–4 týždne), na konci ktorého tím odovzdá hotovú časť produktu.
- **Daily** (Daily Scrum) = krátke denné stretnutie tímu (do 15 min.): čo sa robí, čo blokuje.
- **Bloker** = prekážka, kvôli ktorej sa nedá pokračovať v práci.
- **Jira** = nástroj na správu úloh (ticketov).
- **Prevádzka** (operations, ops) = ľudia, ktorí sa starajú o bežiaci systém. Potrebujú vedieť o nasadeniach, aby boli pripravení, ak niečo spadne.
- **Tech lead** = hlavný technický človek v tíme.
- Stĺpce tabuľky zodpovedajú tomu, čo PMBOK uvádza ako obsah komunikačného plánu: zainteresované strany, aké informácie potrebujú, frekvencia, metóda/kanál, zodpovedná osoba.
- **„Od ľudí, nie od nástrojov“:** častá chyba je začať otázkou „budeme používať Teams alebo Slack?“. Správne poradie: najprv kto čo potrebuje vedieť, potom vybrať nástroj, ktorý to zabezpečí.
- **Eskalačná cesta** = dopredu dohodnuté, komu sa problém posunie, keď sa nedá vyriešiť na nižšej úrovni, a dokedy. Napr. vývojár → tech lead (do 1 dňa) → projektový manažér (do 2 dní) → sponzor. Bez nej sa problémy buď nehlásia, alebo sa hlásia hneď najvyššie.

**Ak sa niekto spýta**
- *„Kto ten plán píše?“* – Projektový manažér, ale spolu so zainteresovanými stranami – musí sa ich opýtať, čo potrebujú.
- *„Nie je to byrokracia?“* – Pri jednej tabuľke so štyrmi riadkami nie. Byrokracia vzniká, keď plán nikto nepoužíva, ale všetci ho musia vypĺňať.

**Prechod:** „Plán hovorí, kto má čo dostať. Ale aj keď to dostane, nemusí tomu rozumieť – lebo každý hovorí iným jazykom.“

---

## Slajd 8 – Každý v projekte hovorí trochu iným jazykom · Nikolas · 35 s

**Hlavná myšlienka:** Projekt potrebuje „prekladateľov“ – Product Owner prekladá cieľ klienta do úlohy pre vývojára a projektový manažér prekladá technický stav do dopadu pre vedenie.

**Čo povedať**
- **Horný riadok:** Klient povie: „Chceme, aby si zákazník vedel sám stiahnuť faktúru.“ → Product Owner preloží cieľ do úlohy → vývojár dostane: „Tlačidlo Stiahnuť PDF pri každej faktúre v profile zákazníka.“
- **Dolný riadok:** Vývojár povie: „Platobný modul má veľký technický dlh.“ → projektový manažér preloží stav do dopadu → vedenie počuje: „Bez dvoch týždňov na opravu bude každá zmena platieb pomalšia a rizikovejšia.“
- Keď tento preklad chýba, vznikajú bariéry (ďalší slajd).

**Vysvetlivky**
- Smer prekladu je opačný:
  - **Zhora nadol** (biznis → vývoj): z *cieľa* (čo chceme dosiahnuť) urobiť *konkrétnu úlohu* (čo presne naprogramovať). Klient vie, čo chce dosiahnuť, ale nevie to opísať tak, aby to vývojár vedel urobiť.
  - **Zdola nahor** (vývoj → vedenie): z *technického stavu* urobiť *dopad na biznis* (čas, peniaze, riziko). Vedenie nezaujíma, *čo* je zle v kóde, ale *čo to znamená* pre firmu a čo má rozhodnúť.
- **Technický dlh** = skratky a provizórne riešenia v kóde, ktoré sa urobili kvôli rýchlosti a „raz sa opravia“. Ako pôžička: teraz ušetríš čas, ale potom platíš „úroky“ – každá ďalšia zmena je pomalšia a rizikovejšia. Preto preklad „každá zmena platieb bude pomalšia a rizikovejšia“ je presne ten úrok.
- Prečo vedenie nerozumie vete o technickom dlhu: nevie, či je to drobnosť alebo katastrofa, a nevie, čo od neho chcete. Preložená veta hovorí cenu (2 týždne), dopad (pomalšie a rizikovejšie zmeny) a implicitne žiada rozhodnutie.
- Prekladateľom nemusí byť iba PO alebo PM – v praxi to robí aj biznis analytik, tech lead alebo ktokoľvek, kto rozumie obom stranám.

**Ak sa niekto spýta**
- *„Prečo sa vývojár a klient nerozprávajú priamo?“* – Môžu a je to dobré. Ale niekto musí zodpovedať za to, aby zo stretnutia vznikla jasná úloha, a za poradie úloh. To je rola PO.

**Prechod:** „Keď preklad chýba, vznikajú typické bariéry. Ukážeme tri.“

---

## Slajd 9 – Tri typické bariéry a ako ich obísť · Nikolas · 40 s

**Hlavná myšlienka:** Tri najčastejšie bariéry – nejasné zadanie, technický text pre vedenie a chýbajúca spätná väzba – majú jednoduché a konkrétne riešenia.

**Čo povedať** (tabuľka: bariéra → ako to znie → čo pomôže)
1. **Nejasné zadanie** – „Veď je jasné, čo chceme.“ → akceptačné kritériá s konkrétnym príkladom, prototyp a demo po každom šprinte.
2. **Technický text pre vedenie** – „Padá nám migrácia DB a CI pipeline je červená.“ → povedať dopad a čo treba rozhodnúť: „Vydanie sa posunie o týždeň, potrebujeme vaše áno.“
3. **Chýbajúca spätná väzba** – „Myslel som, že to už niekto otestoval.“ → zopakovať zadanie vlastnými slovami, uzatvárať tickety a nebáť sa povedať zlú správu.
- Doplň ústne: inak vzniká **melónový report** – zelený navonok, červený vo vnútri.

**Vysvetlivky**
- **Akceptačné kritériá** = podmienky, ktoré musí úloha splniť, aby sa považovala za hotovú. Dobré sú konkrétne a overiteľné, ideálne s príkladom. Napr. namiesto „jednoduchý export“: „Používateľ klikne na Export a stiahne .xlsx súbor so stĺpcami číslo faktúry, dátum, suma, ktorý sa dá otvoriť v Exceli.“ Často sa píšu vo forme *Daný… keď… potom…* (Given–When–Then).
- Bariéra 1 nadväzuje na slajd 3 (export dát) – je to ten istý problém, len pomenovaný ako bariéra.
- **Migrácia DB** = presun dát do novej databázy alebo zmena jej štruktúry. **CI pipeline** = automatický proces, ktorý po každej zmene kódu program zostaví a otestuje (CI = continuous integration). „Červená“ = niečo zlyhalo. Pre vedenie sú to prázdne slová – preto bariéra.
- Bariéra 2 nadväzuje na slajd 8 (preklad zdola nahor). Vzorec dobrej správy pre vedenie: **čo sa stalo (jednou vetou) → aký je dopad → čo od vás potrebujeme.**
- Bariéra 3 – **„Myslel som, že to už niekto otestoval“** je typický príklad rozptýlenej zodpovednosti: každý predpokladá, že to urobil niekto iný. Pomôže jasný vlastník úlohy a uzatváranie ticketov (vieme, čo je naozaj hotové).
- **„Nebáť sa povedať zlú správu“** súvisí s pojmom **psychologická bezpečnosť** (Amy Edmondson, 1999): presvedčenie v tíme, že sa dá priznať chyba, opýtať sa „hlúpu“ otázku alebo povedať nepríjemnú pravdu bez trestu či zosmiešnenia. Edmondson zistila, že tímy s vyššou psychologickou bezpečnosťou sa viac učia z chýb – lebo o nich vôbec hovoria. V komunikácii to znamená, že zlé správy prídu skoro, keď sa ešte dajú riešiť.
- **Melónový report** (watermelon reporting) – stav projektu sa hlási ako „zelený“, lebo nikto nechce byť ten, kto povie, že je zle. Navonok zelený, vo vnútri červený. Pravda vyjde najavo naraz a neskoro. Je to priamy dôsledok chýbajúcej psychologickej bezpečnosti.

**Ak sa niekto spýta**
- *„Ako sa dá zaviesť psychologická bezpečnosť?“* – Začína pri vedúcom: keď niekto povie zlú správu, poďakovať a riešiť problém, nie hľadať vinníka. Retrospektívy bez obviňovania (blameless).

**Prechod:** „Doteraz sme hovorili o jednom projekte. Čo keď ich je vo firme viac naraz? Na to je kancelária projektového manažmentu.“

---

## Slajd 10 – Kancelária projektového manažmentu · Nikolas · 40 s

**Hlavná myšlienka:** PMO je ako riadiaca veža na letisku – každý projekt má svojho „pilota“, ale PMO vidí všetky projekty naraz a stará sa, aby sa nezrazili.

**Čo povedať**
- Definícia (na slajde): PMO je útvar, ktorý zjednocuje, ako sa v organizácii riadia projekty, a podporuje ich metodikou, nástrojmi a ľuďmi.
- Prirovnanie: pilot riadi svoje lietadlo = projektový manažér a jeho projekt. Riadiaca veža vidí všetky lietadlá naraz = PMO.
- Štyri veci, ktoré PMO robí:
  1. **Spoločný jazyk** – rovnaké šablóny a rovnaký význam „zeleného“ stavu vo všetkých projektoch.
  2. **Zdieľaní ľudia** – prehľad, kto na čom robí, aby si projekty nebrali toho istého človeka naraz.
  3. **Jeden prehľad** – porovnateľné správy zo všetkých projektov na jednom mieste.
  4. **Poučenia** – čo sa naučil jeden projekt, ďalší už nemusí opakovať.
- Záver: PMO je vlastne komunikačná infraštruktúra celej organizácie.

**Vysvetlivky**
- **PMO** = Project Management Office. Niekde sa volá aj Program/Portfolio Management Office. Rozdiel netreba vysvetľovať, ale pre istotu:
  - **Projekt** = dočasné úsilie s jasným cieľom a koncom.
  - **Program** = skupina súvisiacich projektov riadených spolu (napr. všetko okolo nového platobného systému).
  - **Portfólio** = všetky projekty a programy firmy, vyberané a riadené podľa stratégie.
- Prečo je PMO o **komunikácii**: všetky štyri funkcie sú v podstate komunikácia medzi projektmi a smerom k vedeniu. Bez PMO každý projekt hlási po svojom, ľudia sa „kradnú“ medzi projektmi a chyby sa opakujú.
- Prepojenie na predošlé slajdy:
  - *Spoločný jazyk* rieši na úrovni firmy to, čo slajd 8 rieši v projekte.
  - *Jeden prehľad* je komunikačný plán (slajd 7) pre vedenie, ale cez všetky projekty.
  - *Poučenia* = **lessons learned** – zaznamenané skúsenosti z projektu (čo fungovalo, čo nie), ktoré sa odovzdajú ďalším projektom.
- **Zdieľaný človek** = špecialista, ktorého potrebuje viac projektov (bezpečnostný tester, architekt, databázový expert). Je ich málo, takže sú úzkym miestom.
- Hobbs a Aubry (2007) skúmali stovky PMO v rôznych organizáciách a zistili, že PMO sa navzájom veľmi líšia – rozsahom, právomocami aj funkciami. Neexistuje jedno „správne“ PMO. To je most k ďalšiemu slajdu.

**Ak sa niekto spýta**
- *„Má PMO každá firma?“* – Nie. Malá firma s jedným-dvoma projektmi ho nepotrebuje. Dáva zmysel, keď beží viac projektov naraz a zdieľajú ľudí alebo peniaze.
- *„Je PMO nadriadený projektovým manažérom?“* – Záleží od typu – to je ďalší slajd.

**Prechod:** „PMO však nie je jedno. Typy sa líšia tým, koľko kontrolujú.“

---

## Slajd 11 – Tri typy PMO sa líšia tým, koľko kontrolujú · Nikolas · 40 s

**Hlavná myšlienka:** Podporné PMO radí, riadiace PMO vyžaduje pravidlá, direktívne PMO priamo riadi – a každé sa hodí na iný problém.

**Čo povedať** (tri stĺpce)
- **Podporné – ako poradca.** Ponúka šablóny, školenia a rady, nikoho nenúti. Hodí sa: málo projektov, skúsení manažéri. Pozor: bez autority ho nikto nepočúva.
- **Riadiace – ako rozhodca s pravidlami.** Vyžaduje spoločnú metodiku a jednotné reporty a kontroluje ich. Hodí sa: projekty si delia ľudí, vedenie chce porovnateľný prehľad. Pozor: ľahko z neho vznikne byrokracia.
- **Direktívne – ako kapitán.** Projekty priamo riadi, manažéri patria pod neho. Hodí sa: strategické a veľmi rizikové projekty. Pozor: drahé, môže sa stať úzkym hrdlom.

**Vysvetlivky**
- Tri typy sú z PMBOK (6. vydanie), ktorý ich rozlišuje podľa **miery kontroly a vplyvu** na projekty:
  - **Supportive (podporné)** – nízka miera kontroly. Funguje ako zdroj: šablóny, osvedčené postupy, školenia, prístup k informáciám a poučeniam z iných projektov.
  - **Controlling (riadiace)** – stredná miera kontroly. Vyžaduje súlad: používanie metodiky, šablón, nástrojov, pravidelné kontroly (audity, revízie).
  - **Directive (direktívne)** – vysoká miera kontroly. Priamo riadi projekty; projektoví manažéri sú pridelení z PMO a zodpovedajú sa mu.
- Ako si to zapamätať – stupnica kontroly: **radí → kontroluje → rozhoduje**.
- Prečo „pozor“ pri každom type:
  - Podporné nemá moc. Keď je manažér pod tlakom termínu, šablónu ignoruje a PMO s tým nič neurobí.
  - Riadiace môže začať vyžadovať formuláre pre formuláre. Ľudia potom vypĺňajú reporty, ktoré nikto nečíta (slajd 6 – monitorovanie by to malo odhaliť).
  - Direktívne potrebuje veľa ľudí (je drahé) a keďže všetko ide cez neho, rozhodnutia sa môžu hromadiť (úzke hrdlo = miesto, kde sa všetko spomalí, lebo tadiaľ musí prejsť všetko).
- Toto nie sú škatuľky, ale body na stupnici. Reálne PMO je často niekde medzi a môže sa časom posúvať.

**Ak sa niekto spýta**
- *„Ktoré je najlepšie?“* – Žiadne samo osebe. Závisí od problému – to ukazujú nasledujúce tri príklady.
- *„Môže firma zmeniť typ PMO?“* – Áno a bežne sa to deje. Hobbs a Aubry zistili, že PMO sa často reorganizujú – zvyčajne po pár rokoch.

**Prechod:** „Ukážeme si každý typ na jednom vymyslenom príklade.“

---

## Slajdy 12–14 – Tri príklady PMO · Nikolas · 3 × 35 s

Všetky tri slajdy majú rovnakú štruktúru, oplatí sa ju povedať pri prvom slajde:
- **vľavo** je situácia a obrázok problému (tri veci smerujú do jedného miesta),
- **vpravo** sú tri karty – čo by urobil každý typ PMO,
- **zelená karta** je typ, ktorý problém vyrieši primerane,
- **dole** je záver príkladu.

Logika celej trojice: **problém sa zväčšuje a s ním aj potrebná miera kontroly.** Najprv nezhoda vo formáte (stačí rada), potom konflikt o zdroje (treba pravidlá), nakoniec projekt, kde ide o všetko a nikto nerozhoduje (treba priame riadenie). Toto je kľúčová vec, ktorú si treba pamätať – ak zabudneš detaily, odvodíš ich z nej.

### Slajd 12 – Príklad 1: tri reporty a každý je iný → podporné PMO

**Hlavná myšlienka:** Keď stačí dobrá rada, netreba pravidlá ani príkazy.

**Čo povedať**
- Situácia: malá firma, tri projekty, skúsení manažéri. Každý píše report po svojom a „zelený“ znamená u každého niečo iné (u jedného „ideme podľa plánu“, u druhého „zatiaľ to nehorí“). Vedenie dostane tri reporty a nevie ich porovnať.
- **Podporné PMO (zelená karta):** dá jednu šablónu reportu a vysvetlí, čo znamená zelená, oranžová a červená. Skúsení manažéri ju radi prevezmú.
- Riadiace: fungovalo by, ale povinné kontroly skúsených manažérov sú zbytočná byrokracia.
- Direktívne: prebrať riadenie projektov kvôli formátu reportu je strieľanie kanónom na vrabce.

**Vysvetlivky**
- Prečo podporné stačí: problém je iba v **nejednotnom jazyku** (funkcia „spoločný jazyk“ zo slajdu 10). Nikto sa nebráni, manažéri sú skúsení a šablóna im ušetrí prácu. Netreba ich nútiť.
- Toto je zároveň situácia, kde podporné PMO *má* autoritu – lebo ponúka niečo, čo ľudia chcú. Slabina „bez autority ho nikto nepočúva“ sa tu neprejaví.
- **RAG stav** (Red–Amber–Green, červená–oranžová–zelená) je bežný spôsob hlásenia stavu projektu. Funguje, iba ak majú farby dohodnutý význam, napr.:
  - zelená = ideme podľa plánu, nič netreba,
  - oranžová = je riziko, riešime ho sami, vedenie o ňom vie,
  - červená = bez zásahu vedenia nestihneme termín/rozpočet.
- Väzba na slajd 9: rôzne významy „zelenej“ sú živnou pôdou pre melónové reporty.

**Ak sa niekto spýta**
- *„Čo ak to jeden manažér odmietne?“* – Potom už problém nie je vo formáte, ale v ochote spolupracovať, a firma môže zvážiť riadiace PMO. Typ sa mení podľa problému.

**Prechod:** „Druhý príklad je o ľuďoch, ktorých si projekty delia.“

### Slajd 13 – Príklad 2: jeden tester a tri projekty → riadiace PMO

**Hlavná myšlienka:** Keď si projekty delia ľudí, treba spoločné pravidlá.

**Čo povedať**
- Situácia: firma má tri projekty a jedného bezpečnostného testera. Každý manažér ho plánuje, akoby bol iba jeho – a všetky tri termíny padnú na ten istý týždeň.
- Podporné: poradí plánovať testy skôr. Konflikt však nevyrieši – nikto nemusí poslúchnuť.
- **Riadiace (zelená karta):** zavedie spoločný kalendár zdieľaných ľudí. O prioritách rozhodne vedenie podľa podkladov od PMO.
- Direktívne: vyriešilo by to tiež, ale kvôli trom projektom je to zbytočne drahé.

**Vysvetlivky**
- Prečo rada nestačí: každý manažér sa správa racionálne zo svojho pohľadu – chráni svoj projekt. Konflikt je **medzi projektmi**, nie v jednom z nich, a žiaden manažér ho nemôže vyriešiť sám. Potrebujeme pravidlo, ktoré platí pre všetkých.
- **Bezpečnostný tester** (penetration tester) = špecialista, ktorý hľadá v systéme bezpečnostné diery. Je ich málo a sú drahí – typický zdieľaný človek.
- Dôležitý detail: **riadiace PMO nerozhoduje o prioritách samo.** Pripraví podklady (čo ktorý projekt potrebuje, čo sa stane pri posune) a rozhodne vedenie. PMO zabezpečí pravidlo (spoločný kalendár, všetci doň musia zapisovať) a viditeľnosť konfliktu včas.
- Väzba na slajd 10: funkcia „zdieľaní ľudia“ a „jeden prehľad“.

**Ak sa niekto spýta**
- *„Nestačilo by najať druhého testera?“* – Možno áno, ale to je tiež rozhodnutie vedenia a vedenie ho vie urobiť iba vtedy, keď konflikt vidí. Bez spoločného kalendára sa o ňom dozvie až v týždni, keď všetko padne naraz.

**Prechod:** „A tretí príklad je projekt, pri ktorom ide o veľa.“

### Slajd 14 – Príklad 3: strategický projekt so zákonným termínom → direktívne PMO

**Hlavná myšlienka:** Pri strategickom projekte sa prísna kontrola oplatí.

**Čo povedať**
- Situácia: banka musí do zákonného termínu prejsť na nový platobný systém. Robia na ňom traja dodávatelia, každý komunikuje s bankou zvlášť a na rozhodnutia sa čaká týždne. Ak termín nestihnú, hrozí pokuta.
- Podporné: šablóny a rady nepomôžu – problém nie je vo formáte, ale v tom, že nikto nerozhoduje.
- Riadiace: jednotné reporty ukážu, kde to viazne. Rozhodovanie však zostane rozdrobené a pomalé.
- **Direktívne (zelená karta):** prevezme riadenie celého programu – jeden manažér, spoločné denné stretnutie a rozhodnutia v ten istý deň.
- Uzavri celú trojicu: **typ PMO vyberáme podľa problému.**

**Vysvetlivky**
- Prečo práve direktívne: problém nie je v informáciách (tie by riadiace PMO zjednotilo), ale v **rozhodovaní**. Traja dodávatelia, každý s vlastným kontaktom v banke, nikto nemá právomoc rozhodnúť za celok. Termín sa nedá posunúť (je zo zákona), takže čakanie týždne na rozhodnutie je neprijateľné.
- Čo konkrétne direktívne PMO zmení z pohľadu komunikácie:
  - **jeden manažér** = jeden bod, kde sa rozhoduje (namiesto troch paralelných kanálov),
  - **spoločné denné stretnutie** = interaktívny kanál (slajd 5) pre všetkých dodávateľov naraz – problémy jedného hneď počujú ostatní,
  - **rozhodnutia v ten istý deň** = žiadne čakanie na odpovede e-mailom.
- Prečo sa to oplatí, hoci je to drahé: cena direktívneho PMO (ľudia, čas) je malá oproti cene zlyhania (pokuta, reputácia, regulátor). Pri bežných projektoch by to bolo zbytočné (pozri príklady 1 a 2).
- Riziko „úzke hrdlo“ zo slajdu 11 tu platí: ak jeden manažér nestíha, všetko stojí. Preto potrebuje skutočnú právomoc a čas.
- **Program** – tu sa oplatí použiť toto slovo: viac súvisiacich projektov (tri dodávky) s jedným cieľom.
- „Zákonný termín“ je vymyslený, ale realistický – banky bežne musia zavádzať zmeny vynútené reguláciou (napr. nové pravidlá pre platby) k pevnému dátumu.

**Ak sa niekto spýta**
- *„Nemohla by to riadiť banka sama, bez PMO?“* – V podstate áno – direktívne PMO *je* spôsob, ako to banka riadi sama: vytvorí jedno miesto, ktoré má právomoc nad všetkými dodávateľmi. Názov je menej dôležitý než to, že jeden subjekt rozhoduje.
- *„Čo keď projekt skončí?“* – Direktívne riadenie môže byť dočasné – po skončení programu sa PMO môže vrátiť k menej kontrolnému modelu.

**Prechod (odovzdanie Adamovi):** „Tým sme prešli všetky tri časti. Adam to zhrnie.“

---

## Slajd 15 – Čo si z toho odniesť · Adam · 30 s

**Hlavná myšlienka:** Nástroje ani porady samy osebe komunikáciu nezaručia. Zaručia ju ľudia, ktorí si overujú, že si rozumejú.

**Čo povedať** (tri čísla = tri časti prezentácie)
1. **Cieľom je porozumenie** – správa splnila účel, až keď ju príjemca pochopí a vie podľa nej konať. *(slajdy 3–5)*
2. **Riadi sa vedome** – plán podľa potrieb ľudí, každodenné riadenie a pravidelná kontrola, či to funguje. *(slajdy 6–9)*
3. **PMO drží celok pokope** – zjednocuje jazyk a prehľad naprieč projektmi; jeho typ volíme podľa problému. *(slajdy 10–14)*
- Záverečná veta (spodná časť slajdu) a poďakovanie: „Ďakujeme, tešíme sa na otázky.“

**Vysvetlivky**
- Tri body sú presne tri kroky zo slajdu 2. Ak si to uvedomíš, záver sa nemusíš učiť – je to obsah prezentácie zhrnutý do troch viet.
- Záverečná veta spája všetko: kanály a nástroje (Teams, Jira, reporty) sú iba prostriedky. Rozhodujúca je spätná väzba – teda to, čo bolo na slajde 3 úplne na začiatku. Prezentácia sa tak uzatvára do kruhu.

---

## Slajd 16 – Referencie (záložný slajd)

Ukazuje sa iba vtedy, ak sa niekto spýta na zdroje. Čo ktorý zdroj hovorí, aby si vedel odpovedať:

| Zdroj | Čo z neho máme | Kde v prezentácii |
|---|---|---|
| **PMI – PMBOK Guide, 6. vyd. (2017)** | Tri procesy riadenia komunikácie, metódy interaktívna/push/pull, obsah komunikačného plánu, vzorec počtu kanálov, tri typy PMO | slajdy 4–7, 10–11 |
| **Hobbs a Aubry (2007)** | Výskum stoviek PMO: PMO sa navzájom veľmi líšia a často sa reorganizujú – neexistuje jedno správne PMO | slajdy 10–14 |
| **Daft a Lengel (1986)** | Teória bohatosti médií – nejasné správy potrebujú „bohatší“ kanál | slajd 5 |
| **Edmondson (1999)** | Psychologická bezpečnosť – tímy, kde sa nikto nebojí povedať zlú správu, sa viac učia | slajd 9 |
| **Schwaber a Sutherland – Scrum Guide (2020)** | Product Owner, šprint, daily, demo (sprint review) | slajdy 7–9 |
| **Brooks – The Mythical Man-Month (1975/1995)** | Pridanie ľudí do meškajúceho projektu ho ešte viac oneskorí | slajd 4 |

**PMBOK** = A Guide to the Project Management Body of Knowledge, štandard projektového riadenia od PMI (Project Management Institute, americká profesijná organizácia). Existuje aj 7. vydanie (2021), ktoré je postavené viac na princípoch než na procesoch. My vychádzame zo 6. vydania, lebo procesy a typy PMO sú v ňom opísané najjasnejšie. Ak sa niekto spýta, prečo nie 7. vydanie, toto je odpoveď.

---

## Slovník pojmov

| Pojem | Vysvetlenie jednou-dvoma vetami |
|---|---|
| **Akceptačné kritériá** | Konkrétne, overiteľné podmienky, kedy je úloha hotová. Najlepšie s príkladom. |
| **API** | Rozhranie, cez ktoré si dáta vymieňajú programy (nie ľudia). |
| **Backlog** | Zoradený zoznam úloh, ktoré sa majú v produkte urobiť. Spravuje ho Product Owner. |
| **Bloker** | Prekážka, ktorá zastaví prácu na úlohe. |
| **Build** | Zostavenie programu zo zdrojového kódu; „stav buildu“ = či sa podaril. |
| **CI pipeline** | Automatický proces, ktorý po každej zmene kódu program zostaví a otestuje. |
| **CSV** | Textový súbor s hodnotami oddelenými čiarkou/bodkočiarkou. |
| **Daily** | Krátke denné stretnutie tímu (Scrum): na čom pracujem, čo ma blokuje. |
| **Dashboard** | Prehľadová obrazovka s aktuálnymi údajmi (pull kanál). |
| **Dekódovanie** | Príjemca si správu vyloží podľa vlastných skúseností. |
| **Demo** | Ukážka hotovej časti softvéru klientovi (v Scrume sprint review). |
| **Eskalačná cesta** | Dohodnutý postup, komu sa problém posunie vyššie a dokedy, ak sa nedá vyriešiť. |
| **Interaktívna komunikácia** | Obojsmerná v reálnom čase: stretnutie, hovor, demo. |
| **Kódovanie** | Premena myšlienky na slová/obrázok; vždy sa pri nej niečo stratí. |
| **Komunikačný plán** | Kto čo potrebuje vedieť, ako často, akým kanálom a kto za to zodpovedá. |
| **Lessons learned** | Zaznamenané poučenia z projektu pre ďalšie projekty. |
| **Melónový report** | Report zelený navonok, červený vo vnútri – zlé správy sa zatajujú. |
| **Migrácia DB** | Presun dát do inej databázy alebo zmena jej štruktúry. |
| **Monitorovanie komunikácie** | Kontrola, či komunikácia naozaj napĺňa potreby ľudí; zistenia idú späť do plánu. |
| **PMBOK** | Štandard projektového riadenia od PMI; používame 6. vydanie. |
| **PMO** | Kancelária projektového manažmentu – zjednocuje riadenie projektov v organizácii. |
| **Podporné / riadiace / direktívne PMO** | Radí / vyžaduje pravidlá a kontroluje / priamo riadi projekty. |
| **Portfólio** | Všetky projekty a programy firmy riadené podľa stratégie. |
| **Product Owner (PO)** | Zodpovedá za to, čo sa vyvíja a v akom poradí; prekladá ciele klienta do úloh. |
| **Program** | Skupina súvisiacich projektov riadených spolu kvôli spoločnému cieľu. |
| **Projektový manažér (PM)** | Zodpovedá za projekt ako celok; okrem iného prekladá technický stav do dopadu pre vedenie. |
| **Prototyp** | Náčrt alebo jednoduchý model softvéru, aby si ho ľudia vedeli predstaviť skôr, než je hotový. |
| **Psychologická bezpečnosť** | Presvedčenie v tíme, že sa dá povedať chyba alebo zlá správa bez trestu (Edmondson). |
| **Pull** | Príjemca si informáciu nájde sám (wiki, backlog, dashboard). |
| **Push** | Odosielateľ informáciu pošle konkrétnym ľuďom (e-mail, report). Doručené ≠ prečítané. |
| **RAG stav** | Hlásenie stavu farbami červená–oranžová–zelená; funguje iba s dohodnutým významom farieb. |
| **Release notes** | Poznámky k vydaniu: čo je nové a čo sa opravilo. |
| **Spätná väzba** | Overenie, že príjemca správu pochopil; jediný krok, kde sa chyba ukáže skoro. |
| **Sponzor** | Človek z vedenia, ktorý projekt financuje a robí veľké rozhodnutia. |
| **Šprint** | Krátke obdobie (1–4 týždne), po ktorom tím odovzdá hotovú časť produktu. |
| **Šum** | Všetko, čo sťažuje pochopenie: chýbajúci kontext, nejasné slová, zlý kanál, preťaženie. |
| **Tech lead** | Hlavný technický človek v tíme. |
| **Technický dlh** | Provizórne riešenia v kóde, za ktoré sa neskôr „platí úrokmi“ – pomalšími a rizikovejšími zmenami. |
| **Úzke hrdlo** | Miesto, cez ktoré musí prejsť všetko, a preto všetko spomaľuje. |
| **Wiki** | Zdieľaná dokumentácia, ktorú môže upravovať tím (napr. Confluence). |
| **Zdieľaný človek** | Špecialista, ktorého potrebuje viac projektov naraz. |

---

## Otázky k celej téme (na diskusiu po prezentácii)

**Čo je najdôležitejšie na celej téme?**
Spätná väzba. Bez nej nevieme, či si rozumieme – a všetko ostatné (plán, kanály, PMO) sú spôsoby, ako ju zabezpečiť vo väčšom.

**Aký je rozdiel medzi komunikáciou a manažmentom komunikácie?**
Komunikácia je samotná výmena informácií. Manažment komunikácie je vedomé rozhodovanie o tom, kto čo potrebuje, akým kanálom to dostane a či to funguje – teda plán, riadenie a monitorovanie.

**Prečo sa komunikácia v softvérových projektoch kazí častejšie než inde?**
Veľa ľudí a spojení (n · (n − 1) / 2), produkt nie je vidieť, kým nie je hotový, a ľudia z biznisu, vývoja a vedenia hovoria rôznymi jazykmi.

**Ako by ste v praxi zistili, že komunikácia v projekte nefunguje?**
Rovnaké otázky sa opakujú, rozhodnutia sa robia neskoro, problémy sa objavujú prekvapivo, reporty nikto nečíta, dodaná funkcia nie je to, čo klient chcel, všetky reporty sú zelené a projekt aj tak mešká (melón).

**Je e-mail zlý kanál?**
Nie, je to dobrý push kanál pre informácie, ktoré konkrétni ľudia musia dostať. Zlý je na nejasné a citlivé veci – na spory, vyjednávanie, zložité vysvetľovanie.

**Potrebuje agilný tím komunikačný plán?**
Áno, aj keď ho tak nenazýva. Scrum udalosti (daily, review, retrospektíva) sú zabudovaný komunikačný plán. Pre ľudí mimo tímu (vedenie, prevádzka) treba aj tak dohodnúť, čo a kedy dostanú.

**Prečo nie je najlepšie mať vždy direktívne PMO, keď je najsilnejšie?**
Je drahé, spomaľuje (úzke hrdlo) a berie projektovým manažérom zodpovednosť. Pri bežných projektoch je to zbytočné – príklady 1 a 2.

**Čo keď PMO vôbec nemáme?**
Pri jednom-dvoch projektoch to nevadí. Keď ich je viac a zdieľajú ľudí, problémy z príkladov (nejednotné reporty, konflikty o ľudí) vzniknú tak či tak – len ich nikto nebude riešiť systematicky.

**Odkiaľ máte príklady?**
Sú vymyslené, ale typické – zámerne zjednodušené, aby bolo jasné, čo ilustrujú.

---

## Ťahák na jednu stranu

| # | Slajd | Jedna veta |
|---|---|---|
| 1 | Úvod | Tím 5, téma komunikácia a PMO, vysvetlíme na príkladoch. |
| 2 | O čom budeme hovoriť | Ako zabezpečiť, aby si ľudia rozumeli – tri kroky: čo je komunikácia, ako ju riadiť, PMO. |
| 3 | Rovnaké slová, iný význam | „Jednoduchý export“: odosielateľ → kódovanie → kanál a šum → dekódovanie → spätná väzba. Komunikácia končí porozumením. |
| 4 | Prečo je to ťažké | Veľa spojení (3→3, 5→10, 8→28), softvér nie je vidieť, rôzne jazyky. |
| 5 | Správny kanál | Interaktívna = telefonát, push = list, pull = knižnica. Nejasná správa → živší kanál. |
| 6 | Cyklus troch krokov | Plánovanie (kto čo potrebuje?), riadenie (deje sa to?), monitorovanie (pomáha to?) → späť do plánu. |
| 7 | Komunikačný plán | Tabuľka kto/čo/ako často/kanál/kto zodpovedá. Od ľudí, nie od nástrojov. Eskalačná cesta. |
| 8 | Rôzne jazyky | PO prekladá cieľ do úlohy, PM prekladá technický stav do dopadu. |
| 9 | Tri bariéry | Nejasné zadanie → akceptačné kritériá; technický text → dopad a rozhodnutie; chýbajúca spätná väzba → zopakovať, nebáť sa zlej správy (melón). |
| 10 | PMO | Riadiaca veža: spoločný jazyk, zdieľaní ľudia, jeden prehľad, poučenia. |
| 11 | Tri typy PMO | Podporné radí, riadiace kontroluje, direktívne riadi. |
| 12 | Príklad 1 | Tri rôzne reporty → podporné PMO dá šablónu. Stačí rada. |
| 13 | Príklad 2 | Jeden tester, tri projekty → riadiace PMO, spoločný kalendár. Treba pravidlá. |
| 14 | Príklad 3 | Banka, traja dodávatelia, zákonný termín → direktívne PMO, jeden manažér. Kontrola sa oplatí. |
| 15 | Záver | Porozumenie, vedomé riadenie, PMO podľa problému. Komunikáciu zaručia ľudia, ktorí si overujú, že si rozumejú. |

**Ako sa to učiť:** najprv si zapamätaj tri vety z úvodu týchto poznámok a stĺpec „Jedna veta“ v ťaháku. Potom si každý slajd povedz nahlas vlastnými slovami bez pozerania – kde sa zasekneš, prečítaj si vysvetlivky. Nakoniec si nechaj od niekoho klásť otázky zo sekcií „Ak sa niekto spýta“.
