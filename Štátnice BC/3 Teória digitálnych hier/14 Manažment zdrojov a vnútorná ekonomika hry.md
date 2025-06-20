**TLDR: Manažment zdrojov a ekonomika hier**

- **Jadro hry:** Každá hra je o riadení zdrojov. Jej vnútorná ekonomika je systém, ktorý riadi, ako zdroje v hre vznikajú, menia sa a zanikajú.
    
- **Kolobeh zdrojov:**
    
    - **Zásobníky (Sources):** "Kohútiky", kde zdroje vznikajú (napr. zabitím monštra, ťažbou).
    - **Odvádzače (Sinks):** "Odtoky", kde zdroje miznú (napr. nákupom, opravou). Sú kľúčové proti inflácii.
    - **Konvertory (Converters):** Menia jeden zdroj na iný (napr. kováč mení rudu na meč).
- **Čo je zdroj:** Nie je to len zlato alebo drevo. Najdôležitejšími zdrojmi sú často nehmotné veci ako **čas, informácie, pozícia a hráčova zručnosť**.

---

### **Manažment zdrojov a vnútorná ekonomika hry**

Každá hra, od jednoduchej plošinovky až po komplexnú stratégiu, je v jadre **systémom riadenia zdrojov**. Hráčovou úlohou je spravovať tieto zdroje tak, aby dosiahol cieľ hry. Vnútorná ekonomika je súbor pravidiel a mechanizmov, ktoré riadia vznik, zánik, výmenu a transformáciu týchto zdrojov.

#### **Časť I: Stavebné bloky vnútornej ekonomiky**

**1. Jednotky, ich schopnosti, štatistiky a modifikátory**

- **Jednotky (Units):** Akákoľvek aktívna entita v hre – hráčova postava, nepriateľ, spojenec (NPC), budova, vozidlo.
- **Štatistiky (Stats):** Číselné hodnoty, ktoré definujú vlastnosti jednotky. Sú to základné zdroje, ktoré jednotka "vlastní".
    - _Príklady:_ Zdravie (HP), Mana (MP), Sila, Obratnosť, Inteligencia, Rýchlosť, Poškodenie (Damage), Brnenie (Armor).
- **Schopnosti (Abilities):** Akcie, ktoré jednotka môže vykonať, často za cenu nejakého zdroja (napr. použitie kúzla spotrebuje manu).
- **Modifikátory (Modifiers):** Dočasné alebo trvalé zmeny štatistík alebo schopností.
    - _Príklady:_ "Buff" (napr. +20% k sile na 30 sekúnd), "Debuff" (napr. -50% k rýchlosti), bonusy z vybavenia (+10 k brneniu z helmy).

**2. Herné meny, položky a typy zdrojov**

- **Herné meny (Currencies):** Univerzálny prostriedok výmeny.
    - _Príklady:_ Zlato, Kredity, Gemy, Duše (v sérii _Dark Souls_).
- **Položky (Items):** Konkrétne objekty s definovanou funkciou.
    - _Príklady:_ Elixíry (obnovujú zdravie), kľúče (otvárajú dvere), materiály na výrobu (železná ruda).

**Hmotné a nehmotné zdroje:**

- **Hmotné zdroje (Tangible Resources):** Sú ľahko merateľné a vlastniteľné. Sú to všetky meny, položky, jednotky, suroviny (drevo, kameň).
- **Nehmotné zdroje (Intangible Resources):** Sú abstraktné, no často oveľa dôležitejšie pre úspech.
    - _Príklady:_ **Čas** (najdôležitejší zdroj v hrách v reálnom čase), **informácie** (vedieť, kde sa nachádza nepriateľ), **pozícia** (mať výhodnejšie postavenie na mape), **tempo** (udržiavanie tlaku na súpera), **hráčova zručnosť**, **reputácia** u frakcií.

#### **Časť II: Tok zdrojov v ekonomike**

Každá herná ekonomika musí riadiť, ako zdroje do systému vstupujú, ako sa v ňom menia a ako z neho odchádzajú. Bez tohto cyklu by sa systém zrútil (napríklad v dôsledku nekontrolovateľnej inflácie).

- **Zásobníky (Sources / Faucets):** Mechanizmy, ktoré **vytvárajú zdroje** a vkladajú ich do herného sveta. Sú to "kohútiky", z ktorých tečú zdroje.
    
    - _Príklady:_ Zabitie monštra (generuje skúsenosti a zlato), ťažba rudy (generuje suroviny), pasívny príjem z budov, denné odmeny za prihlásenie.
