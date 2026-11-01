# Rekey

**Typ nooit meer in de verkeerde taal.**

Rekey is een gratis macOS-app voor de menubalk die merkt wanneer een woord in de verkeerde
toetsenbordindeling is beland en het ter plekke herschrijft — en daarna de indeling voor je
wisselt, zodat je gewoon doortypt. Het is een automatische wisselaar van toetsenbordindeling
voor Mac en een native alternatief voor Punto Switcher en Caramba Switcher, gemaakt door
[Taras Trishchuk](https://trishchuk.com/) en gepubliceerd op
[trishchuk.com/rekey/nl](https://trishchuk.com/rekey/nl/).

![Rekey corrigeert een woord dat in de verkeerde toetsenbordindeling is getypt](assets/rekey-demo.gif)

*Eén ononderbroken reeks toetsaanslagen, niets in scène gezet. `ghbdsn`, getypt op de Engelse
indeling, wordt `привіт` en de indeling springt naar Oekraïens; `Цщкдв`, getypt op de Oekraïense
indeling, wordt `World` en de indeling springt terug.*

## Downloaden

### [⬇ Download Rekey voor macOS](https://trishchuk.com/rekey/download/Rekey.dmg)

macOS 13 Ventura of nieuwer · één universele build voor Apple Silicon en Intel · gratis

Dit is een openbare bèta. Hij werkt zichzelf bij en stuurt op bètabuilds standaard anonieme
crashrapporten, zodat problemen ook echt worden opgelost — beide zijn uit te schakelen in
Instellingen.

## Wat het doet

- **Corrigeert het woord, niet je flow.** Als een woord in een andere taal veel hoger scoort dan
  in de taal waarin je het typte, wist Rekey het, wisselt de indeling en typt het correct
  opnieuw. Geen dialoogvenster, geen bevestiging.
- **Hele reeksen, niet alleen losse woorden.** Een kort woord dat op zichzelf niet te beoordelen
  is, wordt vastgehouden tot het volgende woord de doorslag geeft — zo wordt `f yt` netjes
  `а не` in plaats van dat er niets gebeurt.
- **Ongedaan maken leert het iets.** Druk binnen vijf seconden na een correctie op ⌘Z en Rekey
  zet dat woord op zijn negeerlijst. Het maakt bij hetzelfde woord niet twee keer dezelfde fout.
- **Ook handmatig wisselen.** Standaard door twee keer op Shift te tikken — of met Control,
  Option, Command, ⌃Space, ⌘Space, ⌥⌘Space.
- **Blijft uit de weg.** Wachtwoordvelden, terminals en code-editors zijn standaard uitgesloten,
  en tekst die eruitziet als een URL, een pad of code wordt overgeslagen.

## Talen

34 talen in het Latijnse, Cyrillische, Griekse, Hebreeuwse, Arabische, Armeense, Georgische en
Koreaanse schrift, waaronder Oekraïens, Engels, Duits, Frans, Spaans, Pools en Tsjechisch. De
volledige lijst staat in Settings ▸ Languages (de app heeft nog geen Nederlandse interface).

Herkenning is geen opzoektabel: elk woord wordt beoordeeld op de frequenties van letterparen en
lettertripels per taal plus een woordenboek, opgebouwd uit echte corpusdata in plaats van uit een
woordenlijst die iemand met de hand heeft ingetypt.

## Vergelijking

| | **Rekey** | Caramba Switcher | Punto Switcher |
|---|---|---|---|
| Ondersteunde talen | **34** | EN + RU | EN + RU |
| Je tekst verlaat nooit je Mac | ✓ | ✓ | ✕ |
| Correctie van hele zinnen | ✓ | ✕ | ✕ |
| Respecteert wachtwoordvelden | ✓ | ✓ | ✕ |
| Sluit code-editors standaard uit | ✓ | ✓ | ✕ |
| Direct ongedaan maken (⌘Z) | ✓ | ✓ | ✕ |
| Native Swift, geen Electron | ✓ | ✓ | ✕ |
| Gemaakt voor modern macOS | ✓ | ✓ | ✕ |
| Prijs | **Gratis** | $6.99/jaar | Gratis |

Vergelijking op basis van openbaar beschikbare informatie, juni 2026.

## Punto Switcher- en Caramba Switcher-alternatief voor Mac

Op zoek naar een **Punto Switcher-alternatief voor Mac**? Dat is precies wat dit is — alleen
gemaakt voor mensen die in meer dan twee talen typen. Punto Switcher is een Windows-tool van
Yandex; de oude Mac-versie wordt niet meer onderhouden en draait niet betrouwbaar op Apple
Silicon. Caramba Switcher werkt op modern macOS, maar richt zich op Engels en Russisch en wordt
als abonnement verkocht.

Uitgebreider op de website:

- [Punto Switcher voor Mac — het native macOS-alternatief (Rekey)](https://trishchuk.com/rekey/nl/punto-switcher-voor-mac/)
- [De beste Punto Switcher-alternatieven voor Mac, vergeleken](https://trishchuk.com/rekey/nl/punto-switcher-alternatieven/)
- [De beste Caramba Switcher-alternatieven voor Mac, vergeleken](https://trishchuk.com/rekey/nl/caramba-switcher-alternatieven/)
- Eén op één (in het Engels): [Rekey vs Caramba Switcher](https://trishchuk.com/rekey/compare/rekey-vs-caramba-switcher/) ·
  [Rekey vs Boomkey](https://trishchuk.com/rekey/compare/rekey-vs-boomkey/) ·
  [Rekey vs Keyboop](https://trishchuk.com/rekey/compare/rekey-vs-keyboop/) ·
  [Rekey vs MLSwitcher](https://trishchuk.com/rekey/compare/rekey-vs-mlswitcher/) ·
  [Rekey vs Flipio](https://trishchuk.com/rekey/compare/rekey-vs-flipio/)
- Overstappen van Windows (in het Engels): [alternatief voor Mahou](https://trishchuk.com/rekey/alternatives/mahou/) ·
  [alternatief voor EveryLang](https://trishchuk.com/rekey/alternatives/everylang/)

## Veelgestelde vragen

**Is er een Punto Switcher voor Mac?**
Geen actuele. De oude Mac-build van Punto Switcher wordt niet meer onderhouden en draait niet
betrouwbaar op Apple Silicon. Rekey doet hetzelfde werk — tekst corrigeren die in de verkeerde
indeling is getypt en de indeling wisselen — als native Swift-app voor het huidige macOS.

**Is Rekey gratis?**
Ja. Het is gratis, zonder account en zonder abonnement. Op dit moment is het een openbare bèta.

**Werkt het op Apple Silicon?**
Ja. Eén universele build draait op Macs met Apple Silicon en Intel met macOS 13 Ventura of
nieuwer.

**Welke talen ondersteunt het?**
34 talen, waaronder Oekraïens, Engels, Duits, Frans, Spaans, Pools, Tsjechisch, Grieks,
Hebreeuws en Arabisch. Het werkt met elk paar of elke combinatie van indelingen die je hebt
geïnstalleerd, niet alleen met Engels en Russisch.

**Stuurt het wat ik typ ergens naartoe?**
Nee. Elk woord wordt op je Mac geanalyseerd. Zie [Privacy](#privacy) voor het korte lijstje van
wat de machine wél verlaat.

**Kan ik nog steeds met de hand van indeling wisselen?**
Ja. Standaard door twee keer op Shift te tikken, of kies in plaats daarvan Control, Option,
Command, ⌃Space, ⌘Space of ⌥⌘Space.

## Privacy

Je toetsaanslagen worden op je Mac geanalyseerd en nooit verzonden. Rekey heeft geen account,
geen synchronisatie en geen tekstverwerking op een server.

Vier dingen kunnen de machine verlaten, en verder niets:

1. **De updatecontrole** — de app vraagt de website of er een nieuwere versie is.
2. **Eén installatiesignaal** — één bericht wanneer je het welkomstvenster afrondt, met welke
   toestemmingen je hebt gegeven en of je de configuratie hebt voltooid. Het bevat geen enkele
   identificatie, zelfs geen willekeurige, dus installaties kunnen niet van elkaar worden
   onderscheiden of dubbel worden geteld.
3. **Crashrapporten** — op bètabuilds standaard aan en uit te schakelen in Instellingen.
4. **Je e-mailadres** — alleen als je er tijdens de configuratie een invult en een vakje
   aanvinkt.

Volledige tekst: [Privacybeleid (in het Engels)](https://trishchuk.com/rekey/privacy.html).

## Feedback

Feedback op de bèta hoort in [Issues](../../issues) — bugmeldingen, onterechte correcties, een
taal die slecht scoort. Heeft Rekey een woord verminkt dat het met rust had moeten laten, dan is
dat het allernuttigste wat je kunt melden: vermeld het woord, de twee indelingen en de app waarin
je typte.

[Zo meld je een probleem](https://trishchuk.com/rekey/nl/feedback/) legt uit wat je moet
meesturen. Nieuwe issues beginnen vanuit een van drie sjablonen: **Bug report** (bugmelding),
**Language not detected well** (taal slecht herkend) en **Idea or feedback** (idee of feedback).
Beveiligingsproblemen meld je in plaats daarvan via een privémelding — zie
[SECURITY.md](SECURITY.md).

## Over deze repository

Rekey is op dit moment geen open source. Deze repository bestaat voor releases en het bijhouden
van issues; de broncode staat elders. De app is gratis en wordt als ondertekende en
genotariseerde build rechtstreeks verspreid via
[trishchuk.com/rekey/nl](https://trishchuk.com/rekey/nl/).

Er zijn andere apps met de naam Rekey. Deze wordt gemaakt door Taras Trishchuk en wordt alleen
gepubliceerd op [trishchuk.com/rekey/nl](https://trishchuk.com/rekey/nl/) en in deze repository.

---

[Website](https://trishchuk.com/rekey/nl/) · [Privacy (in het Engels)](https://trishchuk.com/rekey/privacy.html)

[English](README.md) · [Українська](README.uk.md) · [Deutsch](README.de.md) · [Polski](README.pl.md) · [Español](README.es.md) · [Français](README.fr.md) · [Nederlands](README.nl.md) · [Ελληνικά](README.el.md) · [Türkçe](README.tr.md) · [עברית](README.he.md) · [العربية](README.ar.md)
