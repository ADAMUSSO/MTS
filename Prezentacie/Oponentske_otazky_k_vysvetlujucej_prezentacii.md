# Možné otázky od oponentov (tím 3) – vysvetľujúca prezentácia

Tím 5 · Adam Svitek, Nikolas Knapík · streda 13:00 – 14:00

Diskusia s oponentmi trvá najviac 7 minút a za reakcie na otázky sú 2 body. Otázky sú stredne ťažké: vyzerajú ako poriadna oponentúra, ale odpoveď vychádza priamo z toho, čo na prezentácii hovoríme. Na 7 minút sme vybrali 7 otázok, teda asi minútu na otázku aj s odpoveďou. Ostatné sú záložné. Pri každej je krátka kostra odpovede – nie na naspamäť, len aby sme vedeli, kam mieriť. Za otázkou je číslo slajdu, na ktorý sa dá vrátiť.

## Výber 7 otázok na 7 minút

**1. Na príklade s exportom dát (sl. 3) ste ukázali, že chyba vznikla v tickete. Kto je za ňu teda zodpovedný – klient, ktorý napísal tri slová, alebo vývojár, ktorý sa nespýtal?** *(Adam)*
Nejde o hľadanie vinníka – chyba vznikla v procese. Odosielateľ mal dať príklad a kontext, príjemca si mal overiť, ako správu pochopil. Preto hovoríme, že komunikácia nekončí odoslaním: zodpovednosť za porozumenie je na oboch stranách a v projekte ju má zabezpečiť proces (akceptačné kritériá, ukážka návrhu, demo).

**2. Podľa vás „čím je správa nejasnejšia alebo citlivejšia, tým živší kanál“ (sl. 5). Nie je ale písomná forma lepšia, keďže po nej ostane záznam?** *(Adam)*
Nevylučuje sa to. Rozhodnutie sa najlepšie urobí živo (stretnutie, hovor), kde sa dá hneď pýtať – a potom sa písomne zapíše, napr. do wiki alebo ticketu (pull). Živý kanál slúži na porozumenie, písomný na pamäť projektu. Chyba je len vtedy, keď spor riešime iba e-mailmi.

**3. Ako by ste v kroku „monitorovanie“ zmerali, či komunikácia funguje? Počet porád alebo e-mailov to asi nebude.**
Nie, sledovali by sme dopady: koľko práce sa prerábalo pre zle pochopené zadanie, ako rýchlo sa riešia blokery, či stakeholderi vedia aktuálne priority, či sú rozhodnutia zapísané a dajú sa nájsť. Jednoduchý spôsob je aj krátka otázka na retrospektíve alebo stakeholderom.

**4. Na slajde 8 prekladá Product Owner a projektový manažér. Nevzniká tak práve tá „tichá pošta“, pred ktorou varujete – správa ide cez ďalšieho človeka?** *(Nikolas)*
Dobrý postreh – každý sprostredkovateľ je riziko. Preto prekladateľ nemá byť jediný kanál: vývojári sa môžu zúčastniť na demo s klientom a vidieť ho priamo, a preklad sa overuje spätnou väzbou (klient potvrdí akceptačné kritériá). Bez prekladateľa by však bolo horšie – vývojár a vedenie by si jednoducho nerozumeli.

**5. Spomínate melónový report. Prečo by projektový manažér vôbec hlásil zelenú, keď je projekt v problémoch – a ako tomu zabrániť?** *(Nikolas)*
Lebo sa bojí, že zlá správa sa obráti proti nemu, alebo dúfa, že to ešte dobehne. Pomáha prostredie, kde zlá správa skoro je lepšia ako neskoro (nikoho za ňu netrestať), a jasná definícia farieb – presne to, čo v príklade 1 robí PMO. Keď „červená“ znamená konkrétny stav, ťažšie sa obchádza.

**6. Hovoríte, že riadiace PMO ľahko prerastie do byrokracie. Ako to rozpoznať a ako tomu predísť?** *(Nikolas)*
Varovné znaky: projekty vypĺňajú reporty, ktoré nikto nečíta, a manažéri trávia viac času pre PMO než pre projekt. Predchádza sa tomu tak, že PMO požaduje len to, čo naozaj používa na rozhodovanie, a pravidelne sa pýta projektov, čo im pomáha – teda rovnaký cyklus monitorovania ako pri komunikácii (sl. 6).

