---
{"dg-publish":true,"permalink":"/Štátnice BC/3 Teória digitálnych hier/30 Herný engine/","created":"2025-06-21T00:04:10.739+02:00","updated":"2025-06-28T19:47:39.949+02:00"}
---

**TLDR: Herný engine a modifikácie**

- **Čo je Herný engine:** Je to softvérová "stavebnica" pre vývojárov. Poskytuje im hotové nástroje na grafiku, fyziku, zvuk a AI, takže nemusia všetko programovať od nuly a môžu sa sústrediť na kreatívnu časť hry.
    
- **Najznámejšie enginy:**
    
    - **Unreal Engine:** Zameraný na špičkovú grafiku (napr. _Fortnite_).
    - **Unity:** Dominantný v indie a mobilných hrách (napr. _Among Us_, _Genshin Impact_).
    - **Staršie legendy:** **Source Engine** (_Half-Life 2_, _Portal_) a **id Tech** (_Doom_, _Quake_).
- **Modifikácie hier ("Modding"):** Je to úprava hry vytvorená fanúšikmi. Tento fenomén bol neuveriteľne dôležitý, pretože z neho vznikli úplne nové hry a žánre.
    
- **Najväčšie hity, ktoré začali ako modifikácie:**
    
    - _**Counter-Strike**_ začal ako mod pre hru _Half-Life_.
    - Celý žáner **MOBA** (_League of Legends_, _Dota 2_) vznikol z komunitou vytvorenej mapy pre _Warcraft III_.
    - Žáner **Battle Royale** spopularizoval mod pre hru _Arma_, z ktorého priamo vzniklo _PUBG_ (a to inšpirovalo _Fortnite_).

---

### **Herný engine: Srdce a kostra digitálnej hry**

#### **1. Základná definícia**

**Herný engine** je komplexný softvérový rámec (framework), ktorý poskytuje vývojárom základnú technológiu a nástroje potrebné na tvorbu hier. Namiesto toho, aby musel každý vývojár od nuly programovať úplne všetko, engine mu ponúka hotové, opakovane použiteľné komponenty.

Predstavte si to ako stavebnicu pre tvorbu hier. Engine poskytuje "kocky" (nástroje) a "návod" (pravidlá a logiku), ako ich spájať. Tvorca hry sa tak môže viac sústrediť na kreatívne aspekty – dizajn levelov, príbeh, hrateľnosť a grafiku – a menej na základnú, technickú infraštruktúru.

**Hlavné komponenty herného enginu:**

- **Rendering Engine (Vykresľovací engine):** Zodpovedá za všetko vizuálne – vykresľovanie 2D a 3D grafiky, svetlá, tiene, textúry a efekty.
- **Physics Engine (Fyzikálny engine):** Simuluje fyzikálne zákony – gravitáciu, kolízie objektov, správanie kvapalín, dynamiku pevných telies.
- **Audio Engine (Zvukový engine):** Spracúva a prehráva všetky zvuky v hre – hudbu, efekty, dialógy.
- **Scripting (Skriptovanie):** Umožňuje dizajnérom písať logiku hry (napr. "keď hráč stlačí páku, otvoria sa dvere") bez nutnosti zasahovať do hlbokého kódu enginu.
- **Umelá inteligencia (AI):** Poskytuje základné rámce pre správanie nepriateľov a nehráčskych postáv (NPC).
- **Sieťový kód (Networking):** Zabezpečuje komunikáciu pre multiplayerové hry.
- **Nástroje pre vývojárov:** Vizuálne editory na tvorbu levelov, animácií, používateľského rozhrania (UI) a pod.

#### **2. Príklady najúspešnejších enginov, ich vývoj a hry**

História hier je úzko spojená s vývojom legendárnych enginov, ktoré definovali celé generácie hier.

**A. id Tech (Engine hier od štúdia id Software)**

- **Vývoj:** Tento engine bol priekopníkom 3D grafiky a žánru strieľačiek z prvej osoby (FPS). Každá nová verzia znamenala technologickú revolúciu.
- **Najznámejšie hry:**
    - **Doom Engine (id Tech 1):** _Doom_ (1993) – Hoci nebol plne 3D, vytvoril ilúziu rýchleho 3D priestoru a spopularizoval FPS.
    - **Quake Engine (id Tech 2):** _Quake_ (1996) – Jeden z prvých enginov s plne 3D svetom v reálnom čase, hardvérovou akceleráciou a klient-server architektúrou pre online hranie. Jeho kód bol základom pre mnohé ďalšie hry, vrátane _Half-Life_.
    - **id Tech 3:** _Quake III Arena_ (1999) – Zadefinoval rýchle arénové strieľačky.
    - **id Tech 4:** _Doom 3_ (2004) – Priniesol revolučné dynamické osvetlenie a tiene.

**B. Unreal Engine (od Epic Games)**

