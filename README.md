# 🇨🇿 SimCity 4 Deluxe — Český překlad

> Neoficiální český překlad hry **SimCity 4 Deluxe Edition** pro Steam (macOS i Windows).

![Verze](https://img.shields.io/badge/verze-v1.0.0-blue) ![Pokrytí](https://img.shields.io/badge/přeloženo-88%25-brightgreen) ![Platforma](https://img.shields.io/badge/Steam-macOS%20%7C%20Windows-lightgrey) ![Licence](https://img.shields.io/badge/licence-MIT-green)

---

## 📦 Co je přeloženo

| Skupina | Přeloženo | Celkem | % |
|---|---:|---:|---:|
| Zprávy a poradci | 2 418 | 2 442 | **99 %** |
| Popisy budov | 927 | 1 020 | **91 %** |
| UI a tooltipy | 823 | 1 007 | **82 %** |
| Objekty | 392 | 400 | 98 % |
| Statistiky | 274 | 279 | 98 % |
| Rozpočet | 144 | 147 | 98 % |
| Menu | 86 | 93 | 92 % |
| Boží terén | 58 | 58 | 100 % |
| Ostatní | 38 | 38 | 100 % |
| Tipy tutoriálů | 18 | 18 | 100 % |
| Boží katastrofy | 17 | 18 | 94 % |
| Tipy zón | 15 | 15 | 100 % |
| Audio | 8 | 8 | 100 % |
| Populace | 1 | 1 | 100 % |
| **CELKEM** | **5 219** | **5 962** | **88 %** |

> Celkem **88 %** textů hry. Zbývajících 12 % jsou záměrně nepřeložené položky (vlastní jména, klávesové zkratky, herní měna, značky) a několik technicky nepřekládatelných HTML obrazovek.

---

## 🚀 Rychlá instalace

### macOS (Steam)

1. Stáhni `SimCityLocale.dat` z [poslední Release stránky](../../releases/latest)
2. Zazálohuj originál a nahraď v:
   ```
   ~/Library/Application Support/Steam/steamapps/common/SimCity 4 Deluxe/SimCity™4 Deluxe Edition.app/Contents/GameData/English/
   ```
3. Spusť hru přes Steam 🎉

### Windows (Steam)

1. Stáhni `SimCityLocale.dat` z [poslední Release stránky](../../releases/latest)
2. Zazálohuj originál a nahraď v:
   ```
   Steam\steamapps\common\SimCity 4 Deluxe\SimCity 4 Deluxe\Locale\English\
   ```
3. Spusť hru přes Steam 🎉

📖 **Detailní krok-za-krokem návod:** [INSTALLATION.md](INSTALLATION.md)

---

## ⚠️ Co není přeloženo (a proč)

- **Herní tutoriál** — z technických důvodů. HTML formát s vloženými skripty se po překladu zlomil (zobrazoval prázdné okno), proto zůstal anglicky.
- **Závěrečné kredity** — stejný technický problém jako tutoriál.
- **Vlastní jména** Simů, měst a značek (Bob, Eva, Seattle, Berlín, SimCity, Maxis...) — záměrně, neměly by se překládat.
- **Klávesové zkratky** (W, A, S, D, OK, Esc) — zůstávají v originále kvůli kompatibilitě.
- **Herní měna** (§, §§, §§§) — interní symboly.
- **Diakritika je zjednodušená.** Hra interně konvertuje text na kódování Win-1252, které neumí české znaky `ř, č, ě, ů, ť, ď, ň`. Proto je v překladu použita zjednodušená diakritika (`ř → r`, `č → c`, `ě → e`, `ů → ú`). Toto je technické omezení hry, které nelze obejít.

---

## 🔄 Updaty

Překlad budu postupně zlepšovat na základě feedbacku. Nové verze vycházejí jako [GitHub Releases](../../releases).

**Aktuální verze:** `v1.0.0` (2026-05-10)

**Jak získat novější verzi:**
1. Stáhni nejnovější `SimCityLocale.dat` ze [stránky Releases](../../releases/latest)
2. Přepiš starý soubor v herní složce stejným postupem jako při první instalaci
3. Spusť hru

> 💡 **Tip:** Klikni na tlačítko **⭐ Watch** nahoře vpravo na GitHubu a dostaneš e-mail, když vyjde nová verze.

---

## 💬 Feedback a komunita

Našel jsi chybu, divně přeložený text, nebo máš návrh na zlepšení? Ozvi se!

- 💬 **Discord:** [`zen`](https://discord.com/users/453211849849176094) — pro rychlý chat a feedback
- 🐛 **GitHub Issues:** [Nahlásit chybu nebo návrh](../../issues) — pro strukturované hlášení (přiloží screenshot, popis kontextu)

---

## 📜 Licence

[MIT](LICENSE) © 2026 Zen

Můžeš překlad volně používat, upravovat a šířit. Originální hra © Maxis / Electronic Arts — překlad je neoficiální fanouškovský projekt, není sponzorován ani schválen Maxisem ani EA.

---

Překlad vznikl reverse-engineeringem datového formátu **DBPF** (Maxis Database Packed File) a byl vytvořen ve spolupráci s **[Claude AI](https://www.anthropic.com/claude)** od Anthropic. Projekt prošel 27 build iteracemi (v6 → v29) na cestě k 88% pokrytí.

---

⭐ **Pokud se ti překlad líbí, dej hvězdičku!** Pomůže to ostatním českým hráčům projekt najít.
