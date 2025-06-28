---
dg-publish: true
---
**TLDR: Fyzika herného sveta – Priestor a Čas**

- **Základný princíp:** Priestor a čas v hrách nie sú reálne, ale sú to umelo vytvorené systémy, ktoré slúžia hrateľnosti a vytvárajú špecifický zážitok.
    
- **Priestor:**
    
    - Môže byť **diskrétny** (pohyb po políčkach, ako v Šachu) alebo **kontinuálny** (plynulý pohyb, ako vo väčšine 3D hier).
    - Vnímanie priestoru určuje **kamera** (pohľad z prvej/tretej osoby, zhora, izometrický atď.).
- **Čas:**
    
    - Môže byť **diskrétny** (na ťahy, ako v X-COM), kde čas plynie, len keď hráč koná, alebo **kontinuálny** (v reálnom čase, ako v StarCraft), kde plynie neustále.
    - Často plynie inak ako v realite (napr. zrýchlený deň/noc v _Minecraft_) alebo sa ním dá priamo **manipulovať**.
- **Manipulácia s časom:** Je to obľúbená herná mechanika: **spomalenie času** (_Max Payne_), **pretáčanie času** (_Prince of Persia_) alebo **časové slučky** (_Hades_).

---

### **Základy fyziky herného sveta – Priestor a Čas**

Fyzika v hrách nie je replikou skutočnej fyziky. Je to **simulácia** – zjednodušený a účelovo navrhnutý systém, ktorého hlavnou úlohou nie je byť realistický, ale **slúžiť hrateľnosti (gameplayu)**. Priestor a čas sú najzákladnejšie piliere tohto systému, ktoré herní dizajnéri aktívne tvarujú, aby vytvorili špecifický hráčsky zážitok.

### **Časť I: Priestor v Hernom Svete**

Herný priestor je prostredie, v ktorom sa hra odohráva. Jeho vlastnosti priamo definujú, ako sa hráč môže pohybovať a interagovať so svetom.

#### **1. Diskrétne a Kontinuálne Priestory**

- **Diskrétny priestor (Discrete Space):** Priestor je rozdelený na jasne definované, oddelené jednotky (políčka, hexagóny, polia). Pohyb sa nedeje plynule, ale skokovo z jednej jednotky na druhú.
    
    - **Príklady:** Šachovnica, herná plocha v hre _Monopoly_, mapa v ťahových stratégiách ako _Civilization_ alebo _X-COM_. Hráč sa nemôže nachádzať "medzi" políčkami. Tento prístup podporuje strategické a logické myslenie.
- **Kontinuálny priestor (Continuous Space):** Priestor nie je rozdelený na mriežku. Postavy a objekty sa môžu nachádzať na akejkoľvek pozícii definovanej súradnicami (X, Y, Z) a pohybujú sa plynule.
    
    - **Príklady:** Väčšina moderných 3D hier ako _The Witcher 3_, _Call of Duty_ alebo _Elden Ring_. Tento prístup vytvára ilúziu realistickejšieho a plynulejšieho sveta.

#### **2. Rozmery Herného Priestoru**

- **2D Priestor:** Hra sa odohráva na plochej rovine s dvoma osami (X, Y). Pohyb je obmedzený do štyroch alebo ôsmich smerov. Typické pre plošinovky, arkády a staršie RPG.
- **3D Priestor:** Hra sa odohráva v priestore s tromi osami (X, Y, Z), čo umožňuje pohyb všetkými smermi, vrátane hore a dole. Je to štandard pre väčšinu súčasných hier.
- **Zdanlivé 3D (2.5D):** Hry, ktoré používajú 3D grafiku, ale hrateľnosť je obmedzená na 2D rovinu (napr. moderné bojové hry ako _Street Fighter 6_).

#### **3. Abstrakcia Herného Priestoru**

Herný svet nemusí reprezentovať fyzickú realitu. Môže byť úplne abstraktný, kde priestor symbolizuje niečo iné.

- **Príklady:** Šachovnica nereprezentuje skutočné bojisko, ale abstraktný súboj dvoch armád. Priestor v hre _Tetris_ je len nádoba na padajúce bloky. Mriežka v hre _Míny_ reprezentuje logickú hádanku, nie mínové pole.

#### **4. Mierka a Hranice**

- **Mierka (Scale):** Vzťah medzi veľkosťou herného sveta a veľkosťou postáv. Mierka je takmer vždy upravená pre potreby hrateľnosti. Mesto Los Santos v _Grand Theft Auto V_ je obrovské, no je to len zmenšená a skomprimovaná karikatúra skutočného Los Angeles.
- **Hranice (Boundaries):** Každý herný svet je konečný a musí mať hranice. Dizajnéri používajú rôzne techniky na ich vytvorenie:
    - **Fyzické prekážky:** Hory, oceán, nepriechodné steny.
    - **Neviditeľné steny:** Umelé, neviditeľné bariéry, ktoré bránia hráčovi opustiť určenú oblasť.
    - **Portály a načítavacie obrazovky:** Svet je rozdelený na menšie zóny, medzi ktorými hráč prechádza.
    - **Programové obmedzenia:** Hra hráča upozorní ("Vráťte sa do bojovej zóny!") a pošle ho späť.

#### **5. Perspektíva – Kamerové Modely**

