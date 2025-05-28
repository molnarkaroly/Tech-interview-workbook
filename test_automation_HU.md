<span style="
    background-image: linear-gradient(to right,rgb(42, 126, 9),rgb(15, 3, 122));
    color: white; 
    padding: 3px 20px; 
    border-radius: 10px;
    font-size: 25px;
">Tesztautomatizálási kérdések </span>

## Tesztelési alapok (ISTQB-hez kapcsolódó)
<img src="https://www.mindsmapped.com/wp-content/uploads/2016/06/ISTQB.jpg" alt="image" width="300" height="220">

#### ✅ Mi a tesztelés célja? Mi nem az?
#### A tesztelés célja:
- felfedezze a hibákat
- biztosítsa, hogy egy rendszer vagy termék megfelelően működjön
#### A tesztelés nem helyettesíti
- a fejlesztést
- nem előzi meg a hibákat
- nem dönt a végleges termék jóváhagyásáról
- nem a felhasználói visszajelzések gyűjtésére szolgál.

#### ✅ Mik a tesztelési alapelvek?

-   **Hibák Felfedezése:**
    -   A tesztelés célja a hibák felfedezése.
    -   Segít a minőség biztosításában.

-   **Teljes Tesztelés Lehetetlensége:**
    -   A teljes tesztelés lehetetlen.
    -   A tesztelés kockázatértékelés alapján történik.

-   **Korai Tesztelés:**
    -   Segít a költségek csökkentésében.

-   **Hibák Újraellenőrzése:**
    -   Szükséges.
    -   Ennek oka, hogy a hibajavítások újabb hibákat okozhatnak.

-   **Kontextusfüggő Tesztelés:**
    -   Különböző megközelítést igényel különböző projektek esetén.

-   **Nem Garantálja a Hibamentességet:**
    -   A hiedelmekkel ellentétben a tesztelés nem garantálja a hibamentességet.

#### ✅ Mi az egységtesztelés (unit testing)? Ki felelős az egységtesztek írásáért?
-   **Definíció:**
    -   Szoftverfejlesztési módszer.
    -   A szoftver legkisebb egységeinek (funkciók, metódusok) külön-külön történő tesztelése.
    -   Célja: megbizonyosodni arról, hogy helyesen működnek.

-   **Felelős Személyek:**
    -   Általában a fejlesztők.
    -   Ok: ők ismerik legjobban a kódot és annak működését.

-   **Előnyök/Célok:**
    -   Segít a hibák korai felismerésében és javításában.
    -   Hozzájárul a kód minőségének javításához.

#### ✅ Mik a tesztszintek, és mi a különbség köztük?
-   **Tesztszintek:**
    -   Komponens tesztelés
    -   Integrációs tesztelés
    -   Rendszer tesztelés
    -   Rendszerintegrációs tesztelés
    -   Elfogadási tesztelés

-   **Különbség:**
    -   Ezek a tesztszintek a rendszer egyre nagyobb egységeit tesztelik.
    -   A tesztelés a legkisebb egységektől a teljes rendszerig halad.

#### ✅ Mi a különbség a verifikáció és a validáció között?
-   **Verifikáció:**
    -   Azt jelenti, hogy egy termék vagy szolgáltatás megfelel-e a specifikációnak.
    -   Vizsgálja, hogy "helyesen lett-e megvalósítva".
    -   A specifikáció szerinti működést vizsgálja.

-   **Validáció:**
    -   Azt jelenti, hogy egy termék vagy szolgáltatás megfelel-e a felhasználó elvárásainak.
    -   Vizsgálja, hogy "hasznos-e a felhasználó számára".
    -   A felhasználó elvárásai szerinti működést vizsgálja.

-   **Különbség:**
    -   A verifikáció a specifikáció szerinti működést vizsgálja.
    -   A validáció a felhasználó elvárásai szerinti működést vizsgálja.