- **Odvádzače (Drains / Sinks):** Mechanizmy, ktoré **trvalo odstraňujú zdroje** z hry. Sú to "odtoky", ktoré bránia hromadeniu zdrojov a inflácii.
    
    - _Príklady:_ Nákup spotrebných predmetov (elixírov), oprava vybavenia, poplatky za cestovanie, poplatky za aukciu, smrť postavy (strata skúseností alebo peňazí).
- **Konvertory (Converters):** Mechanizmy, ktoré **menia jeden typ zdroja na iný**. Sú motorom ekonomiky.
    
    - _Príklady:_ **Kováč** (mení železnú rudu + zlato na meč), **obchodník** (mení meč na zlato), **systém skúseností** (mení XP na nový level a nové schopnosti), **výroba/crafting** vo všeobecnosti.

#### **Časť III: Ekonomické mechanizmy**

- **Obchodnícke mechaniky (Trading):** Umožňujú výmenu zdrojov.
    
    - **Hráč ↔ NPC:** Predaj nepotrebných predmetov obchodníkovi v meste.
    - **Hráč ↔ Hráč:** Aukčné domy v online hrách (_World of Warcraft_), priama výmena medzi hráčmi.
- **Produkčné mechanizmy (Production):** Sú to typické konvertory, kde hráč kombinuje vstupné suroviny, aby vytvoril hodnotnejší produkt.
    
    - **Vstup (Input):** Suroviny, recept/plán, energia, čas.
    - **Proces (Process):** Samotná výroba.
    - **Výstup (Output):** Finálny produkt (zbraň, brnenie, elixír).

#### **Časť IV: Dynamika herného systému**

Vnútorná ekonomika nie je statická. Jej správanie je definované vzťahmi medzi jej prvkami.

- **Slučka spätnej väzby (Feedback Loop):** Základný princíp dynamických systémov.
    - Výrobný mechanizmus, ktorý vyžaduje niektoré zdroje, ktoré samotný mechanizmus produkuje, predstavuje spätnú väzbu vo výrobnom procese. V kontexte vnútornej ekonomiky sa spätná väzba vzťahuje na zdroje, ktoré sa vracajú späť do výrobného mechanizmu.
    - Pokiaľ má mechanizmus na začiatku dostatok zdrojov a produkuje ich viac, než potrebuje, nie je na použití spätnej väzby nič zlé. Ak však z nejakého dôvodu dôjde v systéme zdroj, mechanizmus už nebude schopný produkovať viac. Tento stav, nazývaný slepá ulička, zablokuje túto časť ekonomiky, pokiaľ nezabezpečíme nejaký iný prísun zdroja - spôsob, ako sa dostať zo slepej uličky.
- **Vzájomná závislosť (Interdependence):** Rôzne zdroje a mechanizmy sú navzájom prepojené a závislé. _Na výrobu lepšieho meča potrebujete vzácnu rudu. Na ťažbu vzácnej rudy potrebujete lepší krompáč. Na kúpu lepšieho krompáča potrebujete peniaze, ktoré získate predajom mečov._ Tieto závislosti vytvárajú komplexné strategické rozhodovanie.
    
- **Slepá ulička (Deadlock):** Stav v hre, z ktorého sa hráč nemôže dostať, pretože mu chýba kľúčový zdroj a nemá žiadny spôsob, ako ho získať. Je to zvyčajne výsledok zlého herného dizajnu.
    
- **Statické a Dynamické Ekvilibrium (Equilibrium):**
    
    - **Statické ekvilibrium:** Stav rovnováhy, ktorý sa nemení. (Napr. šachovnica pred prvým ťahom). V komplexných hrách je vzácne.
    - **Dynamické ekvilibrium:** Stav, v ktorom systém neustále osciluje okolo rovnovážneho bodu. V online hrách sa vývojári snažia udržiavať dynamické ekvilibrium v ekonomike – tok zdrojov zo **zásobníkov (sources)** by sa mal zhruba rovnať toku zdrojov do **odvádzačov (sinks)**, aby ceny zostali stabilné.

**Záver:** Vnútorná ekonomika hry je komplexný systém, ktorý dáva hodnotu predmetom, zmysel akciám a hĺbku strategickému rozhodovaniu. Dobrý herný dizajn sa prejavuje v tom, ako elegantne a vyvážene sú tieto systémy navrhnuté, aby vytvorili pútavý a dlhodobo udržateľný zážitok pre hráča.