Kamera určuje, ako hráč vníma herný priestor. Je to jeden z najdôležitejších nástrojov dizajnu.

- **Pohľad prvej osoby (First-Person):** Hráč vidí svet očami svojej postavy. Maximalizuje to ponorenie do hry (imerziu). (Príklady: _Skyrim_, _Cyberpunk 2077_, _Half-Life_).
- **Pohľad tretej osoby (Third-Person):** Kamera sleduje postavu zozadu alebo zboku. Hráč vidí svoju postavu a jej bezprostredné okolie, čo mu dáva lepší prehľad o situácii. (Príklady: _The Witcher 3_, _Tomb Raider_).
- **Pohľad zhora (Top-Down):** Kamera je umiestnená vysoko nad hernou scénou a pozerá sa priamo nadol. (Príklady: staré diely _GTA_, _Stardew Valley_).
- **Izometrický pohľad:** Kamera je umiestnená hore a pod uhlom, čo vytvára dojem 3D priestoru na 2D ploche. (Príklady: _Diablo_, _Baldur's Gate 3_).
- **Bočný pohľad (Side-Scrolling):** Kamera sleduje postavu zboku. Typické pre 2D plošinovky. (Príklady: _Super Mario Bros._, _Hollow Knight_).

### **Časť II: Čas v Hernom Svete (Temporálna dimenzia)**

Čas v hrách je rovnako flexibilný a umelo vytvorený ako priestor.

#### **1. Diskrétny a Kontinuálny Čas**

- **Diskrétny čas (Turn-Based):** Čas v hre napreduje len vtedy, keď hráč (alebo súper) vykoná akciu. Hra je rozdelená na ťahy. Tento systém dáva hráčovi čas na premýšľanie a strategické rozhodovanie.
    - **Príklady:** Šach, _X-COM_, _Slay the Spire_, väčšina JRPG (napr. staršie _Final Fantasy_).
- **Kontinuálny čas (Real-Time):** Čas plynie neustále a nezávisle od hráčových akcií. Vyžaduje si rýchle reakcie a rozhodovanie pod tlakom.
    - **Príklady:** Akčné hry (_Doom_), stratégie v reálnom čase (_StarCraft_), športové hry (_FIFA_).
- **Hybridné modely:** Niektoré hry kombinujú oba prístupy. _Fallout_ umožňuje kedykoľvek hru zapauzovať a použiť systém V.A.T.S., ktorý je v podstate ťahový.

#### **2. Chronológia Času v Hrách**

- **Lineárny čas:** Príbeh a udalosti postupujú v pevne danom poradí od začiatku do konca.
- **Nelineárny čas:** Hráč môže plniť úlohy a prežívať príbeh v rôznom poradí.
- **Cyklický čas (Time Loop):** Hra sa po určitom čase alebo po splnení/nesplnení úlohy resetuje a začína odznova. Hráč si však zachováva vedomosti z predchádzajúcich cyklov.
    - **Príklady:** _The Legend of Zelda: Majora's Mask_, _Hades_, _Outer Wilds_.

#### **3. Časomiery (Timers)**

Časomiery sú explicitné časové limity na splnenie úlohy. Ich hlavnou funkciou je vytvárať pocit naliehavosti a tlaku.

- **Príklady:** Limit 90 sekúnd na prejdenie levelu v klasických _Super Mario_ hrách, odpočet bomby v _Counter-Strike_, čas na jedno kolo v pretekárskych hrách.

#### **4. Variabilný a Anomálny Čas**

- **Variabilný čas:** Rýchlosť plynutia času nie je konštantná alebo sa nerovná reálnemu času. Najčastejším príkladom je zrýchlený **cyklus dňa a noci**, kde 24 hodín v hre uplynie za 24 minút reálneho času (_Minecraft_, _Skyrim_).
- **Anomálny čas:** V určitých zónach herného sveta sa čas správa neštandardne – môže byť spomalený, zastavený alebo sa môže vracať.

#### **5. Manipulácia s Časom ako Herná Mechanika**

Niektoré hry robia z manipulácie s časom svoju jadrovú mechaniku.

- **Spomalenie času (Slow-Motion):** Umožňuje hráčovi lepšie reagovať v hektických situáciách. (Príklad: "Bullet Time" v hre _Max Payne_).
- **Pretáčanie času (Time Rewind):** Umožňuje hráčovi vrátiť sa o pár sekúnd späť a napraviť chybu. (Príklad: Dýka času v _Prince of Persia: The Sands of Time_).
- **Zastavenie času:** Hráč môže na krátky okamih "zamraziť" svet okolo seba. (Príklad: Schopnosť "Bend Time" v hre _Dishonored_).
- **Skákanie v čase:** Hráč sa môže prepínať medzi dvoma časovými rovinami (minulosťou a prítomnosťou) na tom istom mieste, aby riešil hádanky. (Príklad: Misia "Effect and Cause" v _Titanfall 2_).

**Záver:** Priestor a čas nie sú v hrách len pasívnym pozadím. Sú to aktívne a flexibilné dizajnové nástroje, ktoré definujú pravidlá, vytvárajú výzvy a formujú celkový zážitok hráča. Ich pochopenie je kľúčom k pochopeniu toho, ako hry fungujú a prečo sú pre nás tak pútavé.