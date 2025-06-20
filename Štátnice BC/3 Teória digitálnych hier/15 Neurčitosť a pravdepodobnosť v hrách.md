**TLDR: Neurčitosť a pravdepodobnosť v hrách**

- **Načo slúži:** Pravdepodobnosť a náhodnosť (RNG) robia hry napínavými, nepredvídateľnými a znovuhrateľnými. Používa sa všade: v boji (šanca na zásah), pri vypadávaní predmetov (loot) aj pri generovaní máp.
    
- **Zručnosť vs. Náhoda:** Väčšina hier je mixom oboch. Zručnosť v nich nespočíva v istote, ale v **manažovaní rizika** a robení rozhodnutí, ktoré maximalizujú vaše šance na úspech (napr. v hrách ako X-COM alebo poker).
    
- **Ľudský faktor je problém:** Ľudia sú zlí v chápaní skutočnej náhodnosti. Podliehame **"omylu hazardného hráča"** (keďže mi to 3x nevyšlo, teraz už _musí_) a viac si pamätáme smolu než šťastie, čo vedie k pocitu, že hra je "nefér".
    
- **Riešenie dizajnérov:** Aby predišli frustrácii, vývojári často "podvádzajú" a používajú **riadenú náhodnosť**. Napríklad, po sérii neúspechov vám hra tajne mierne zvýši šancu na úspech, aby bol zážitok menej frustrujúci a pôsobil férovejšie.

---

### **Neurčitosť a Pravdepodobnosť v Hrách**

Neurčitosť je jedným z najdôležitejších nástrojov herného dizajnéra. Zabraňuje tomu, aby sa hra stala len deterministickým a predvídateľným "puzzle", a vnáša do nej napätie, vzrušenie, prekvapenie a znovuhrateľnosť. Hlavným nástrojom na riadenie neurčitosti je **pravdepodobnosť**.

#### **1. Pravdepodobnosť vo vzťahu k iným mechanikám**

Pravdepodobnosť nie je samostatná mechanika, ale skôr vlastnosť, ktorá ovplyvňuje takmer všetky ostatné systémy v hre:

- **Boj:** Šanca na zásah, šanca na kritický zásah, rozsah poškodenia (napr. útok spôsobí 10-15 bodov poškodenia), šanca na blokovanie alebo úskok.
- **Získavanie predmetov (Loot):** Šanca, že z porazeného nepriateľa vypadne vzácny predmet.
- **Generovanie sveta:** Procedurálne generované mapy (_Minecraft_, _No Man's Sky_) využívajú náhodnosť na vytvorenie unikátnych svetov pri každom hraní.
- **Umelá inteligencia (AI):** Nepriatelia môžu mať určitú pravdepodobnosť, že použijú rôzne útoky alebo taktiky, aby ich správanie nebolo predvídateľné.
- **Výroba (Crafting):** Šanca na úspešné vylepšenie predmetu.

#### **2. Základy pravdepodobnosti a generátory náhodnosti**

- **Základy pravdepodobnosti:** V jednoduchosti, pravdepodobnosť je pomer priaznivých výsledkov ku všetkým možným výsledkom. Šanca, že na šesťstennej kocke padne šestka, je 1/6 (približne 16.7%).
- **Náhodnosť a Generátory náhodnosti (RNG):** V digitálnych hrách neexistuje skutočná náhoda. Namiesto nej sa používa **generátor náhodných čísel (Random Number Generator - RNG)**. Je to algoritmus, ktorý vytvára sekvenciu čísel, ktorá sa javí ako náhodná. Keď hra potrebuje rozhodnúť, či váš 90% útok trafí cieľ, vygeneruje náhodné číslo od 1 do 100. Ak je číslo 90 alebo menšie, útok trafí. Ak je 91 alebo vyššie, minie. Kvalita a "férovosť" RNG je častou témou diskusií medzi hráčmi.

#### **3. Očakávaná hodnota (Expected Value - EV)**

Očakávaná hodnota je kľúčový matematický koncept, ktorý umožňuje hráčom robiť racionálne rozhodnutia v podmienkach neistoty. Je to **priemerný výsledok, ktorý by ste dosiahli, ak by ste danú akciu opakovali nekonečne veľakrát**.

Vypočíta sa ako súčet (pravdepodobnosť výsledku * hodnota výsledku) pre všetky možné výsledky.

Príklad:

Máte na výber dva meče:

- **Meč A:** Spôsobí vždy presne **15 bodov** poškodenia. (Očakávaná hodnota je 15).
- **Meč B:** Má 50% šancu spôsobiť **10 bodov** a 50% šancu spôsobiť **25 bodov** poškodenia.
    - Očakávaná hodnota Meča B = (0.50 * 10) + (0.50 * 25) = 5 + 12.5 = **17.5**.

Z hľadiska očakávanej hodnoty je Meč B v dlhodobom horizonte lepší. Hráč sa však môže rozhodnúť pre Meč A, ak potrebuje spoľahlivý, garantovaný výsledok a nemôže si dovoliť riskovať nízke poškodenie.
#### **4. Interakcia zručností a pravdepodobnosti**

Každú hru možno umiestniť na spektrum medzi čistou zručnosťou a čistou náhodou.

- **Hry s vysokou zručnosťou (nízka náhodnosť):** Napríklad **šach** alebo **Go**. Tieto hry sú takmer úplne deterministické. Neobsahujú žiadne prvky náhody. Lepší hráč takmer vždy vyhrá.
- **Hry s vysokou náhodnosťou (nízka zručnosť):** Napríklad **hracie automaty** alebo **Človeče, nehnevaj sa**. Výsledok je takmer výhradne závislý od šťastia.
- **Hry v strede (kombinácia zručnosti a náhody):** Toto je najväčšia a najpopulárnejšia kategória. Hry ako **poker**, **X-COM**, **Hearthstone** alebo **Dungeons & Dragons**.
    - V týchto hrách **zručnosť spočíva v manažmente pravdepodobnosti**. Dobrý hráč nerobí "správne" ťahy, ale ťahy, ktoré **maximalizujú jeho šance na úspech** a minimalizujú riziko. Aj keď urobíte najlepší možný ťah, stále môžete prehrať kvôli smole (a naopak, zlý hráč môže vyhrať vďaka šťastiu). Táto kombinácia vytvára napätie, prekvapivé zvraty a umožňuje slabším hráčom občas poraziť silnejších.

#### **5. Ľudský faktor – Vnímanie pravdepodobnosti**

Ľudský mozog je notoricky zlý v intuitívnom chápaní štatistiky. Naše pocity o náhodnosti sa často nezhodujú s matematickou realitou. Tento nesúlad vedie k frustrácii a je dôležitou výzvou pre herných dizajnérov.

- **Omyl hazardného hráča (Gambler's Fallacy):** Mylné presvedčenie, že minulé náhodné udalosti ovplyvňujú budúce. ("Už mi trikrát po sebe padla červená, teraz _musí_ padnúť čierna.") Hráči to prežívajú neustále: "Už som trikrát minul 90% šancu na zásah, štvrtýkrát to už _musí_ vyjsť!" V skutočnosti je každá udalosť nezávislá a šanca je stále 90%.
    
- **Potvrdzovacia zaujatosť (Confirmation Bias) a Negativita:** Oveľa intenzívnejšie si pamätáme situácie, kedy nám náhoda uškodila (minuli sme istý zásah), než keď nám pomohla (mali sme šťastie a trafili sme 10% šancu). To vedie k pocitu, že "RNG je proti mne" alebo "táto hra je nefér".
    
- **Dizajnérske riešenia – "Riadená náhoda":** Aby predišli frustrácii hráčov, vývojári často "podvádzajú" v prospech hráča a používajú systémy, ktoré nie sú úplne náhodné.
    
    - **Pseudo-Random Distribution:** V hrách ako _Dota 2_ alebo _League of Legends_ sa šanca na kritický zásah mierne zvyšuje s každým útokom, ktorý _nebol_ kritický. Tým sa zabráni dlhým sériám smoly.
    - **"Pity Timers" (Časovače z ľútosti):** V hrách s loot boxami alebo kartovými balíčkami systém garantuje, že hráč dostane vzácny predmet po určitom počte neúspešných pokusov.

**Záver:** Pravdepodobnosť je silný, no dvojsečný nástroj. Na jednej strane je nevyhnutná pre vytváranie napätia, znovuhrateľnosti a strategickej hĺbky. Na druhej strane, jej surová, matematicky čistá podoba je často v rozpore s ľudskou psychológiou a môže viesť k frustrácii. Úlohou dobrého dizajnéra je použiť náhodnosť tak, aby vytvorila zaujímavé a férové výzvy, a zároveň ju jemne "ohýbať", aby bol výsledný zážitok pre hráča uspokojivý.