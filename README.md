# Nástroje PH – doplněk pro Archicad

Doplněk pro Archicad 29 a 30 (Windows i macOS) s nástroji pro projektanty pozemních staveb a architekty.
Autor: Pavel Halgaš · web a kontakt: <https://pavelhalgas.com/archicad-doplnek/>

## Co doplněk umí

### Odhad nákladů
- výpočet podle obestavěného prostoru pomocí zón a cenových ukazatelů ve stavebnictví
- možnost zadat vlastní cenu
- výběr zón podle vrstvy a varianty návrhu
- součástí je schéma tabulky (Interactive Schedule)

### Hromadný import dat z .gpkg (GIS)
- import souboru .gpkg, např. sítě nebo prostorová situace z portálu DMVS
- vlastní pojmenování jednotlivých vrstev
- barva a typ čáry pro každou vrstvu
- uložení nastavení a export nastavení do souboru
- u vrstevnic s výškou vloží i popisku výškové kóty

## Stažení

Aktuální verzi najdete v [Releases](../../releases/latest).

| | Archicad 29 | Archicad 30 |
|---|---|---|
| **Windows** | `Nastroje-PH-win-ac29.zip` | `Nastroje-PH-win-ac30.zip` |
| **macOS** | `Nastroje-PH-mac-ac29.zip` | `Nastroje-PH-mac-ac30.zip` |

Každý ZIP obsahuje doplněk (`Nastroje PH.apx` na Windows, `Nastroje PH.bundle` na macOS)
a schéma tabulky pro odhad nákladů (`.xml`).

Pozor: doplněk pro Archicad 30 na macOS vyžaduje macOS 14.1 nebo novější.

## Instalace

1. ZIP rozbalte a doplněk uložte do složky podle své preference.
2. V menu *Volby* otevřete *Správce doplňků*.
3. Klikněte na *Přidat* a vyberte soubor `.apx` (Windows) nebo `.bundle` (macOS).
   Případně doplněk dejte do složky, ze které Archicad načítá ostatní doplňky
   (*Načíst doplňky z určené složky*).
4. Při instalaci nové verze stačí starou nahradit novou a restartovat Archicad.
5. Schéma tabulky importujete v nastavení tabulek (*Schémata tabulek*).

## Podpis

- **macOS:** doplněk je podepsaný certifikátem Developer ID a notarizovaný Applem.
- **Windows:** doplněk není digitálně podepsaný. Prohlížeč nebo SmartScreen proto může
  stažený ZIP označit jako neznámý. Archicad ho načte normálně.

## Zdroje dat a licence

Data z ČÚZK a dalších veřejných zdrojů, pokud je do projektu vkládáte, podléhají
vlastním licenčním podmínkám (ČÚZK: CC BY 4.0, uveďte zdroj).
Doplněk samotný je poskytován bez záruky.

## Hlášení chyb

Kontakt najdete na <https://pavelhalgas.com/archicad-doplnek/>.
