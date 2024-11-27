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