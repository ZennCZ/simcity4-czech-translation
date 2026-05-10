# 📥 Instalace českého překladu SimCity 4

Detailní krok-za-krokem návod pro **macOS** a **Windows** uživatele Steam verze.

---

## 🛡️ Než začneš

- ✅ Ujisti se, že máš **SimCity 4 Deluxe Edition** ze Steamu (originální verze hry)
- ✅ Hra musí být **úplně zavřená** (i Steam launcher)
- ✅ **Doporučujeme zazálohovat originální `SimCityLocale.dat`** — kdybys chtěl zpět na angličtinu, hned ho vrátíš

---

## 🍎 macOS (Steam)

### Krok 1: Stáhni překlad

1. Otevři [stránku Releases](../../releases/latest)
2. Najdi sekci **Assets** a klikni na `SimCityLocale.dat`
3. Soubor se stáhne do `~/Downloads/`

> 💡 Velikost souboru je cca **1,1 MB**. Pokud máš 0 bytů, stahování neproběhlo.

### Krok 2: Otevři složku hry

V **Finderu** stiskni `⌘ Cmd + Shift + G` (Přejít do složky) a vlož cestu:

```
~/Library/Application Support/Steam/steamapps/common/SimCity 4 Deluxe/SimCity™4 Deluxe Edition.app/Contents/GameData/English/
```

### Krok 3: Zazálohuj originál

1. Najdi soubor `SimCityLocale.dat` ve složce
2. Klikni pravým tlačítkem → **Duplikovat**
3. Přejmenuj kopii na `SimCityLocale.dat.BACKUP`

### Krok 4: Nahraď překladem

1. Přetáhni stažený `SimCityLocale.dat` z `Downloads` do herní složky `English/`
2. Když Finder zeptá, potvrď **Nahradit** (Replace)

### Krok 5: Spusť hru

Spusť **SimCity 4** přes Steam. Hra bude česky! 🎉

---

## 🪟 Windows (Steam)

### Krok 1: Stáhni překlad

1. Otevři [stránku Releases](../../releases/latest)
2. V sekci **Assets** klikni na `SimCityLocale.dat`
3. Soubor se stáhne do tvé složky `Stažené soubory`

### Krok 2: Otevři složku hry

V **Průzkumníku Windows** přejdi do:

```
C:\Program Files (x86)\Steam\steamapps\common\SimCity 4 Deluxe\SimCity 4 Deluxe\Locale\English\
```

> 💡 **Cesta se může lišit**, pokud máš Steam knihovnu na jiném disku. V tom případě:
> 1. Otevři Steam → pravý klik na SimCity 4 Deluxe → **Spravovat** → **Procházet místní soubory**
> 2. Z otevřené složky pokračuj do `Locale\English\`

### Krok 3: Zazálohuj originál

1. Najdi `SimCityLocale.dat`
2. Klikni pravým tlačítkem → **Kopírovat**, pak **Vložit** v stejné složce
3. Přejmenuj kopii na `SimCityLocale.dat.BACKUP`

### Krok 4: Nahraď překladem

1. Přesuň stažený `SimCityLocale.dat` ze `Stažené soubory` do herní složky
2. Potvrď **Nahradit**

> ⚠️ Windows může chtít **administrátorská práva** pro zápis do `Program Files`. Klikni **Pokračovat**.

### Krok 5: Spusť hru

Spusť **SimCity 4** přes Steam. Hra bude česky! 🎉

---

## 🔄 Update z předchozí verze překladu

Pokud už máš nainstalovanou starší verzi překladu (např. `v1.0.0`) a chceš updatovat na novější (např. `v1.1.0`):

1. Stáhni novější `SimCityLocale.dat` z [Releases](../../releases/latest)
2. Přepiš ten současný stejným postupem jako při první instalaci (kroky 2–4 výše)
3. **Není potřeba znovu zálohovat** — tvůj `SimCityLocale.dat.BACKUP` z první instalace je pořád originální anglická verze

---

## ↩️ Návrat k anglické verzi

Pokud se chceš vrátit k originální angličtině, máš dvě možnosti:

### Možnost A: Z vlastní zálohy

1. Smaž český `SimCityLocale.dat`
2. Přejmenuj `SimCityLocale.dat.BACKUP` zpět na `SimCityLocale.dat`

### Možnost B: Přes Steam

1. Otevři Steam → pravý klik na **SimCity 4 Deluxe** → **Vlastnosti**
2. **Nainstalované soubory** → **Ověřit integritu herních souborů**
3. Steam stáhne originální anglickou verzi zpět

---

## 🆘 Řešení problémů

### „Po instalaci se hra nespustí"

Zkontroluj:

- Soubor je opravdu pojmenován **přesně** `SimCityLocale.dat` (ne `SimCityLocale (1).dat`, `SimCityLocale.dat.txt`, atd.)
- Soubor je ve **správné složce** `English/`
- Soubor **není 0 bytů** (stahování proběhlo úspěšně) — má mít cca **1,1 MB**

Pokud problém přetrvává:
- Ověř integritu herních souborů přes Steam (Možnost B výše) → tím se vrátíš k anglické verzi
- Pak zkus překlad znovu nainstalovat

### „Některé texty jsou stále anglicky"

To je v pořádku! Překlad pokrývá **88 %** textů. Zbývající anglické texty jsou:

- Tutoriál a kredity (technické omezení)
- Vlastní jména Simů, měst, značek (záměrně)
- Klávesové zkratky a herní měna

Detaily v [README.md](README.md#-co-není-přeloženo-a-proč).

### „Diakritika se zobrazuje divně" (`ř` jako `r`, `č` jako `c`, atd.)

To je **záměrné**. Hra interně konvertuje text na kódování Win-1252, které neumí české znaky `ř, č, ě, ů, ť, ď, ň`. Proto je v překladu použita zjednodušená diakritika. Toto je technické omezení hry samotné — nelze obejít bez modifikace herního enginu.

### „Vidím poškozený text / Krakozjably / kostičky"

Pravděpodobně máš **starou nebo neoriginální verzi** hry. Tento překlad je testovaný na:
- ✅ Steam macOS (Apple Silicon i Intel)
- ✅ Steam Windows (Windows 10 a 11)
- ❌ Necertifikované verze (GOG, retail CD, jiné distribuce) — můžou fungovat, ale netestováno

### Něco jiného?

Otevři [GitHub Issue](../../issues/new) nebo napiš na Discord [`@megi9073`](https://discord.com/users/453211849849176094) s popisem problému. Co pomůže:

- Tvůj operační systém (macOS / Windows + verze)
- Screenshot toho, co vidíš
- Co se stalo přesně před chybou (instalace? spuštění? načtení města?)