#### ✅ Mik a tesztelési típusok, és mi a különbség köztük?
-   **Teszttípusok:**
    -   Funkcionális tesztelés
    -   Nem funkcionális tesztelés
    -   Biztonsági tesztelés

-   **Különbségek / Jellemzők:**
    -   **Funkcionális tesztelés:**
        -   A szoftver funkcióit teszteli.
    -   **Nem funkcionális tesztelés:**
        -   A szoftver nem funkcionális jellemzőit teszteli.
        -   Példák: teljesítmény, biztonság (általános jellemzőként), felhasználói élmény.
    -   **Biztonsági tesztelés:**
        -   A szoftver biztonsági jellemzőit és ellenálló képességét teszteli.

#### ✅ Mi a különbség a fehér doboz, szürke doboz és fekete doboz tesztelés között?
-   **Fehér Doboz Tesztelés:**
    -   A tesztelő ismeri a kód belső működését.
    -   Ez alapján írja a teszteket.

-   **Szürke Doboz Tesztelés:**
    -   A tesztelő részleges ismeretekkel rendelkezik a kód belső működéséről.
    -   Ennek alapján írja a teszteket.

-   **Fekete Doboz Tesztelés:**
    -   A tesztelő nem ismeri a kód belső működését.
    -   A teszteket anélkül írja.


#### ✅ Mi a különbség a felhasználói elfogadási teszt (UAT) és a rendszerteszt között?
-   **Felhasználói Elfogadási Teszt (UAT):**
    -   A rendszer tesztelésének egy fázisa.
    -   Során a felhasználók ellenőrzik, hogy a rendszer megfelel-e a felhasználói elvárásoknak.
    -   A felhasználói elvárásokra fókuszál.

-   **Rendszerteszt:**
    -   A teljes rendszer tesztelését jelenti.
    -   Során a rendszer funkcionalitását, teljesítményét és biztonságát tesztelik.
    -   A teljes rendszerre fókuszál.

-   **Különbség:**
    -   A **UAT** a felhasználói elvárásokra fókuszál.
    -   A **rendszerteszt** a teljes rendszerre fókuszál.

#### ✅ Sorolj fel különbségeket a regressziós tesztelés, a füsttesztelés és az újratesztelés között!

- A **regressziós** tesztelés a változtatások hatását vizsgálja.
- A **füsttesztelés** a szoftver kritikus részeit teszteli.
- Az **újratesztelés** pedig a hibajavítások hatását vizsgálja.

#### ✅ Mi a különbség a statikus és dinamikus tesztelés között?
A statikus tesztelés során a kód áttekintése történik, hogy megtaláljuk a hibákat, míg a dinamikus tesztelés során a kód futtatása történik, hogy megtaláljuk a hibákat.

### ✅ Hasonlítsd össze a V-modellt, a vízesés modellt és az Agile megközelítést a tesztelés szempontjából!
#### 1. V-modell
-   **Tesztelés Időzítése:**
    -   A fejlesztési fázisokkal párhuzamosan történik.
-   **Tesztelés Célja:**
    -   A **minőség** biztosítása.

#### 2. Vízesés Modell (Waterfall)
-   **Tesztelés Időzítése:**
    -   Egy későbbi fázisban történik.
-   **Tesztelés Célja:**
    -   A **hibák** keresése.

#### 3. Agile Megközelítés
-   **Tesztelés Időzítése:**
    -   Iteratív folyamat.
    -   A fejlesztési ciklusokkal párhuzamosan történik.
-   **Tesztelés Célja:**
    -   A **minőség** biztosítása **és** a **hibák** keresése.


<img src="https://t4.ftcdn.net/jpg/03/90/15/65/360_F_390156585_8w1lsOyICIAOvDCU8tExXW2QwLCOFwXD.jpg" alt="image" width="550" height="400">


