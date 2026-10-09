# Változások

## 1.1.0 – 2026-10-10

- **WiFi-út:** a hálózat nevét is elfogadja (Wi-Fi Connection szenzor – ajánlott), vagy több BSSID-t vesszővel
  elválasztva. Korábban egyetlen BSSID kellett, ami kétsávos vagy több routeres otthonban sokszor nem egyezett, és a
  kapu nem nyílt. Ha a telefon a zónába lépéskor már az otthoni WiFi-n van, nem vár tovább. Kis- és nagybetű nem számít.
  A korábbi beállítások (egy BSSID) változatlanul működnek.
- **README:** új „Telefon beállítása” fejezet – helyhozzáférés („Mindig”, pontos hely), akkumulátor-korlátozás és
  automatikus indítás (Xiaomi, Samsung, Huawei), a szenzorok bekapcsolása az appban ÉS a Home Assistantban,
  ellenőrzés és hibakeresés.

## 1.0.0 – 2026-10-09

Első kiadás: kétfaktoros automata kapu-/garázsajtó-nyitás érkezéskor (zóna + Bluetooth és/vagy WiFi), független
rendszámfelismerési út, külön megadható kapuhelyzet-forrás (pl. mágneses érzékelő vagy küszöbös sablon),
cooldown, éjszakai tiltás, opcionális auto-zárás. Értesítés kamera-pillanatképpel csak a kapu tényleges kinyílása után;
ha a kapu 30 mp alatt sem jelez nyitott állapotot, sikerüzenet helyett figyelmeztetés.
