# Tesztautomatizálási kérdések

## Tesztelési alapok (ISTQB-hez kapcsolódó)
<img src="https://www.mindsmapped.com/wp-content/uploads/2016/06/ISTQB.jpg" alt="image" width="300" height="220">

#### ✅ Mi a tesztelés célja? Mi nem az?
A tesztelés célja, hogy felfedezze a hibákat és biztosítsa, hogy egy rendszer vagy termék megfelelően működjön. A tesztelés nem helyettesíti a fejlesztést, nem előzi meg a hibákat, nem dönt a végleges termék jóváhagyásáról, és nem a felhasználói visszajelzések gyűjtésére szolgál.

#### ✅ Mik a tesztelési alapelvek?
A tesztelési alapelvek közé tartozik a hibák felfedezése, amely segít a minőség biztosításában. A teljes tesztelés lehetetlen, így kockázatértékelés alapján történik a tesztelés. A korai tesztelés segít a költségek csökkentésében. A hibakumuláció azt jelenti, hogy a hibák gyakran halmozódnak egyes modulokban. A hibák újraellenőrzése szükséges, mivel a hibajavítások újabb hibákat okozhatnak. A tesztelés kontextusfüggő, azaz különböző megközelítést igényel különböző projektek esetén. A hiedelmekkel ellentétben a tesztelés nem garantálja a hibamentességet.

#### ✅ Mi az egységtesztelés (unit testing)? Ki felelős az egységtesztek írásáért?
Az egységtesztelés a szoftverfejlesztés egy módszere, amely során a szoftver legkisebb egységeit, azaz a funkciókat vagy metódusokat teszteljük külön-külön, hogy megbizonyosodjunk arról, hogy helyesen működnek. Az egységtesztek megírásáért általában a fejlesztők felelősek, mivel ők ismerik legjobban a kódot és annak működését. Az egységtesztelés segít a hibák korai felismerésében és javításában, valamint hozzájárul a kód minőségének javításához.

#### ✅ Mik a tesztszintek, és mi a különbség köztük?
A tesztszintek a komponens, integrációs, rendszer, rendszerintegrációs és elfogadási tesztelés. Ezek a tesztszintek a rendszer egyre nagyobb egységeit tesztelik, a legkisebb egységektől a teljes rendszerig.

#### ✅ Mi a különbség a verifikáció és a validáció között?
A verifikáció azt jelenti, hogy egy termék vagy szolgáltatás megfelel-e a specifikációnak, azaz hogy helyesen lett-e megvalósítva. A validáció pedig azt jelenti, hogy egy termék vagy szolgáltatás megfelel-e a felhasználó elvárásainak, azaz hogy hasznos-e a felhasználó számára. A különbség az, hogy a verifikáció a specifikáció szerinti működést vizsgálja, míg a validáció a felhasználó elvárásai szerinti működést vizsgálja.

#### ✅ Mik a tesztelési típusok, és mi a különbség köztük?
A tesztelési típusok a funkcionális tesztelés, a nem funkcionális tesztelés és a biztonsági tesztelés. A funkcionális tesztelés a szoftver funkcióit teszteli, a nem funkcionális tesztelés a szoftver nem funkcionális jellemzőit teszteli, mint például a teljesítményt, a biztonságot és a felhasználói élményt. A biztonsági tesztelés a szoftver biztonsági jellemzőit és ellenálló képességét teszteli.

#### ✅ Mi a különbség a fehér doboz, szürke doboz és fekete doboz tesztelés között?
A fehér doboz tesztelés során a tesztelő ismeri a kód belső működését, és ez alapján írja a teszteket. A szürke doboz tesztelés során a tesztelő részleges ismeretekkel rendelkezik a kód belső működéséről, és ennek alapján írja a teszteket. A fekete doboz tesztelés során a tesztelő nem ismeri a kód belső működését, és a teszteket anélkül írja. A különbség, hogy a fehér doboz tesztelés részletes ismereteket igényel a kód belső működéséről, míg a fekete doboz tesztelés nem igényel ilyen ismereteket.
#### ✅ Mi a különbség a felhasználói elfogadási teszt (UAT) és a rendszerteszt között?
A felhasználói elfogadási teszt a rendszer tesztelésének egy fázisa, amely során a felhasználók ellenőrzik, hogy a rendszer megfelel-e a felhasználói elvárásoknak. A rendszerteszt a teljes rendszer tesztelését jelenti, amely során a rendszer funkcionalitását, teljesítményét és biztonságát tesztelik. A különbség, hogy a UAT a felhasználói elvárásokra fókuszál, míg a rendszerteszt a teljes rendszerre.
#### ✅ Sorolj fel különbségeket a regressziós tesztelés, a füsttesztelés és az újratesztelés között!

- A regressziós tesztelés a változtatások hatását vizsgálja.
- A füsttesztelés a szoftver kritikus részeit teszteli.
- Az újratesztelés pedig a hibajavítások hatását vizsgálja.

#### ✅ Mi a különbség a statikus és dinamikus tesztelés között?
A statikus tesztelés során a kód áttekintése történik, hogy megtaláljuk a hibákat, míg a dinamikus tesztelés során a kód futtatása történik, hogy megtaláljuk a hibákat.

### ✅ Hasonlítsd össze a V-modellt, a vízesés modellt és az Agile megközelítést a tesztelés szempontjából!
A V-modellben a tesztelés a fejlesztési fázisokkal párhuzamosan történik, míg a vízesés modellben a tesztelés egy későbbi fázisban történik. Az Agile megközelítésben a tesztelés iteratív folyamat, amely a fejlesztési ciklusokkal párhuzamosan történik. A V-modellben a tesztelés célja a minőség biztosítása, míg a vízesés modellben a tesztelés célja a hibák keresése. Az Agile megközelítésben a tesztelés célja a minőség biztosítása és a hibák keresése.


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

1



1


*   **`ElementNotInteractableException` (Az elem nem interaktív):**
    *   Az elem megtalálható a DOM-ban és látható, de valamilyen okból nem lehet vele interakcióba lépni (pl. kattintani, szöveget beírni).
    *   **Másik elem elfedi:** Egy átfedő elem (pl. felugró ablak, töltőképernyő) blokkolja az interakciót.
    *   **Elem le van tiltva (`disabled` attribútum).**
    *   **Elem még nem teljesen betöltve/renderelve** az interakcióhoz.
    *   Az elem még animáció alatt áll.

*   **`StaleElementReferenceException` (Elavult elem referencia):**
    *   Az elem DOM-struktúrája megváltozott (pl. AJAX frissítés, oldal navigáció) az elem megtalálása és a vele való interakció kísérlete között. [29] Az elem korábbi referenciája már nem érvényes. 
    *   Megoldás: Újra meg kell keresni az elemet a művelet előtt.

#### ✅ Hasonlítsd össze a POM és a Keyword Driven Testing megközelítéseket!

#### ✅ Mi a különbség a TDD és BDD között?

#### ✅ Mi az API tesztelés és miért hasznos?

#### ✅ Mi az adatvezérelt tesztelés és miért hasznos?