<img src="https://i.imgur.com/S38EBJw.png" alt="image" width="550" height="400">   <img src="https://segedletek.level14.hu/assets/img/modszertan-vizeses.svg" alt="image" width="550" height="400">


<img src="https://promanconsulting.hu/wp-content/uploads/2022/03/agilis-modszertanok-optimized.jpg" width="550" height="400">







## Reporting, Bugs
<img src="https://moolya.com/blog/wp-content/uploads/2023/05/Bug-Report.png" alt="image" width="300" height="220">

#### ✅ Milyen lépéseket követnél egy hiba megtalálásakor?
-    A hiba megértése és reprodukálása
     -   A probléma pontos meghatározása
     -   A hiba reprodukálása
     -   Információgyűjtés
- A hiba izolálása
- A hiba okának azonosítása (Diagnózis)
     - Tesztelés
     - Kódelemzés
- A hiba kijavítása
    - Megoldási terv készítése
    - A javítás implementálása
    - Tesztelés
-  Ellenőrzés és dokumentáció
    - A javítás ellenőrzése
    - Dokumentálás

## ✅ Beszélj a gyakori tesztjelentésekről és részleteikről!

Gyakori Tesztjelentések és Részleteik


### 1. Teszt Összefoglaló Jelentés (Test Summary Report)

*   **Célja:** Gyors, magas szintű áttekintés a menedzsment 
*   **Főbb Tartalmi Elemek:**
    *   Hibák száma súlyosság szerint.
    *   Főbb kockázatok és következtetések a kiadásra vonatkozóan.

### 2. Hibajelentés / Defektjelentés (Bug/Defect Report)

*   **Célja:** Egy konkrét hiba részletes dokumentálása
*   **Főbb Tartalmi Elemek:**
    *   Egyedi felismrhető cím.
    *   Összefoglaló (rövid leírás).
    *   Reprodukálás lépései.
    *   Várt és tényleges eredmény.
    *   Súlyosság és prioritás. 
    *   Környezet (operációs rendszer, böngésző, stb.).
    *   Csatolmányok (képernyőképek, logok).

### 3. Részletes Tesztvégrehajtási Jelentés (Detailed Test Execution Report)

*   **Célja:** Részletes információk az egyes tesztesetek végrehajtásáról és azok konkrét eredményeiről
*   **Főbb Tartalmi Elemek:**
    *   Teszteset azonosítója és leírása.
    *   Végrehajtás státusza (sikeres, sikertelen, blokkolt stb.).
    *   Tényleges eredmények, eltérések.

### 4. Tesztelési Előrehaladási Jelentés (Test Progress Report)

*   **Célja:** Rendszeres (pl. napi, heti) frissítés a tesztelési tevékenységek haladásáról a tervhez képest.
*   **Főbb Tartalmi Elemek:**
    *   Jelentési időszak.
    *   Elvégzett és tervezett feladatok.
    *   Talált és javított hibák száma az adott időszakban.
    *   Esetleges akadályozó tényezők.

## ✅ Mit tartalmaz egy hibajelentés?

### Egy Hibajelentés Tartalma


*   **Összefoglaló / Cím:** Rövid, lényegre törő leírás arról, hogy mi a hiba.
*   **Leírás / Reprodukálás Lépései:**
    *   Részletes, lépésről-lépésre útmutató, hogyan lehet előidézni a hibát.
*   **Várt Eredmény:** Mi kellett volna, hogy történjen a lépések végrehajtása után.
*   **Tényleges Eredmény:** Mi történt valójában a lépések végrehajtása után 
*   **Súlyosság (Severity):** Mennyire kritikus a hiba, milyen mértékben befolyásolja az alkalmazás funkcionalitását vagy használhatóságát
*   **Prioritás (Priority):** Mennyire sürgős a hiba kijavítása az üzleti fontosság vagy a felhasználói élmény szempontjából
*   **Környezet (Environment):**
    *   Szoftver verziója, ahol a hibát felfedezték.
    *   Operációs rendszer ( verzió).
    *   Böngésző (verzió).
    *   Hardver specifikációk 
    *   Egyéb környezeti tényezők (pl. hálózati beállítások).
