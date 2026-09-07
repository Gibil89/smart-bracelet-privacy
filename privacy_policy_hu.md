# Adatkezelési Tájékoztató – Smart Bracelet

**Utolsó frissítés:** 2026. Szeptember

Ez az Adatkezelési Tájékoztató bemutatja, hogyan kezeli és védi a "Smart Bracelet" (Mobil és Wear OS) alkalmazás az Ön adatait.

## 1. Adatok, amelyeket NEM gyűjtünk
Alkalmazásunk adatvédelmi központú, Peer-to-Peer (P2P) architektúrára épül. **Nem rendelkezünk központi adatbázissal**, és **nem gyűjtjük**, tároljuk vagy osztjuk meg az Ön személyes adatait (például nevét, e-mail címét vagy tartózkodási helyét).

## 2. Engedélyek és Eszközadatok
Az alapvető funkciók biztosításához az alkalmazásnak bizonyos helyi engedélyekre van szüksége:
*   **Kamera:** Kizárólag helyileg, a párosításhoz szükséges QR-kód beolvasására szolgál. A kameraképeket az alkalmazás nem rögzíti, nem menti és nem továbbítja semmilyen szerverre.
*   **Internet / Hálózati állapot:** A rezgésminták és animációk küldéséhez és fogadásához szükséges a Google Firebase Cloud Messaging (FCM) rendszerén keresztül.

## 3. Kommunikációs Adatok (Tokenek)
Az eszközök párosításához az alkalmazás egy FCM (Firebase Cloud Messaging) tokent generál. Ez egy anonim karaktersorozat, amely az üzenetek továbbítására szolgál Ön és partnere között.
*   Ezeket a tokeneket a felhasználók közvetlenül cserélik ki QR-kód segítségével.
*   Az üzenetek ideiglenesen egy biztonságos Cloudflare Worker-en haladnak keresztül, kizárólag a kézbesítés céljából. Az üzenetek tartalmát (animációk azonosítói, rezgésminták) nem tároljuk véglegesen.

## 4. Alkalmazáson belüli vásárlások (In-App Purchases)
Alkalmazásunk prémium funkciókat kínál a Google Play számlázási rendszerén keresztül. Minden fizetési folyamatot a Google biztonságosan kezel. Nem férünk hozzá az Ön bankkártya adataihoz, számlázási címéhez vagy személyes pénzügyi adataihoz. A prémium státusz ellenőrzése helyileg és a Google API-jain keresztül történik.

## 5. Harmadik féltől származó szolgáltatások
Az alkalmazás az alábbi harmadik féltől származó szolgáltatásokat használja, amelyek saját adatvédelmi irányelvekkel rendelkeznek:
*   **Google Play Services & Firebase Cloud Messaging** (üzenetkézbesítés és számlázás)
*   **Cloudflare** (biztonságos üzenettovábbítás)

## 6. Jelen Adatkezelési Tájékoztató módosításai
Adatvédelmi irányelveinket időről időre frissíthetjük. Javasoljuk, hogy rendszeresen tekintse át ezt az oldalt az esetleges változások miatt.

## 7. Kapcsolat
Ha bármilyen kérdése vagy javaslata van az Adatkezelési Tájékoztatónkkal kapcsolatban, forduljon hozzánk bizalommal: 89.toth.tamas@gmail.com
