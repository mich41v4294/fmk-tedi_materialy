**TLDR: 3D grafika v hrách**

- **Ako vzniká 3D obraz:** Je to proces v niekoľkých krokoch:
    
    1. **Polygóny:** Základné trojuholníky, z ktorých je zložený tvar 3D modelu (postavy, budovy).
    2. **Textúry:** 2D obrázok ("tapeta"), ktorý sa "nalepí" na model a dá mu farbu a detail povrchu.
    3. **Shadery:** Programy, ktoré vypočítavajú, ako model reaguje na svetlo (tiene, odlesky, lesk).
    4. **Rendering:** Finálny proces, kde grafická karta všetko spojí a vykreslí na obrazovku (ideálne 60-krát za sekundu).
- **Vývoj a kľúčové hry:** 3D grafika sa vyvinula od jednoduchých čiarových hier (_Star Wars_ arkáda) k revolúcii v 90. rokoch. Hry ako **Doom**, **Super Mario 64** a **Quake** definovali, ako sa v 3D priestore pohybujeme, skáčeme a bojujeme.
    
- **Virtuálna (VR) a rozšírená (AR) realita:**
    
    - Obe technológie fungujú na princípe **stereoskopie**: každému oku ukážu mierne odlišný obraz, čím oklamú mozog a vytvoria ilúziu skutočnej hĺbky.
    - **VR headset** vás úplne ponorí do virtuálneho sveta a odreže od reality.
    - **AR (rozšírená realita)** naopak, pridáva digitálne prvky do reálneho sveta, ktorý vidíte cez kameru (ako v _Pokémon GO_).

---

### **3D grafika: Tvorba ilúzie hĺbky a priestoru**

3D (trojrozmerná) grafika je súbor techník používaných na zobrazenie trojrozmerných objektov na dvojrozmernej obrazovke (monitor, displej). Jej cieľom je vytvoriť ilúziu hĺbky, priestoru a objemu. Na rozdiel od 2D grafiky, kde sa pracuje s plochými obrázkami (sprajtami), 3D grafika pracuje s virtuálnymi modelmi v trojrozmernom priestore.

#### **1. Základné pojmy a princípy**

Proces vytvorenia 3D obrazu v reálnom čase (ako v hrách) má niekoľko kľúčových stavebných kameňov:

- **Polygón (Polygon):** Je to základný stavebný prvok každého 3D modelu. Ide o jednoduchý 2D tvar (najčastejšie trojuholník alebo štvorec) definovaný vrcholmi (vertexami) v 3D priestore. Spájaním tisícok až miliónov polygónov do siete (mesh) sa vytvára tvar komplexného 3D objektu – postavy, budovy, vozidla. Čím viac polygónov model má, tým je detailnejší a hladší, ale aj náročnejší na výpočtový výkon.
    
- **Textúra (Texture):** Samotný polygonálny model je len bezfarebná "drôtená" kostra. Aby získal povrch a vizuálny detail, "obalí" sa 2D obrázkom, ktorý sa nazýva textúra. Je to ako tapeta, ktorá sa nalepí na 3D model. Textúry môžu simulovať akýkoľvek povrch – drevo, kov, kožu, kameň. Moderné hry používajú viacero vrstiev textúr na simuláciu drsnosti, odleskov či hĺbky materiálu.
    
- **Shadery (Tieňovače):** Sú to malé programy, ktoré bežia na grafickej karte (GPU) a určujú, ako má povrch objektu reagovať na svetlo. Zatiaľ čo textúra definuje základnú farbu a vzor, shadery vypočítavajú finálny vzhľad pixelov na základe umiestnenia svetiel, pozície kamery a vlastností materiálu (napr. či je lesklý, matný, priehľadný alebo kovový). Sú zodpovedné za všetky realistické efekty ako odrazy, tiene, lom svetla a celkovú atmosféru scény.
    
- **Rendering (Vykresľovanie):** Je to finálny proces, pri ktorom grafická karta zoberie všetky tieto informácie – 3D modely (polygóny), ich povrchy (textúry) a materiálové vlastnosti (shadery) – a prevedie ich na finálny 2D obraz, ktorý vidíte na monitore. V hrách musí tento proces prebehnúť extrémne rýchlo, ideálne 60-krát za sekundu (60 FPS - frames per second) alebo aj častejšie.
    

#### **2. Druhy perspektívy, predchodcovia a vývojové fázy 3D grafiky**

**Druhy perspektívy:**

- **Pohľad prvej osoby (First-Person Perspective - FPP):** Kamera je umiestnená v "očiach" postavy. Ponúka najvyššiu mieru ponorenia (imerzie).
- **Pohľad tretej osoby (Third-Person Perspective - TPP):** Kamera sleduje postavu zozadu alebo zboku, hráč vidí svoju postavu na obrazovke. Umožňuje lepší prehľad o okolí.
- **Pevná perspektíva (Fixed 3D):** Objekty sú renderované v reálnom čase na statickom pozadí, Kamera sa nepohybuje, ale je staticky umiestnená na preddefinovaných miestach

**Predchodcovia a vývojové fázy:**

