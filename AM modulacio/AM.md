# Jegyzőkönyv

## Téma: Amplitúdómoduláció vizsgálata a GRF-1300A trénerrel
**Név**: [Buró Bence]   
**Dátum**: 2025. február 13.

---

## 1. Bevezetés  
Az amplitúdómoduláció (AM) vizsgálata egy fontos feladat a távközlési rendszerek és RF (rádiófrekvenciás) kommunikációs technológiák megértéséhez. A feladat célja az AM jel spektrumának elemzése, a jelszint, a sávszélesség és a modulációs mélység mérésével. A vizsgálatot a GRF-1300A RF és kommunikációs tréner segítségével végeztük el.

---

## 2. Használt eszközök  
- **GRF-1300A RF és kommunikációs tréner**

<details>

  <summary>Kép megtekintése</summary>

  ![GRF](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/AM%20modulacio/k%C3%A9pek/InstekGRF-1300A.jpg)

</details>

- **GSP-730 Spektrumanalizátor**

<details>

  <summary>Kép megtekintése</summary>

  ![GSP](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/AM%20modulacio/k%C3%A9pek/GSP-730.png)

</details>

- **HMO-1002 Digitális tárolós oszcilloszkóp**

<details>

  <summary>Kép megtekintése</summary>

  ![HMO](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/AM%20modulacio/k%C3%A9pek/hmo1002.jpg)

</details>

---

## 3. Előkészítés  
A következő lépéseket végeztük el a mérés előtt:
1. **Csatlakozás**: A GRF-1300A RF tréner RF kimenetét csatlakoztattuk a GSP-730 spektrumanalizátor RF bemenetéhez. Az oszcilloszkópot az amplitúdómodulációs jel megfigyelésére használtuk.
2. **Kezdeti beállítások**: A GRF-1300A tréneren az alábbi beállításokat végeztük el:
   - Vivőfrekvencia: 880 MHz
   - Moduláló jel: 100 kHz szinuszjel
   - Modulációs mélység: 100%

---

## 4. Mérési feladatok és eredmények

### 4.1. Első mérés: 880 MHz vivőfrekvenciával, 100 kHz moduláló jellel és 100% modulációs mélységgel

- **Spektrumanalizátor mérés**:
   - A spektrum elemzése alapján a fő vivőfrekvencia 880 MHz volt. A spektrumban a két oldalcsúcs (frekvenciaváltás) és a vivőfrekvencia körüli jelszintek jól láthatóak voltak.
   - **Jelszint**: A spektrumanalizátor szerint a jelszint értéke -31,7 dBm volt a vivőfrekvencián.
   - **Sávszélesség**: A sávszélesség 3 MHz volt, amely megfelelt az elvárt értéknek 100% modulációs mélység esetén.
   - **Modulációs mélység**: Az 100%-os modulációs mélységet a spektrum és az oszcilloszkópon mért értékek is megerősítették.
   
- **Oszcilloszkópos mérés**:
   - A moduláló jel amplitúdóját az oszcilloszkópon mértük.
   - **Moduláló jel szintje (Vpp)**: A mért érték 1 Vpp volt.


<details>

  <summary>Kép megtekintése</summary>

  ![1](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/AM%20modulacio/k%C3%A9pek/SCR00.BMP)

</details>

<details>

  <summary>Kép megtekintése</summary>

  ![2](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/AM%20modulacio/k%C3%A9pek/SCR01.BMP)

</details>
   
---

### 4.2. Második mérés: 900 MHz vivőfrekvenciával, 500 kHz moduláló jellel és 63% modulációs mélységgel

- **Spektrumanalizátor mérés**:
   - A vivőfrekvencia 900 MHz-ra módosult, és a moduláló jel 500 kHz lett.
   - **Jelszint**: A spektrumanalizátor mérése alapján a jelszint -32,1 dBm-ra emelkedett a vivőfrekvencián.
   - **Sávszélesség**: A sávszélesség 5 MHz-re nőtt, mivel a moduláló jel frekvenciája is nagyobb lett.
   - **Modulációs mélység**: A spektrum és oszcilloszkóp mérése alapján a modulációs mélység 63%-nak felelt meg.

- **Oszcilloszkópos mérés**:
   - A moduláló jel amplitúdóját ismét az oszcilloszkóppal mértük.
   - **Moduláló jel szintje (Vpp)**: A mért érték 1.2 Vpp volt.

   
<details>

  <summary>Kép megtekintése</summary>

  ![3](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/AM%20modulacio/k%C3%A9pek/TA01.PNG)

</details>

<details>

  <summary>Kép megtekintése</summary>

  ![4](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/AM%20modulacio/k%C3%A9pek/TA02.PNG)

</details>
   

---

## 5. Következtetés

A mérés során az amplitúdómoduláció (AM) jellemző paraméterei – jelszint, sávszélesség, modulációs mélység és moduláló jel szintje – sikeresen dokumentálásra kerültek. Az AM spektrumot a spektrumanalizátor segítségével elemeztük, és az oszcilloszkóppal mértük a moduláló jel amplitúdóját.

- Az első mérés 880 MHz vivőfrekvencián és 100 kHz moduláló jellel 100%-os modulációs mélységgel jellemzően stabil jelszintet és sávszélességet eredményezett.
- A második mérés 900 MHz vivőfrekvencián és 500 kHz moduláló jellel, 63%-os modulációs mélységgel mutatta a frekvencia és modulációs mélység hatását a jelszintre és sávszélességre.

A mérési eredmények alapján az AM jel vizsgálata és jellemzése sikeresen megvalósult.

---

## Jegyzőkönyv zárása  
A mérési eredmények és a dokumentált adatok alapján a feladat sikeresen befejeződött.

---

**Aláírás**  
Név: [Buró Bence]   
Dátum: 2025. február 13.