*   **Csatolmányok (Attachments):**
    *   Képernyőképek a hibáról.
    *   Videófelvételek a hiba előfordulásáról.
    *   Naplófájlok (logok).
    *   Adatbázis dumpok vagy releváns adatok.
*   **Jelentő (Reported by):** A személy neve, aki a hibát jelentette.
*   **Jelentés Dátuma (Date Reported):** A hiba jelentésének időpontja.
*   **Érintett Modul/Funkció:** Az alkalmazás melyik része, funkciója érintett a hibában.
*   **Státusz (Status):** A hiba aktuális állapota a javítási folyamatban

#### ✅ Hogyan rangsorolnál egy hibát?

*   **1. Súlyosság (Severity):** [2]
    *   **A hiba technikai hatása a rendszerre.**
        *   *Például:* Kritikus (rendszer leáll), Magas (fontos funkció nem megy), Közepes (kisebb funkcióhibák), Alacsony (esztétikai).

*   **2. Prioritás (Priority):** [2]
    *   **A javítás sürgőssége üzleti/projekt szempontból.**
        *   *Például:* Azonnali, Magas, Közepes, Alacsony.


## Test Automation, Selenium
<img src="https://media.licdn.com/dms/image/C4D12AQE3GOyVsZazOw/article-cover_image-shrink_600_2000/0/1583830696602?e=2147483647&v=beta&t=bYHbKyhMoWsMgtEug6eSf3m0db5ZtGEl437TeS1qkfI" alt="image" width="320" height="220">

#### ✅ Melyik teszteseteket érdemes automatizálni és melyiket nem?

**✅ Érdemes Automatizálni:**

*   **Gyakran Ismétlődő Tesztek:**
    *   Regressziós tesztek  
    *   Smoke tesztek és Sanity tesztek (alapvető funkcionalitás gyors ellenőrzése minden build után).
*   **Adatvezérelt Tesztek:**
    *   Amikor ugyanazt a tesztlogikát sok különböző adatbevitellel kell ellenőrizni.
*   **Komplex Számításokat vagy Pontos Ellenőrzést Igénylő Tesztek:**
    *   Ahol az emberi hiba kockázata magas.
*   **Teljesítmény- és Terheléses Tesztek:**
    *   Nagy mennyiségű felhasználó szimulálása, amit manuálisan nehéz lenne.
*   **Kereszt-platform és Kereszt-böngésző Tesztek:**
    *   Ugyanazon tesztek futtatása több környezetben.
*   **Hosszadalmas, Időigényes Manuális Folyamatok:**
    *   Például bonyolult telepítési vagy konfigurációs lépések ellenőrzése.

**❌ Nem Érdemes Automatizálni:**

*   **Felfedező Tesztelés (Exploratory Testing):**
*   **Használhatósági Tesztek (Usability Testing):**
    *   A felhasználói élményt, a rendszer könnyű kezelhetőségét emberi szemszögből kell értékelni.
*   **Gyakran Változó Funkciók vagy UI Elemeinek Tesztjei:**
    *   Magas lenne a szkriptek folyamatos karbantartási igénye
*   **Szubjektív Értékelést Igénylő Tesztek:**
    *   Például vizuális megjelenés, design elemek tökéletessége

#### ✅ Írj le egy jó automatizált tesztet!

*   **Megbízható és Megismételhető:** Ugyanazon körülmények között mindig ugyanazt az eredményt adja.
*   **Könnyen Olvasható és Érthető** 
*   **Karbantartható:** Könnyen frissíthető, ha az alkalmazás változik.
*   **Célzott:** Egy specifikus funkcionalitást vagy viselkedést ellenőriz.
*   **Gyors Visszajelzést Ad:** Egyértelműen jelzi a sikert vagy hibát.


