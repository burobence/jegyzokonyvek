
# Jegyzőkönyv: Hálózati konfiguráció és tesztelés

## Bevezetés

Ez a jegyzőkönyv a Linksys router beállítását és a hozzá kapcsolódó hálózati eszközök tesztelését dokumentálja. A feladat során IP-címek kezelése, routing tábla megtekintése, ping tesztek és egyéb hálózati parancsok alkalmazása történt.




## Eszközök
A tesztelés során a következő eszközökkel dolgoztam:
- **Catalyst 2950 switch**: A hálózati eszközök közötti kapcsolatot biztosította.
- **Linksys router**: A hálózat központi irányítószerveként szerepelt.
- **ThinkPad laptop**: A teszteléshez használt számítógép, amelyről a ping tesztek és egyéb parancsok futtak.
- **Mobiltelefon**: Ezzel csatlakoztam a Linksys routerhez, hogy a laptop és a többi eszköz között pingelni tudjak.
## 1. A számítógép IP beállításainak lekérdezése
Parancs: `ipconfig`
<details>
  <summary>Kép megtekintése</summary>

  ![IPCONFIG](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/iphalo/k%C3%A9pek/ping%201.PNG)

</details>

## 2. Az aktuális IP-cím eldobása
Parancs: `ipconfig /release`
<details>

  <summary>Kép megtekintése</summary>

  ![release](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/iphalo/k%C3%A9pek/release.PNG)

</details>

## 3. Új IP-cím kérése
Parancs: `ipconfig /renew`
<details>

  <summary>Kép megtekintése</summary>

  ![renew](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/iphalo/k%C3%A9pek/renew.PNG)

</details>

## 4. A routing tábla megjelenítése
Parancs: `netstat -a`
<details>

  <summary>Kép megtekintése</summary>

  ![netstat-a](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/iphalo/k%C3%A9pek/lista.PNG)

</details>

## 5. A microsoft.com szerver elérhetőségének tesztelése
Parancs: `ping microsoft.com`
<details>

  <summary>Kép megtekintése</summary>

  ![microsoft](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/iphalo/k%C3%A9pek/microsoft.PNG)

</details>

## 6. Az www.ipon.hu szerver felé vezető útvonal lekövetése
Parancs: `tracert www.ipon.hu`
<details>

  <summary>Kép megtekintése</summary>

  ![tracert](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/iphalo/k%C3%A9pek/ipon.PNG)

</details>

## 7. Használt portok listázása
Parancs: `netstat -f`
<details>

  <summary>Kép megtekintése</summary>

  ![netstat-f](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/iphalo/k%C3%A9pek/FQDN.PNG)

</details>

## 8. Hálózati kapcsolatok megjelenítése
Parancs: `netsh interface show interface`
<details>

  <summary>Kép megtekintése</summary>

  ![netsh](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/iphalo/k%C3%A9pek/nslookup.PNG)

</details>

## 9. DNS-beállítások aktualizálása
Parancs: `ipconfig /flushdns`
<details>

  <summary>Kép megtekintése</summary>

  ![flushdns](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/iphalo/k%C3%A9pek/DNS.PNG)

</details>

## 10. Csatolt hálózati meghajtók megjelenítése
Parancs: `net use`
<details>

  <summary>Kép megtekintése</summary>

  ![netuse](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/iphalo/k%C3%A9pek/net%20use.PNG)

</details>

## 11. A www.ipon.hu tartománynév és IP-cím megjelenítése
Parancs: `nslookup www.ipon.hu`
<details>

  <summary>Kép megtekintése</summary>

  ![Ipon](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/iphalo/k%C3%A9pek/ipon.PNG)
  ![Ipon](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/iphalo/k%C3%A9pek/nslookup.PNG)

</details>

## 12. Telefon rákapcsolódva a Wi-Fi-re
<details>
  <summary>Kép megtekintése</summary>

  ![telcsati]
</details>

## 13. Telefon pingelése laptopról
<details>
  <summary>Kép megtekintése</summary>

  ![telping](https://raw.githubusercontent.com/burobence/jegyzokonyvek/refs/heads/main/iphalo/k%C3%A9pek/ping%20telefon.PNG)
</details>

## 14. Router konfigurációk
<details>
  <summary>Kép megtekintése</summary>

  ![routercon]()
</details>

<details>
  <summary>Kép megtekintése</summary>

  ![routercon1]
</details>

<details>

  <summary>Kép megtekintése</summary>

  ![routercon2]
</details>

## Összegzés
A tesztelés során a **Linksys router**, a **Catalyst 2950 switch** és a többi hálózati eszköz zökkenőmentesen működtek együtt. Az IP-konfigurációk kezelése, a routing tábla megjelenítése és a különböző hálózati parancsok futtatása sikeresen zajlott. A mobiltelefonnal való csatlakozás lehetővé tette a laptop és a többi eszköz közötti kommunikációt.