- **Vývoj:** Dnes jeden z dvoch dominantných enginov na trhu. Pôvodne vytvorený pre FPS hry, postupne sa stal extrémne flexibilným a univerzálnym nástrojom. Je známy špičkovou grafikou a vizuálnymi efektmi.
- **Najznámejšie hry:**
    - **Unreal Engine 1:** _Unreal_ (1998), _Deus Ex_ (2000).
    - **Unreal Engine 2:** _BioShock_ (2007), _Mass Effect_ (2007).
    - **Unreal Engine 3:** Dominantný engine siedmej konzolovej generácie. Bežali na ňom stovky hier vrátane série _Gears of War_, _Batman: Arkham_ a _Mass Effect 2 a 3_.
    - **Unreal Engine 4 & 5:** Dnešný štandard pre vysokorozpočtové (AAA) hry. _Fortnite_, _Gears 5_, _Final Fantasy VII Remake_, _The Matrix Awakens_ (technologické demo pre UE5).

**C. Unity**

- **Vývoj:** Druhý gigant na súčasnom trhu. Na rozdiel od Unrealu, ktorý bol vždy zameraný na high-end grafiku, Unity sa presadilo vďaka svojej **dostupnosti, flexibilite a podpore viacerých platforiem**. Stalo sa dominantným enginom pre **nezávislých (indie) vývojárov a mobilné hry**.
- **Najznámejšie hry:** _Cuphead_, _Hollow Knight_, _Among Us_, _Genshin Impact_, _Pokémon GO_, _Hearthstone_.

**D. Source Engine (od Valve)**

- **Vývoj:** Nástupca Quake enginu, vytvorený pre potreby štúdia Valve. Preslávil sa pokročilou fyzikou, animáciou tvárí a schopnosťou plynulo rozprávať príbeh v hernom prostredí.
- **Najznámejšie hry:** _Half-Life 2_ (2004), _Counter-Strike: Source_, _Portal 1 a 2_, _Team Fortress 2_, _Left 4 Dead_, _Titanfall_ (upravená verzia).

#### **3. Modifikácia Hier ("Modding") ako Princíp Tvorby**

**Modifikácia (mod)** je úprava existujúcej hry vytvorená hráčmi alebo fanúšikmi. "Modderi" menia alebo pridávajú do hry nový obsah – postavy, predmety, mapy, misie, alebo úplne menia jej pravidlá a mechaniky.

Niektorí vývojári (najmä id Software a Valve) aktívne podporovali modding tým, že zverejňovali svoje nástroje a časti kódu. Tento otvorený prístup viedol k explózii kreativity a zrodu nových hier a žánrov.

Princíp kreovania nových titulov a žánrov:

V mnohých prípadoch bola modifikácia taká úspešná a originálna, že sa z nej stala samostatná komerčná hra alebo dokonca úplne nový žáner.

**Najznámejšie príklady:**

- **Counter-Strike (1999):** Začal ako **modifikácia pre hru _Half-Life_**. Tímová hra zameraná na súboj teroristov a protiteroristickej jednotky sa stala tak populárnou, že Valve najalo jej tvorcov a vydalo ju ako samostatný, komerčne úspešný titul. Dnes je to jedna z najväčších e-športových značiek na svete.
    
- **Team Fortress:** Pôvodne modifikácia pre _Quake_, neskôr pre _Half-Life_. Tímová strieľačka založená na triedach (class-based) postáv. Valve opäť najalo tvorcov a vytvorilo extrémne populárnu hru _Team Fortress 2_.
    
- **Žáner MOBA (Multiplayer Online Battle Arena):** Celý tento žáner, ktorému dnes dominujú hry ako _League of Legends_ a _Dota 2_, vznikol z jedinej modifikácie.
    
    1. Začalo to mapou **Aeon of Strife** pre stratégiu _StarCraft_.
    2. Tento koncept bol neskôr prenesený do mapy **Defense of the Ancients (DotA)** pre hru _Warcraft III_.
    3. Táto mapa sa stala globálnym fenoménom. Jej hlavní tvorcovia boli neskôr najatí spoločnosťami Riot Games (kde vytvorili _League of Legends_) a Valve (kde vytvorili _Dota 2_), čím sa z modu zrodil multi-miliardový žáner.
- **Žáner Battle Royale:** Hoci má korene aj inde, moderný boom tohto žánru odštartovala modifikácia **Battle Royale pre hru _Arma 2_** (a neskôr _Arma 3_), ktorú vytvoril Brendan Greene ("PlayerUnknown"). Jeho úspech viedol priamo k vytvoreniu samostatnej hry ***PlayerUnknown's Battlegrounds (PUBG)***, ktorá spopularizovala tento žáner a inšpirovala hry ako _Fortnite_.
    

**Záver:** Herné enginy sú technologickým základom, ktorý umožňuje a zefektívňuje vývoj hier. Poskytujú vývojárom silné nástroje na realizáciu ich vízií. História však ukazuje, že rovnako dôležitá je aj otvorenosť týchto nástrojov. Umožnenie modifikácií dalo priestor kreativite komunity, ktorá nielenže predĺžila životnosť existujúcich hier, ale stala sa aj neuveriteľne plodnou pôdou, z ktorej vyrástli úplne nové, revolučné hry a žánre, ktoré dnes dominujú hernému priemyslu.