#### ✅ Mi a Selenium, Selenium IDE és Selenium WebDriver?

#### Selenium

*   **Definíció:** A Selenium egy nyílt forráskódú **keretrendszer-csomag**, amely eszközök és könyvtárak gyűjteménye webböngészők automatizálására.
*   **Főbb Jellemzők:**
    *   Több programozási nyelvet támogat (Java, Python, C#, Ruby, JavaScript stb.). 
    *   Szinte minden modern webböngészőt támogat (Chrome, Firefox, Safari, Edge stb.). 
    *   Több operációs rendszeren fut (Windows, macOS, Linux).
    *   Lehetővé teszi a böngészőbeli interakciók (kattintás, gépelés, navigáció stb.) szimulálását.

#### Selenium IDE (Integrated Development Environment)

*   **Definíció:** A Selenium IDE egy **böngészőbővítmény** (Chrome és Firefox számára), amely lehetővé teszi a felhasználói interakciók rögzítését és visszajátszását a böngészőben.  
*   **Főbb Jellemzők:**
    *   **Record and Playback:** Rögzíti a böngészőben végzett műveleteket és újra lejátssza azokat. 
    *   Egyszerűbb tesztesetek létrehozása kódírás nélkül (bár korlátozottan exportálható kód). 
    *   Parancsok szerkesztése, hibakeresés.
    *   Könnyen tanulható kezdők számára. 
    *   Korlátozottabb képességű a WebDriverhez képest komplexebb scenáriókban, ciklusokban, feltételes logikában.

#### Selenium WebDriver

*   **Definíció:** A Selenium WebDriver egy **programozási interfész (API)** és könyvtárkészlet, amely lehetővé teszi a webböngészők natív szintű vezérlését kódból.
*   **Főbb Jellemzők:**
    *   **Közvetlen böngészővezérlés:** A böngésző saját automatizálási támogatását használja. 
    *   **Platformfüggetlenség:** Különböző operációs rendszereken fut.
    *   **Rugalmasság:** Támogatja a komplex tesztlogikákat, feltételes utasításokat, ciklusokat, külső adatforrások használatát.
    *   Jól integrálható más tesztelési keretrendszerekkel és eszközökkel (pl. TestNG, JUnit, Maven).

#### ✅ Hogyan lehet azonosítani a webes elemeket?
-  A webes elemeket egyedi azonosítókkal, úgynevezett lokátorokkal (pl. ID, Name, Class Name, CSS Selector, XPath) lehet azonosítani az automatizált tesztekben.


#### ✅ Hogyan lehet várni az elemekre, és mi lehet a probléma? Gyűjtsd össze a lehetséges hibákat és okokat!

### Hogyan Lehet Várni Elemekre, és Mi Lehet a Probléma?

A modern weboldalak dinamikusan töltődnek be, ezért az automatizált teszteknek gyakran várniuk kell, amíg egy elem elérhetővé vagy interaktívvá válik. [26]

**Várakozási Stratégiák:**

*   **Implicit Várakozás (Implicit Wait):**
    *   Globális beállítás, ami megadja, hogy a WebDriver legfeljebb mennyi ideig várjon egy elem megtalálására, mielőtt hibát dobna.
*   **Explicit Várakozás (Explicit Wait):**
    *   Egy konkrét elemre vagy feltételre (pl. láthatóság, kattinthatóság) vár egy megadott ideig, mielőtt továbblépne vagy hibát dobna.
*   **Fluent Várakozás (Fluent Wait):**
    *   Az explicit várakozás egy fejlettebb formája, ahol a várakozási idő, a lekérdezési gyakoriság és az figyelmen kívül hagyandó kivételek is konfigurálhatók.

**Lehetséges Hibák és Okok:**

*   **`NoSuchElementException` (Az elem nem található):**
    *   **Rossz lokátor:** A használt ID, XPath, CSS szelektor stb. hibás vagy nem egyedi.
    *   **Időzítési probléma:** Az elem még nem töltődött be a DOM-ba, amikor a keresés történt (a várakozás hiánya vagy elégtelensége).
    *   **Elem rejtett:** Az elem a DOM-ban van, de nem látható (pl. `display: none`).
    *   **Elem `iframe`-ben van:** Át kell váltani az `iframe`-re a keresés előtt.
    *   **Oldal még nem teljesen betöltve:** A keresés túl korán történik.

*   **`TimeoutException` (Időtúllépés):**
    *   Az explicit vagy fluent várakozás során a megadott időkereten belül nem teljesült a várt feltétel. 
    *   Lassú hálózati kapcsolat vagy szerverválasz.


*   **`ElementNotInteractableException` (Az elem nem interaktív):**
    *   Az elem megtalálható a DOM-ban és látható, de valamilyen okból nem lehet vele interakcióba lépni (pl. kattintani, szöveget beírni).
    *   **Másik elem elfedi:** Egy átfedő elem (pl. felugró ablak, töltőképernyő) blokkolja az interakciót.
    *   **Elem le van tiltva (`disabled` attribútum).**
    *   **Elem még nem teljesen betöltve/renderelve** az interakcióhoz.
    *   Az elem még animáció alatt áll.

*   **`StaleElementReferenceException` (Elavult elem referencia):**
    *   Az elem DOM-struktúrája megváltozott (pl. AJAX frissítés, oldal navigáció) az elem megtalálása és a vele való interakció kísérlete között.  Az elem korábbi referenciája már nem érvényes. 
    *   `Megoldás`: Újra meg kell keresni az elemet a művelet előtt.

#### ✅ Hasonlítsd össze a POM és a Keyword Driven Testing megközelítéseket!


**POM (Page Object Model):** 
*   Az alkalmazás UI-ját oldalakra bontja; minden oldal egy osztály, ami az elemeit és a velük végezhető műveleteket tartalmazza.
*   Főleg UI változások könnyebb kezelésére és olvashatóbb tesztkódra fókuszál.

**Keyword Driven Testing (KDT):**
*   A teszteket kulcsszavak sorozatából (pl. "bejelentkezés", "adatbevitel") építi fel, melyekhez konkrét implementációk (kód) tartoznak.
*   `Célja`, hogy kevésbé technikai személyek is írhassanak teszteket és az adatvezérelt tesztelést támogassa.

**Összehasonlítás dióhéjban:**

| Jellemző            | POM (Page Object Model)                             | Keyword Driven Testing (KDT)                           |
| :------------------ | :-------------------------------------------------- | :--------------------------------------------------- |
| **Absztrakciós Egység** | Weboldalak/UI Komponensek                           | Műveletek                              |
| **Teszt Írás**      | Programozási nyelven | Jellemzően táblázatos forma, kulcsszavak használata |
| **Fő Előny**        | UI változások könnyű kezelése, kódszintű olvashatóság | Tesztek írása kevesebb technikai tudással|
| **Komplexitás**     | Közepes             | Magas  |
| **Technikai Tudás (tesztíró)** | Programozási ismeret szükséges        | Kevesebb (kulcsszó használathoz)                       |


#### ✅ Mi a különbség a TDD és BDD között?

**TDD (Test-Driven Development):**
*   **Fókusz:** A kód *egységeinek* (funkciók, metódusok) helyes működése.
*   **Cél:** Jobb kódszerkezet, kevesebb hiba
*   **"Ki?"**: Főleg a fejlesztők.

**BDD (Behavior-Driven Development):**
*   **Fókusz:** Az alkalmazás *viselkedésének* leírása és tesztelése természetes nyelven, az üzleti elvárások alapján. A tesztek példákon keresztül (szcenáriók) definiálják, hogyan kell működnie a szoftvernek.
*   **Cél:** Jobb kommunikáció és együttműködés az üzleti és technikai oldalak között, a szoftver az elvárt üzleti értéket szállítja.
*   **"Ki?"**: Csapatmunka (fejlesztők, tesztelők, üzleti elemzők, terméktulajdonosok).

| Jellemző            | TDD (Tesztvezérelt Fejlesztés)          | BDD (Viselkedésvezérelt Fejlesztés)             |
| :------------------ | :------------------------------------ | :------------------------------------------- |
| **Elsődleges Cél**  | Kód funkcionalitásának ellenőrzése      | Alkalmazás viselkedésének validálása          |
| **Nézőpont**        | Fejlesztői, "belülről kifelé"           | Üzleti/Felhasználói, "kívülről befelé"         |
| **Együttműködés**  | Főleg fejlesztői fókuszú                 | Csapat szintű (üzlet, fejlesztők)      |
| **Teszt Nyelve**    | Általában programozási nyelv  | Természetes nyelvhez közeli   |
| **Fókusz**          | Kód egységei, implementációs részletek  | Rendszer viselkedése, üzleti érték             |
| **Eredmény**        | Jól tesztelt, moduláris kód             | Közösen megértett, az elvárásoknak megfelelő szoftver |

**Fontos:** A BDD nem helyettesíti a TDD-t, hanem kiegészíti azt. 

#### ✅ Mi az API tesztelés és miért hasznos?


**Mi az API Tesztelés?**

*   Az alkalmazásprogramozási felületek (API-k) közvetlen tesztelése.
*   A szoftver üzleti logikájának ellenőrzése felhasználói felület (UI) nélkül.
*   `Fókuszban`: *funkcionalitás, megbízhatóság, teljesítmény, biztonság*

**Miért Hasznos?**

*   **Korai Hibafelismerés:** Problémák azonosítása az üzleti logikában, mielőtt a UI elkészül.
*   **Gyorsabb Tesztek:** Jelentősen gyorsabb, mint a UI tesztek, mert nincs UI renderelés. 
*   **Nagyobb Tesztlefedettség:** Olyan logikák is tesztelhetők, amik UI-n keresztül nehezen elérhetők.
*   **Nyelv- és Platformfüggetlenség:** Szabványos protokollok (HTTP) és formátumok (JSON/XML)
*   **Stabilabb Tesztek:** API interfészek ritkábban változnak, mint a UI, így kevesebb a tesztkarbantartás.
*   **Költséghatékonyság:** Gyorsabb, korábbi hibajavítás olcsóbb.
*   **Biztonsági Tesztelés:** Fontos a hitelesítés, engedélyezés és adatvédelem ellenőrzésére.
*   **Integrációs Tesztek Könnyítése:** Komponensek és mikroszolgáltatások együttműködésének hatékony ellenőrzése.

#### ✅ Mi az adatvezérelt tesztelés és miért hasznos?

Az adatvezérelt tesztelés egy olyan szoftvertesztelési módszertan, ahol a tesztadatokat (bemeneti értékek és elvárt kimenetek) külső adatforrásokból (pl. Excel táblázat, CSV fájl, adatbázis) olvassuk be, ahelyett, hogy fixen a tesztkódba égetnénk őket. Ugyanazt a tesztlogikát (szkriptet) hajtjuk végre többször, különböző tesztadat-készletekkel.

**Miért Hasznos?**

*   **Nagyobb Tesztlefedettség Könnyedén:** Lehetővé teszi ugyanazon funkció tesztelését számos különböző adatbevitellel (pozitív, negatív, határértékek), növelve a lefedettséget minimális extra kódírással.
*   **Újrahasznosíthatóság és Hatékonyság:** Ugyanaz a tesztszkript használható több adatsorral, csökkentve a redundanciát.
*   **Adatok és Tesztlogika Szétválasztása:** Tisztábbá és karbantarthatóbbá teszi a tesztkódot, mivel a tesztadatok függetlenek a tesztlogikától. 
*   **Könnyebb Karbantartás:** A tesztadatok módosítása vagy bővítése nem igényel változtatást a tesztszkriptben, csak a külső adatforrás frissítését. 
*   **Kevesebb Teszteset (Kódsor):** Egyetlen szkript képes sokféle adatvariációt kezelni.
*   **Nem technikai felhasználók bevonása:** A tesztadatokat olyan személyek is könnyebben kezelhetik és bővíthetik, akik nem rendelkeznek mély programozási ismeretekkel.

#### ✅ Mi az adatvezérelt tesztelés és miért hasznos?
### Mi az adatvezérelt tesztelés?

*   **Definíció:** Olyan szoftvertesztelési módszertan, ahol a tesztelési adatok (bemenetek és várt kimenetek) elkülönülnek a tesztlogikától (a tesztszkripttől).
*   **Működés:** Ugyanaz a tesztszkript futtatható többször, különböző adatállományokkal.
*   **Adatforrás:** Az adatokat külső forrásból olvassa be (pl. CSV, Excel táblázat, adatbázis, XML).

### Miért hasznos?

*   **Újrafelhasználhatóság:**
    *   A tesztlogika többször felhasználható eltérő adatokkal.
*   **Karbantarthatóság:**
    *   Könnyebb az adatokat frissíteni, mint magát a kódot módosítani.
    *   A tesztadatok és a tesztlogika külön kezelhető, módosítható.
*   **Nagyobb tesztlefedettség:**
    *   Könnyen lehet sokféle forgatókönyvet (pozitív, negatív, határesetek) tesztelni új adatsorok hozzáadásával.
*   **Hatékonyság:**
    *   Kevesebb ismétlődő kód, gyorsabb tesztkészítés.
    *   Automatizálás esetén különösen előnyös.
*   **Skálázhatóság:**
    *   Új tesztesetek hozzáadása gyakran csak új adatok hozzáadását jelenti a külső fájlba/adatbázisba.
*   **Átláthatóság:**
    *   A tesztadatok egy helyen, strukturáltan kezelhetők, könnyebben áttekinthetők.
    *   Nem műszaki szakemberek (pl. üzleti elemzők) is könnyebben hozzájárulhatnak a tesztadatok készítéséhez.

#### ✅ Mik a kihívások és ajánlott eljárások a dinamikusan betöltött webes elemekkel?

####  Kihívások:

*   **Időzítés:** Az elem nincs ott/kész, amikor a teszt keresi.
*   **Aszinkronitás:** AJAX/JS műveletek miatt nehéz megjósolni az elemek állapotát.
*   **Instabil lokátorok:** Dinamikusan generált ID-k, DOM változások.

#### Ajánlott Eljárások:

*   **Explicit Várakozás (`WebDriverWait`):** Várj egy adott feltételre (pl. láthatóság, kattinthatóság).
*   **Stabil Szelektorok:** Használj egyedi, megbízható lokátorokat (pl. `data-testid`).
*   **Oldal Objektum Modell (POM):** Várakozási logikát az oldal objektumokba építeni.
*   **`Thread.sleep()` kerülése:** Megbízhatatlan és lassú.

#### ✅ Mik a mobil tesztautomatizálás kihívásai?


## Haladó témák
<img src="https://www.softwaretestinghelp.com/wp-content/qa/uploads/2020/05/DevOps-in-a-Selenium-Testing.png" alt="image" width="320" height="220">

#### ✅ Mi a különbség a CI és CD között?

#### ✅ Írj le egy Continuous Delivery folyamatot!

#### ✅ Hasonlítsd össze két népszerű CI rendszert, ezek közül az egyik legyen a Jenkins!

#### ✅ Mi a Docker és miért hasznos?