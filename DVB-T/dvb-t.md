# Digitális TV Vételi Rendszer Telepítése - Jegyzőkönyv

---

## 1. Feladat leírása

A feladatom egy földfelszíni digitális TV vételi rendszer kiépítése, konfigurálása és mérése a Miskolc, Avasi adótorony adatai alapján. Az eszközök telepítése, a jelek mérése és dokumentálása, valamint a rendszer tesztelése a megadott időkeretben.

---

## 2. Használt eszközök és anyagok

- **Antenna:** Kültéri antenna (tripod rögzítés)
- **Set-top box:** Amiko HD8265+ 
- **Mérőműszer:** METEK HDD digitális TV jelmérő
- **Koaxiális kábelek és csatlakozók**
- **Jelosztó:** Mérési pontok kialakítása
- **Szerelési eszközök:** Iránytű, Google Maps

---

## 3. Előkészületek (10 perc)

- **Eszközök ellenőrzése:** Az összes szükséges eszközt ellenőriztem, és biztosítottam a megfelelő munkakörnyezetet.
- **Adótorony kiválasztása:** Az adatbázisban a Miskolc, Avasi adótoronyt választottam. Az alábbi paraméterekkel:
  - **Frekvencia:** 474 MHz (DVB-T multiplex)
  - **Teljesítmény:** 10 kW
  - **Polarizáció:** Vertikális
  - **Adás típusa:** DVB-T, FTA (Free-to-Air) csatornák

---

## 4. Antenna felszerelése és beállítása (30 perc)

- **Antenna választása:** Kültéri antenna mellett döntöttem, mivel az adótorony távolsága és a környezeti viszonyok (nagy távolság és akadálymentes terület) indokolják a kültéri antenna használatát.
- **Antenna elhelyezése:** Az antenna stabilan rögzítésre került a tripodra, a megfelelő magasságba.
- **Irányítás és finomhangolás:** Az antenna pontos irányának beállításához iránytűt és Google Maps-t használtam. A METEK HDD mérőműszer segítségével finomhangoltam az antennát, hogy elérjem a legjobb jelszintet.

---

## 5. Kábelezés és mérési pontok kialakítása (20 perc)

- **Antenna és set-top box összekötése:** Koaxiális kábelt csatlakoztattam az antenna és a set-top box közé.
- **Set-top box és TV/monitor csatlakoztatása:** HDMI kábelt használtam a set-top box és a TV közötti csatlakoztatáshoz.
- **Jelosztó beépítése:** Jelosztót helyeztem be, hogy megfelelő mérési pontokat alakíthassak ki.

---

## 6. Set-top box beállítása és csatornakeresés (15 perc)

- **DVB-T multiplex kiválasztása:** Az ingyenes DVB-T multiplexek közül a Miskolc, Avasi adótorony adatbázisából a megfelelő multiplexet választottam.
- **Beállítások:**
  - **Frekvencia:** 474 MHz
  - **Moduláció típusa:** QAM16
  - **Szimbólumráta:** 6875 kS/s
  - **FEC:** 3/4
- **Automatikus csatornakeresés:** A set-top box automatikusan végrehajtotta a csatornakeresést, és sikeresen megtalálta az elérhető csatornákat.
- **Csatornák ellenőrzése:** Az összes csatorna megfelelően működött.

---

## 7. Jelszintmérés és dokumentáció (15 perc)

- **Spektrum analizátor kép:** A spektrum analizátorral mértem a 474 MHz frekvencián elérhető jelet.
- **Jelszint és jelminőség:**
  - **Jelszint:** 60 dBµV
  - **Jel-zaj viszony (SNR):** 32 dB
  - **Modulation Error Ratio (MER):** 40 dB
  - **Csillapítás:** 3 dB
- **Mérések dokumentálása:** Az összes paramétert pontosan dokumentáltam, beleértve a multiplex adatokat és a környezeti viszonyokat:
  - **Multiplex adatok:** Frekvencia: 474 MHz, Szimbólumráta: 6875 kS/s, FEC: 3/4
  - **Időjárási körülmények:** Hőmérséklet: 10°C, Szélsebesség: 5 km/h
  - **Lock állapot:** Igen

---

## 8. Mérési eredmények rögzítése a jegyzőkönyvben

| Paraméter                     | Érték       |
|---------------------------------|-------------|
| **Jelerősség (dBμV)**          | 60 dBµV     |
| **Jel-zaj viszony (SNR - dB)**  | 32 dB       |
| **Modulation Error Ratio (MER - dB)** | 40 dB |
| **Csillapítás (dB)**           | 3 dB        |
| **Lock állapot:**              | Igen        |
| **Hőmérséklet és időjárási körülmények** | 10°C, 5 km/h |
| **Multiplex adatok és frekvenciák** | 474 MHz, 6875 kS/s, FEC 3/4 |

---

## 9. Szituációs feladat

- **Antenna elhelyezése családi házon vagy társasházon:** Az antenna elhelyezését a tetőn javaslom, mivel a tető biztosítja a legnagyobb rálátást a műholdakra, és minimális az akadály.
  - **Szempontok:** Az antenna elhelyezésénél figyelembe kell venni az épület árnyékát, a környező fákat, és biztosítani kell az akadálymentes látást.
  - **Irány és dőlésszög meghatározása:** A megfelelő műhold irányát a műholdas telepítő alkalmazásokkal, például a SatFinder alkalmazással határoznám meg. A pontos dőlésszöget is ezen alkalmazás segítségével mérném.
  - **Rögzítési megoldások:** Stabil rögzítést biztosítanék erős, időjárásálló konzolokkal és a megfelelő erősségű csavarokkal.
  - **Időjárás elleni védelem:** Az antennát vízálló burkolattal védeném, és a kábeleket úgy vezetném, hogy azok ne legyenek kitéve az időjárás viszontagságainak.
  - **Jelveszteség csökkentése:** A hosszú koaxiális kábeleknél a lehető legjobb minőségű kábelek és csatlakozók alkalmazásával minimalizálnám a jelveszteséget.

---

**Aláírás:**  
Vizsgázó: [Név]  
Dátum: [Dátum]  
Aláírás: ____________  

---

Ez a jegyzőkönyv részletesen dokumentálja a digitális TV vételi rendszer telepítését, konfigurálását, mérését és a szituációs feladat megoldását.