1. **Vektorová grafika (70. a 80. roky):** Prvé pokusy o 3D priestor, ktoré nepoužívali polygóny, ale len čiary na špeciálnych vektorových monitoroch. (Príklad: arkádová hra _Star Wars_, 1983).
2. **Pseudo-3D (koniec 80. rokov):** Hry, ktoré vytvárali ilúziu 3D priestoru pomocou 2D grafiky a trikov. Typickým príkladom je škálovanie sprajtov – vzdialenejšie objekty sa zobrazovali ako menšie 2D obrázky. (Príklad: _Out Run_, 1986).
3. **Raná polygónová grafika (začiatok 90. rokov):** Prvé hry s reálnou 3D grafikou. Modely boli zložené z veľmi malého počtu nevyplnených alebo jednofarebných polygónov. (Príklady: _Virtua Racing_, 1992; _Star Fox_, 1993).
4. **Textúrovaná 3D grafika (polovica 90. rokov):** Obrovská revolúcia. Na polygóny sa začali nanášať textúry, čo dramaticky zvýšilo vizuálnu vernosť. Toto je éra, kedy sa 3D stalo mainstreamom. (Príklady: _Quake_, 1996; _Super Mario 64_, 1996).
5. **Éra hardvérovej akcelerácie (koniec 90. rokov - súčasnosť):** Nástup dedikovaných 3D grafických kariet (GPU) umožnil spracovať obrovské množstvo polygónov a zložité efekty v reálnom čase. To viedlo k ére programovateľných shaderov, fotorealistickému osvetleniu a neustálemu zvyšovaniu vizuálnej kvality, ktoré vidíme dodnes.

#### **3. Príklady hier, ktoré priniesli zásadné inovácie v 3D zobrazení**

- **Doom (1993):** Hoci technicky nešlo o plne 3D svet (levely boli 2D mapy s rôznou výškou podláh a stropov, postavy boli 2D sprajty), vytvoril ilúziu rýchleho pohybu v 3D priestore a definoval žáner strieľačiek z prvej osoby (FPS).
- **Super Mario 64 (1996):** Definovala, ako sa ovláda postava v 3D priestore. Zaviedla koncept analógovej páčky pre plynulý pohyb a inteligentnej kamery, ktorá postavu sleduje. Položila základy pre 3D plošinovky.
- **Quake (1996):** Jedna z prvých hier, ktorá bežala v plne 3D renderovanom svete (vrátane postáv a nepriateľov) a masívne spopularizovala hardvérovú 3D akceleráciu.
- **The Legend of Zelda: Ocarina of Time (1998):** Zaviedla revolučný systém zameriavania na nepriateľa ("Z-targeting"), ktorý vyriešil mnohé problémy s bojom a kamerou v 3D priestore.
- **Half-Life (1998):** Ukázal, ako sa dá v 3D prostredí rozprávať plynulý a pútavý príbeh bez prerušenia a bez použitia oddelených videosekvencií.

#### **4. Stereoskopia a princíp fungovania VR a AR**

Stereoskopia je technológia, ktorá vytvára ilúziu trojrozmernej hĺbky z dvoch dvojrozmerných obrazov. Princíp je založený na tom, ako funguje ľudské videnie:

Naše oči sú od seba vzdialené niekoľko centimetrov, takže každé oko vidí svet z mierne odlišného uhla. Mozog tieto dva obrazy spojí a na základe rozdielov medzi nimi vypočíta hĺbku a vzdialenosť objektov.

- **Princíp fungovania zariadení pre virtuálnu realitu (VR):**
    
    - **VR headset** (napr. Meta Quest 3, PlayStation VR2) je v podstate displej (alebo dva samostatné displeje) umiestnený priamo pred očami.
    - Pre **každé oko sa vykresľuje samostatný, mierne posunutý obraz**, čím sa presne simuluje prirodzené stereoskopické videnie.
    - Vstavané senzory (gyroskopy, akcelerometre) a externé kamery sledujú polohu a natočenie hlavy. Keď pohnete hlavou, obraz v headsete sa okamžite aktualizuje, čo vytvára dokonalú ilúziu, že sa nachádzate a pozeráte okolo seba vo virtuálnom svete. Týmto vás VR úplne **ponorí (imerzia)** do digitálneho prostredia a oddelí od reality.
- **Princíp fungovania zariadení pre rozšírenú realitu (AR):**
    
    - **AR nezatvára používateľa do virtuálneho sveta, ale pridáva digitálne prvky do reálneho sveta.**
    - Zariadenia ako smartfóny, tablety alebo špeciálne priehľadné okuliare (napr. Microsoft HoloLens, Apple Vision Pro) používajú svoju **kameru na snímanie reálneho prostredia**.
    - Softvér potom v reálnom čase analyzuje tento obraz, rozpoznáva povrchy (podlahu, stôl) a následne na displej **"dokreslí" 3D objekty** tak, aby to vyzeralo, že sú súčasťou reálneho priestoru.
    - Príkladom je hra _Pokémon GO_, kde vidíte cez kameru reálnu ulicu a hra na ňu dokreslí postavičku pokémona.