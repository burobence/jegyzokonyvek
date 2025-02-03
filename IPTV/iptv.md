# Jegyzőkönyv: Távközlési Technikus Vizsgafeladat

---

**Vizsgázó neve:** Buró Bence  
**Vizsga dátuma:** [Dátum]  
**Feladat tétele:** B tétel – DVB-T jel fejállomásba küldése és IPTV rendszeren való kiadása  
**Adótorony:** Miskolc, Avasi adótorony  

---

### 1. Előkészületek (10 perc)

- **Eszközök ellenőrzése:**  
  A szükséges eszközök (antenna, fejállomás, Set-top box, mérőműszer, stb.) rendben voltak, és minden eszköz elérhető volt a feladat elvégzéséhez.  

- **Munkakörnyezet:**  
  A munkakörnyezet tiszta és biztonságos, minden szükséges szerszám és eszköz rendelkezésre állt.

- **Multiplexek keresése:**  
  Az adótorony adatbázisában elérhető multiplexek (frekvencia, teljesítmény, polarizáció, adás típusa) ellenőrzése megtörtént. Az alábbi információk kerültek rögzítésre:  
  - **Frekvencia:** [Frekvencia]  
  - **Teljesítmény:** [Teljesítmény]  
  - **Polarizáció:** [Polarizáció]  
  - **Adás típusa:** [Adás típusa]  

---

### 2. Antenna felszerelése és beállítása (30 perc)

- **Antenna kiválasztása:**  
  A vizsgázó beltéri antennát választott a megfelelő vétel érdekében. Az antenna helyzete optimalizálva lett a legjobb vétel érdekében a V3 labor egyik jó vételi pontján.

- **Antenna beállítása:**  
  Az antenna pontos irányba állítása iránytű és dőlésszögmérő használatával történt. A METEK HDD mérőműszer segítségével a finomhangolás is sikeresen megtörtént.

---

### 3. Kábelezés, mérési pontok kialakítása és jel bevezetése a fejállomásba (25 perc)

- **Kábelezés:**  
  Az antenna koaxiális kábellel és osztóval lett összekötve a fejállomással. A jelosztó beépítése megtörtént a mérési pont kialakításához. A jelek megfelelően elosztásra kerültek a fejállomás bemenetein.

- **Jel bevezetése:**  
  A jelek a villamos 3 laborba kerültek bevezetésre, hogy az IPTV hálózaton keresztül továbbíthatók legyenek.

---

### 4. Fejállomás beállítása és IPTV stream konfigurálása (25 perc)

- **Fejállomás beállítása:**  
  A fejállomás bemeneteire a megfelelő multiplexek hozzárendelésre kerültek. A szabadon fogható (FTA) DVB-T jelet feldolgozták és IP streamre konvertálták.

- **Multicast IP tartomány:**  
  A megfelelő multicast IP tartomány kiválasztása megtörtént, és a streamelt IPTV csatornákhoz hozzá lettek rendelve.

- **IPTV Set-top-box konfigurálása:**  
  A MAG IPTV Set-top box csatlakoztatása és konfigurálása sikeresen megtörtént.  
  - **Hálózati kapcsolat:** A kapcsolat beállítása megfelelően történt.  
  - **Csatornakeresés:** A csatornakeresés sikeresen lezajlott, és az IPTV vétel megfelelően működik.

---

### 5. Jelszintmérés és dokumentáció (30 perc)

- **Mérések az antennánál:**  
  - **Spektrum analizátor kép:** [Kép mellékelve]  
  - **Jelszint:** [Jelszint (dBμV)]  
  - **Jel-zaj viszony (SNR):** [SNR (dB)]  
  - **Bit Error Rate (BER):** [BER]  
  - **Modulation Error Ratio (MER):** [MER (dB)]  
  - **Csillapítás:** [Csillapítás (dB)]  
  - **Lock állapot:** [ ] Igen [ ] Nem  
  - **Hőmérséklet:** [Hőmérséklet]  
  - **Időjárási körülmények:** [Szélsebesség, egyéb]  
  - **Multiplex adatok:** [Frekvencia, szimbólumráta, FEC]

- **Mérések a fejállomás után (IPTV stream):**  
  - **Multicast IP címek ellenőrzése:** [Multicast IP címek]  
  - **IPTV stream stabilitás:** [Stabil] / [Instabil]  
  - **Hálózati késleltetés és csomagvesztés:** [Késleltetés] / [Csomagvesztés]  
  - **Stream adatok:** [Adatok mentve]

---

### 6. Eszközök telepítése és hálózati tesztelés

- **VLC, Wireshark, FFmpeg, iPerf3 telepítése:**  
  A szükséges IPTV vizsgálati eszközök telepítése sikeresen megtörtént a winget csomagkezelő használatával.  
  - **VLC:** [Telepítve]  
  - **Wireshark (TShark):** [Telepítve]  
  - **FFmpeg:** [Telepítve]  
  - **iPerf3:** [Telepítve]  

- **Hálózati teljesítmény tesztelése (iperf3):**  
  - **Multicast IP cím:** 239.1.1.1  
  - **Sávszélesség:** 10 Mbps  
  - **Ping teszt:** [Válaszidő: ms]  
  - **Traceroute vizsgálat:** [Útvonal ellenőrzés]

- **Wireshark elemzés:**  
  - A multicast csomagok figyelése és a stream rögzítése sikeresen megtörtént. A csomagvesztés és hibák elemzése is megtörtént az FFmpeg segítségével.

---

### Összegzés:

A vizsgázó sikeresen elvégezte a feladatot, és minden szükséges lépést teljesített a DVB-T jel fejállomásba küldése és IPTV rendszer kiadása során. Az IPTV stream megfelelően működik, és a szükséges hálózati tesztelések is sikeresen megtörténtek.

---

### Jegyzőkönyv aláírása:

**Vizsgáztató:** [Név]  
**Aláírás:** [Aláírás]  

---

**Vizsgázó:** [Név]  
**Aláírás:** [Aláírás]  

---

Ez a jegyzőkönyv a vizsga elvégzését és annak eredményeit dokumentálja.
