---
dg-publish: true
---
**TLDR: 2D grafika v hrách**

- **Dva základné typy:**
    
    - **Rastrová (Bitmap):** Obraz zložený z mriežky pixelov. Väčšina 2D hier ju používa pre postavy (sprity) a pozadia. Pri zväčšení sa rozpixeluje.
    - **Vektorová:** Obraz definovaný matematicky (krivky, čiary). Dá sa ľubovoľne zväčšovať bez straty kvality. Používa sa hlavne pre herné rozhranie (UI).
- **Historický vývoj:** Vzhľad starých 2D hier bol priamo daný **technologickými limitmi**:
    
    - **8-bitová éra (NES):** Veľmi málo farieb a nízke rozlíšenie viedli ku kreatívnym riešeniam a ikonickému, jednoduchému štýlu.
    - **16-bitová éra (SNES):** Považovaná za "zlatý vek". Viac farieb a vyššie rozlíšenie umožnili vznik komplexného a detailného 2D umenia, ktoré dnes poznáme ako **pixel art**.
- Pixel art dnes:
    
    V súčasnosti už nie je nutnosťou, ale vedomou umeleckou voľbou. Nezávislí vývojári ho milujú pre jeho nostalgiu, čitateľnosť a jedinečnú estetiku. Moderné hry ako Celeste alebo Stardew Valley často kombinujú pixel art s modernými technológiami (plynulé animácie, efekty), ktoré na starých konzolách neboli možné.

---

### **2D grafika v digitálnych hrách**

2D (dvojrozmerná) grafika označuje všetky vizuálne prvky, ktoré existujú na plochej rovine a majú len dva rozmery: šírku a výšku. Pre herný priemysel bola po desaťročia jedinou dostupnou formou a jej vývoj je priamo spojený s technologickým pokrokom hardvéru. Dnes zažíva renesanciu ako špecifický umelecký štýl.

#### **1. Vektorová vs. Rastrová Grafika – Dva Základné Prístupy**

Na začiatok je kľúčové pochopiť dva odlišné spôsoby, akými sa dá 2D obraz vytvoriť a uložiť.

- **Rastrová grafika (Bitmap):**
    
    - **Ako funguje:** Obraz je zložený z mriežky farebných bodov – **pixelov**. Je to ako digitálna mozaika. Každý pixel má presne určenú polohu a farbu.
    - **Vlastnosti:**
        - **Výhody:** Dokáže zobraziť komplexné a detailné obrazy s jemnými farebnými prechodmi (napr. fotografie).
        - **Nevýhody:** Pri zväčšení stráca kvalitu a obraz sa "rozpixeluje" (stáva sa zrnitým a neostrým). Veľkosť súboru závisí od rozlíšenia a počtu farieb.
    - **Využitie v hrách:** Drvivá väčšina 2D hernej grafiky, najmä postavičky (**sprity**) a pozadia, je rastrová. Je to dominantný prístup.
- **Vektorová grafika:**
    
    - **Ako funguje:** Obraz nie je zložený z pixelov, ale je definovaný matematickými rovnicami – pomocou bodov, čiar, kriviek a plôch. Je to skôr ako technický výkres.
    - **Vlastnosti:**
        - **Výhody:** Dá sa **ľubovoľne zväčšovať a zmenšovať bez straty kvality**. Veľkosť súborov je zvyčajne veľmi malá.
        - **Nevýhody:** Nie je vhodná na zobrazenie fotorealistických obrazov. Je ideálna pre logá, ikony, text a jednoduché, čisto pôsobiace ilustrácie.
    - **Využitie v hrách:** V rannej histórii sa používala v arkádových hrách ako _Asteroids_ (1979), ktoré používali špeciálne vektorové monitory (CRT) na zobrazenie ostrých čiar. Dnes sa bežne používa na prvky používateľského rozhrania (UI), mapy alebo v hrách s veľmi štylizovaným, "kresleným" vzhľadom.

#### **2. Vývoj 2D Grafiky v Hrách – Cesta od Blokov k Umeniu**

Vzhľad 2D hier bol vždy priamo ovplyvnený technologickými obmedzeniami danej doby, najmä výkonom procesora, kapacitou pamäte a schopnosťami grafického čipu.

