# Jirkas-prog

**Home Assistant · PC aplikace · Android · ESP32**

Nástroje pro vlastní zařízení, domácí automatizaci a tvoření. Tento rozcestník pomáhá najít zdrojové kódy, instalaci a aktuální vydání.

[Doplňky pro Home Assistant](https://github.com/Jirkas-prog/home-assistant-addons) · [Jirka Store](https://github.com/Jirkas-prog/jirka-store) · [Instalační balíčky](https://github.com/Jirkas-prog/jirka-store/releases)

---

## Home Assistant

Společný repozitář pro instalace a aktualizace doplňků:

```text
https://github.com/Jirkas-prog/home-assistant-addons
```

Přidejte adresu v Home Assistantu do seznamu repozitářů obchodu s doplňky. Dokumentaci a podmínky jednotlivých aplikací najdete v jejich složkách.

| Projekt | Kde začít |
| :--- | :--- |
| **Home Assistant Add-ons** | [Přehled doplňků a instalace](https://github.com/Jirkas-prog/home-assistant-addons#readme) |
| **FastShare Play** | [Aktuální zdroje ve společném repozitáři](https://github.com/Jirkas-prog/home-assistant-addons/tree/main/fastshare_play) |

Samostatný repozitář `fastshare-play` uchovává starší vývoj. Nové aktualizace FastShare Play patří do společného repozitáře výše.

## PC a Windows

| Projekt | Zaměření | Odkazy |
| :--- | :--- | :--- |
| **Jirka Store** | Obchod a launcher se společným katalogem aplikací | [Zdrojové kódy](https://github.com/Jirkas-prog/jirka-store) · [Vydání](https://github.com/Jirkas-prog/jirka-store/releases) |
| **FreeCAD Fusion** | Rozhraní pro FreeCAD: ribbon, strom modelu, časová osa a nástroje CAD | [Dokumentace a stav podpory](https://github.com/Jirkas-prog/freecad-fusion#readme) |

## Android

| Projekt | Zaměření |
| :--- | :--- |
| [**ArtCraft**](https://github.com/Jirkas-prog/artcraft_android) | Aplikace pro Android a tablet |
| [**FreeCAD Android**](https://github.com/Jirkas-prog/freecad-android) | Experimentální offline CAD s WebAssembly a rozhraním FusionFlow |
| [**Termux Zephyr**](https://github.com/Jirkas-prog/termux-zephyr-android) | Android projekt založený na Termuxu |
| [**Jirka Store**](https://github.com/Jirkas-prog/jirka-store) | Android klient společného katalogu |

## ESP32

Zdrojové kódy, nastavení sestavení a testy pro jednotlivá zařízení:

| Projekt | Zaměření |
| :--- | :--- |
| [**Z-Lamp**](https://github.com/Jirkas-prog/z-lamp) | Zigbee světla, Wi-Fi/BLE brána a Android klient |
| [**IRrem**](https://github.com/Jirkas-prog/irrem) | Infračervený ovladač, MQTT a Home Assistant |
| [**ESP Termostat**](https://github.com/Jirkas-prog/esp-termostat) | Experimentální dvojice propojených jednotek |
| [**ESP Termostat Solo**](https://github.com/Jirkas-prog/esp-termostat-solo) | Samostatná jednotka, teplotní sondy, web a MQTT |
| [**ESP Christmas Lights**](https://github.com/Jirkas-prog/esp-christmas-lights) | LED řetěz, stmívání, režimy a časové plány |
| [**ESP LoRa Chat**](https://github.com/Jirkas-prog/esp-lora-chat) | Lokální chat a přenos dat mezi dvěma rádiovými uzly |
| [**ESP Desk Buddy**](https://github.com/Jirkas-prog/esp-desk-buddy) | Stolní kamarád s animovanými očima a Home Assistant Assist |

Jde o zdrojové snímky; konkrétní provedené kontroly a omezení jsou v `VALIDATION.md` každého projektu. Osobní konfiguraci si doplňte až místně. Tyto importy nepřidávají nová binární vydání.

## Linux

Samostatná ověřená linuxová vydání zatím v tomto přehledu nejsou. Dostupnost zdrojového kódu sama o sobě nepotvrzuje podporu Linuxu; rozhoduje dokumentace konkrétního projektu.

---

**Před instalací:** ověřte platformu, verzi a požadavky v dokumentaci projektu. Zdrojový snímek a vydaný instalační balík mohou mít odlišný stav rozpracovanosti.