**7. Na príklade 2 (jeden tester, tri projekty) rozhoduje o prioritách vedenie. Prečo to nerozhodne PMO samo, keď má najlepší prehľad?** *(Nikolas)*
Pretože riadiace PMO nemá autoritu meniť priority firmy – to je rozhodnutie vedenia. PMO pripraví podklady (konflikt v kalendári, dopady na termíny) a vedenie rozhodne. Keby PMO rozhodovalo samo, išlo by už o direktívne PMO.

## Záložné otázky

Ak oponenti položia niečo podobné alebo zostane čas.

**Z. Vzorec n·(n−1)/2 (sl. 4) znamená, že väčší tím komunikuje horšie. Majú teda veľké projekty rozdeliť ľudí na malé tímy?**
Áno, presne to sa v praxi robí – malé tímy (napr. Scrum tímy do ~10 ľudí) a medzi nimi niekoľko definovaných rozhraní namiesto „každý s každým“. Vzorec je ilustrácia, nie meranie: neznamená, že každé spojenie sa reálne používa, ale ukazuje, prečo komunikáciu treba štruktúrovať, keď tím rastie. Na úrovni viacerých tímov/projektov to je presne úloha PMO.

**Z. Hovoríte, že softvér „nie je vidieť“. Ako to konkrétne v projekte riešite?**
Tak, že ho zviditeľníme čo najskôr: prototyp, mockup, demo na konci šprintu, dashboard so stavom buildu. Klient tak reaguje na niečo, čo vidí, nie na predstavu. To je aj dôvod, prečo je demo v našom komunikačnom pláne pre klienta každý šprint.

**Z. Ako zistíte, že push správu (e-mail, report) niekto naozaj prečítal?**
Priamo to garantovať nevieme, a preto na to upozorňujeme. Pomáha vyžiadať si reakciu („potrebujeme vaše áno do piatku“), dôležité veci zopakovať aj na stretnutí a pri monitorovaní sa spýtať stakeholderov, či report používajú. Ak nie, zmeníme formát alebo kanál – to je príklad zo slajdu 6.

**Z. Nie je komunikačný plán v agilnom tíme zbytočná byrokracia, keď máme daily, review a retro?**
Vnútri tímu je veľa komunikácie zabudovanej do Scrum udalostí, takže plán môže byť krátky. Plán však rieši najmä ľudí mimo tímu – sponzora, prevádzku, iné tímy – a eskalačnú cestu. Preto ukazujeme, že stačí jednoduchá tabuľka (sl. 7), nie hrubý dokument.

**Z. Čo konkrétne má obsahovať eskalačná cesta, o ktorej hovoríte pri komunikačnom pláne?**
Kto je ďalší v poradí, keď sa problém nedá vyriešiť na úrovni tímu (napr. tím → PM → sponzor), do akého času sa má problém posunúť ďalej a akým kanálom. Cieľ je, aby sa nikto nemusel v kritickej chvíli pýtať „komu to mám povedať?“.

**Z. Ak má firma len jeden-dva projekty, potrebuje vôbec PMO?**
Formálne oddelenie nie. PMO má zmysel, keď je projektov viac a treba ich porovnávať alebo si delia ľudí. Pri malej firme môžu úlohu „podporného PMO“ robiť aj šablóny a jeden skúsený človek popri inej práci. Typ (a samotnú existenciu) PMO vyberáme podľa problému, nie preto, že „sa to má“.

**Z. Musí firma mať jeden typ PMO pre všetky projekty? Nedá sa to kombinovať?**
Dá. Typy PMO sú skôr škála ako tri škatuľky. Firma môže mať bežne podporné/riadiace PMO a pre jeden strategický projekt (ako v príklade 3) zriadiť direktívne riadenie programu, kým projekt neskončí.

**Z. Vaše príklady sú vymyslené. Ako viete, že by to v reálnej firme naozaj takto fungovalo?**
Príklady sú zjednodušené zámerne, aby bolo vidieť rozdiel medzi typmi PMO. Samotné typy (podporné, riadiace, direktívne) a ich výhody/nevýhody vychádzajú z literatúry (PMBOK, zdroje na záložnom slajde). V reálnej firme sú situácie zmiešané, ale logika „vyber typ podľa problému“ platí.

## Rýchle tipy k diskusii

- Najprv krátko odpovedať (jedna veta), potom vysvetliť a ak sa dá, ukázať na slajd.
- Keď otázka mieri na slabinu, je v poriadku to priznať („dobrý postreh“) a povedať, ako to riešime – napr. otázky 8 a 15.
- Rozdelenie: otázky na komunikáciu, kanály a príklad s exportom berie Adam; plán, bariéry a PMO Nikolas. Druhý môže doplniť.