- **Vývoj rozlíšenia (Resolution):**
    
    - **Rozlíšenie** je počet pixelov na obrazovke (napr. 640x480). Čím vyššie rozlíšenie, tým ostrejší a detailnejší obraz.
    - V ére **Atari 2600 (2. generácia)** bolo rozlíšenie extrémne nízke (cca 160x192 pixelov), čo viedlo k veľmi abstraktnej, blokovej grafike, kde veľkú časť práce musela urobiť fantázia hráča.
    - **NES (3. generácia, 8-bit)** prinieslo skok na rozlíšenie cca 256x240, čo už umožnilo vytvoriť rozpoznateľné postavy a svety.
    - **SNES/Sega Mega Drive (4. generácia, 16-bit)** ďalej zvýšili rozlíšenie, čo viedlo k detailnejším a komplexnejším sprajtom a pozadiam.
- **Vývoj farebnej hĺbky (Color Depth):**
    
    - **Farebná hĺbka** určuje, koľko farieb dokáže systém naraz zobraziť.
    - **Atari 2600** dokázalo zobraziť len pár farieb na jednej obrazovej linke, čo viedlo k typickému blikaniu a dúhovým efektom.
    - **NES** malo paletu 54 farieb, no naraz mohlo na obrazovke zobraziť len 25 z nich, pričom jednotlivé sprajty mali ešte prísnejšie obmedzenia (často len 3 farby + priehľadná). Tieto limity donútili umelcov byť extrémne kreatívnymi a viedli k vzniku ikonického vizuálneho štýlu (napríklad fúzy a čiapka Super Maria vznikli preto, že bolo ťažké na tak malom počte pixelov vykresliť ústa a vlasy).
    - **SNES** predstavovalo obrovský skok. Z palety 32,768 farieb dokázalo naraz zobraziť 256. To umožnilo umelcom používať tieňovanie, farebné prechody a vytvárať vizuálne bohaté a atmosferické svety. Táto éra je považovaná za **zlatý vek 2D grafiky a pixel artu**.

#### **3. Pixel Art a Historické Prvky v Súčasných Hrách**

Po nástupe 3D grafiky v polovici 90. rokov sa 2D grafika dostala do úzadia, no nikdy úplne nezmizla. V posledných 10-15 rokoch zažíva obrovskú renesanciu, najmä na nezávislej scéne, a to vo forme **pixel artu**.

- Čo je Pixel Art?
    
    Nie je to len "stará" alebo "škaredá" grafika. Je to zámerná a vedomá umelecká forma, kde umelec ručne a precízne umiestňuje každý jeden pixel, aby vytvoril špecifickú estetiku. Je to digitálny ekvivalent mozaiky alebo krížikovej výšivky.
    
- **Prečo je dnes populárny?**
    
    1. **Nostalgia:** Pripomína hráčom "zlatý vek" 8-bitových a 16-bitových hier.
    2. **Čitateľnosť:** Jasne definované tvary a obmedzená paleta často vedú k veľmi prehľadnej grafike, kde hráč okamžite vie, čo je postava, čo je nepriateľ a čo je pozadie.
    3. **Estetická hodnota:** Má svoj unikátny šarm a krásu, ktorý mnohí hráči a umelci obľubujú.
    4. **Praktickosť pre nezávislých vývojárov:** Pre malé tímy je oveľa uskutočniteľnejšie vytvoriť kvalitnú a vizuálne pútavú pixel artovú hru, než sa snažiť konkurovať miliónovým rozpočtom veľkých štúdií v oblasti realistickej 3D grafiky.
- Moderné využitie:
    
    Súčasné pixel artové hry často kombinujú historickú estetiku s modernými technológiami. Používajú vysoké rozlíšenie (pre ostrý obraz), plynulé animácie (vďaka modernému hardvéru), dynamické osvetlenie a komplexné časticové efekty, ktoré na pôvodných konzolách neboli možné.
    
    - **Príklady:** _Stardew Valley_, _Celeste_, _Shovel Knight_, _Dead Cells_, _Sea of Stars_.

**Záver:** 2D grafika prešla dlhú cestu od technickej nutnosti, ktorá bola definovaná prísnymi hardvérovými limitmi, až po rešpektovaný a rozmanitý umelecký štýl. Zatiaľ čo v minulosti umelci bojovali s obmedzeniami, aby vytvorili ikonické svety, dnes si tieto "obmedzenia" vyberajú dobrovoľne, aby vytvorili vizuálne jedinečné a nostalgické zážitky, ktoré dokážu konkurovať aj najmodernejším 3D hrám.