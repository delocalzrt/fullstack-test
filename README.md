# Full-stack fejlesztési teszt

A feladat célja, hogy átfogó betekintést nyújtson a jelentkező **webfejlesztési**  és  **API-integrációs**  készségeibe. A feladat egy  **teljes értékű webalkalmazást**  igényel, ahol a  **frontend**és a  **backend**  komponensek  **API-n keresztül kommunikálnak**  egymással.

**Feladat:**

Fejlessz egy olyan webapp-ot, ahol a felhasználóknak lehetőségük van regisztráció / bejelentkezés után kedvenc cikkeiket linkkel elmenteni egy adatbázisba, ahonnan a későbbiekben könnyen elérhetik azt. Az alkalmazás a linket egy képpel (ha értelmezhető), egy rövid leírással (ha értelmezhető) és a cikk címével mentse el a rendszer. Az elmentett linkek egymás alatt vagy mellett helyezkedjenek el egy reszponzív grid rendszerben, kártya-szerű megjelenítéssel. Az elmentett linket legyen lehetőség törölni, és listában legyen lehetőség a címre keresve szűrni.

**Kritériumok:**

-   **API-vezérelt frontend:**  A frontendnek  **teljes mértékben az API-ra kell támaszkodnia**  az adatok betöltéséhez és a funkciók megvalósításához. Ez azt jelenti, hogy a frontendnek  **nem szabad közvetlenül kommunikálnia az adatbázissal**.
-   **Továbbfejlesztett felhasználói felület:**  A frontend legyen **interaktív**  és  **letisztult**. A frontend funkcionalitás felépítéséhez csak **vanilla javascript** használható, **keretrendszerek nem**.
-   **API végpontok:**  A backendnek  **több API végpontot**  kell biztosítania a frontend számára, amelyek különböző funkciókat fednek le (pl. felhasználókezelés, adatlekérés, adatküldés).
-   **Hitelesítési és engedélyezési logika:**  A backendnek  **robosztus hitelesítési és engedélyezési logikát**  kell megvalósítania, amely biztosítja a felhasználók adatainak védelmét és a jogosulatlan hozzáférést.
-   **Hibakezelés és naplózás:**  Mind a frontend, mind a backend komponenseknek  **hatékony hibakezelési és naplózási mechanizmusokkal**  kell rendelkezniük a problémák azonosításához és elhárításához.
-   **Ideális esetben** nem használsz keretrendszert a backend oldalon sem, látni szeretnénk, milyen a logikád, hogyan gondolkodsz

**Feladatok benyújtása:**

A feladatot publikus Github repo-ban, vagy .zip fájlba csomagolva kell benyújtani. A következőket kell tartalmaznia:

-   A backend kód (pl. index.php, api.php, db.php)
-   A frontend kód (pl. index.html, app.js, components, styles)
-   Az adatbázis szerkezete (pl. create_table.sql)
-   A feladathoz kapcsolódó dokumentáció (pl. README.md)

**Értékelés:**

A feladatot a következő szempontok alapján fogják értékelni:

-   A feladat  **teljesítése**
-   A kód  **minősége**  (olvashatóság, áttekinthetőség, hibamentes működés)
-   A  **frontend felépítése** és a vanilla js hatékony használata
-   Az  **API-k**  megvalósítása
-   A  **biztonságos hitelesítési**  és  **engedélyezési logika**
-   A  **hatékony hibakezelés**  és  **naplózás**
-   A  **kreativitás**
-   A  **hatékonyság**
-   A  **megjegyzések**  használata

**További információk:**
A feladat elkészítésére 5 nap áll rendelkezésre. Kérdés esetén írj emailt!
