# Historie verzí

Tento projekt sleduje [Sémantické verzování](https://semver.org/lang/cs/).

---

## [v1.0.0] — 2026-05-10

🎉 **První veřejné vydání**

### Přidáno

- Český překlad **5 219 z 5 962** textových položek (**88 %**)
- Detailní instalační návod pro **macOS** i **Windows** Steam ([INSTALLATION.md](INSTALLATION.md))
- README s vysvětlením omezení (HTML tutoriály, Win-1252 diakritika)
- MIT licence
- GitHub Issues + Discord kanál pro feedback
- Mechanismus updatů přes GitHub Releases

### Pokrytí překladu

- **99 %** zpráv a poradců (2 418 / 2 442)
- **91 %** popisů budov (927 / 1 020)
- **82 %** UI a tooltipů (823 / 1 007)
- **100 %** menu božího režimu (terén)
- **100 %** tipů, tipů zón a tutoriálových podnětů
- **100 %** audio nastavení
- **~98 %** statistik, rozpočtu a popisů objektů

### Záměrně nepřeloženo

- HTML tutoriály a kredity (technické omezení — vložené skripty se po překladu zlomily)
- Vlastní jména Simů, měst a značek
- Klávesové zkratky a herní měna (§)

### Známá omezení

- **Diakritika je zjednodušená** kvůli Win-1252 kódování hry (`ř → r`, `č → c`, `ě → e`, `ů → ú`, `ť → t`, `ď → d`, `ň → n`). Nelze obejít bez modifikace herního enginu.

### Vývoj

- 27 build iterací (v6 → v29) na cestě k finálnímu pokrytí
- Reverse-engineering DBPF formátu (Maxis Database Packed File)
- Vytvořeno ve spolupráci s [Claude AI](https://www.anthropic.com/claude) (Anthropic)
