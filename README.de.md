# Rekey

**Nie wieder in der falschen Sprache tippen.**

Rekey ist eine kostenlose macOS-App für die Menüleiste. Sie bemerkt, wenn ein Wort im falschen
Tastaturlayout gelandet ist, schreibt es an Ort und Stelle neu — und wechselt dann das Layout
für Sie, sodass Sie einfach weitertippen. Rekey ist ein automatischer Tastaturlayout-Umschalter
für den Mac und eine native Alternative zu Punto Switcher und Caramba Switcher, entwickelt von
[Taras Trishchuk](https://trishchuk.com/) und veröffentlicht auf
[trishchuk.com/rekey](https://trishchuk.com/rekey/de/).

![Rekey korrigiert ein Wort, das im falschen Tastaturlayout getippt wurde](assets/rekey-demo.gif)

*Eine einzige durchgehende Tastenfolge, nichts gestellt. `ghbdsn`, im englischen Layout getippt,
wird zu `привіт`, und das Layout springt auf Ukrainisch; `Цщкдв`, im ukrainischen Layout
getippt, wird zu `World`, und das Layout springt zurück.*

## Download

### [⬇ Rekey für macOS herunterladen](https://trishchuk.com/rekey/download/Rekey.dmg)

macOS 13 Ventura oder neuer · ein Universal-Build für Apple Silicon und Intel · kostenlos

Dies ist eine öffentliche Beta. Sie aktualisiert sich selbst und sendet in Beta-Builds
standardmäßig anonyme Absturzberichte, damit Probleme auch wirklich behoben werden — beides
lässt sich in den Einstellungen abschalten.

## Was Rekey macht

- **Korrigiert das Wort, nicht Ihren Flow.** Wenn ein Wort in einer anderen Sprache weit besser
  abschneidet als in der, in der Sie es getippt haben, löscht Rekey es, wechselt das Layout und
  tippt es richtig neu. Kein Dialog, keine Rückfrage.
- **Ganze Passagen, nicht nur einzelne Wörter.** Ein kurzes Wort, das sich allein nicht beurteilen
  lässt, wird zurückgehalten, bis das nächste Wort die Frage klärt — so wird `f yt` zu `а не`,
  statt dass gar nichts passiert.
- **Rückgängig bringt es ihm bei.** Drücken Sie innerhalb von fünf Sekunden nach einer Korrektur
  ⌘Z, setzt Rekey das Wort auf seine Ignorierliste. Denselben Fehler beim selben Wort macht es
  kein zweites Mal.
- **Auch manuelles Umschalten.** Standardmäßig per doppeltem Shift — oder mit Control, Option,
  Command, ⌃Space, ⌘Space, ⌥⌘Space.
- **Hält sich raus.** Passwortfelder, Terminals und Code-Editoren sind standardmäßig
  ausgeschlossen, und Text, der wie eine URL, ein Pfad oder Code aussieht, wird übersprungen.

## Sprachen

34 Sprachen in lateinischer, kyrillischer, griechischer, hebräischer, arabischer, armenischer,
georgischer und koreanischer Schrift, darunter Ukrainisch, Englisch, Deutsch, Französisch,
Spanisch, Polnisch und Tschechisch. Die vollständige Liste steht unter Einstellungen ▸ Sprachen.

Die Erkennung ist keine Nachschlagetabelle: Jedes Wort wird anhand sprachspezifischer
Häufigkeiten von Buchstabenpaaren und -tripeln sowie eines Wörterbuchs bewertet — gewonnen aus
echten Korpusdaten statt aus einer Wortliste, die jemand von Hand abgetippt hat.

## Im Vergleich

| | **Rekey** | Caramba Switcher | Punto Switcher |
|---|---|---|---|
| Unterstützte Sprachen | **34** | EN + RU | EN + RU |
| Ihr Text verlässt nie Ihren Mac | ✓ | ✓ | ✕ |
| Korrektur ganzer Sätze | ✓ | ✕ | ✕ |
| Respektiert Passwortfelder | ✓ | ✓ | ✕ |
| Schließt Code-Editoren standardmäßig aus | ✓ | ✓ | ✕ |
| Sofort rückgängig (⌘Z) | ✓ | ✓ | ✕ |
| Natives Swift, kein Electron | ✓ | ✓ | ✕ |
| Für modernes macOS gebaut | ✓ | ✓ | ✕ |
| Preis | **Kostenlos** | $6.99/Jahr | Kostenlos |

Vergleich auf Basis öffentlich verfügbarer Informationen, Juni 2026.

## Punto-Switcher- und Caramba-Switcher-Alternative für Mac

Sie suchen eine **Punto-Switcher-Alternative für Mac**? Genau das ist Rekey — nur gebaut für
Menschen, die in mehr als zwei Sprachen tippen. Punto Switcher ist ein Windows-Tool von Yandex;
die alte Mac-Version wird nicht mehr gepflegt und läuft auf Apple Silicon nicht zuverlässig.
Caramba Switcher funktioniert auf modernem macOS, konzentriert sich aber auf Englisch und
Russisch und wird im Abo verkauft.

Ausführlicher auf der Website:

- [Punto Switcher für Mac — native macOS-Alternative Rekey](https://trishchuk.com/rekey/de/punto-switcher-fuer-mac/)
- [Die besten Punto-Switcher-Alternativen für Mac im Vergleich](https://trishchuk.com/rekey/de/punto-switcher-alternativen/)
- [Die besten Caramba-Switcher-Alternativen für Mac im Vergleich](https://trishchuk.com/rekey/de/caramba-switcher-alternativen/)
- Direktvergleiche (auf Englisch): [Rekey vs Caramba Switcher](https://trishchuk.com/rekey/compare/rekey-vs-caramba-switcher/) ·
  [Rekey vs Boomkey](https://trishchuk.com/rekey/compare/rekey-vs-boomkey/) ·
  [Rekey vs Keyboop](https://trishchuk.com/rekey/compare/rekey-vs-keyboop/) ·
  [Rekey vs MLSwitcher](https://trishchuk.com/rekey/compare/rekey-vs-mlswitcher/) ·
  [Rekey vs Flipio](https://trishchuk.com/rekey/compare/rekey-vs-flipio/)
- Umstieg von Windows (auf Englisch): [Mahou-Alternative](https://trishchuk.com/rekey/alternatives/mahou/) ·
  [EveryLang-Alternative](https://trishchuk.com/rekey/alternatives/everylang/)

## FAQ

**Gibt es Punto Switcher für Mac?**
Keinen aktuellen. Der alte Mac-Build von Punto Switcher wird nicht mehr gepflegt und läuft auf
Apple Silicon nicht zuverlässig. Rekey erledigt dieselbe Aufgabe — Text korrigieren, der im
falschen Layout getippt wurde, und das Layout wechseln — als native Swift-App für aktuelles macOS.

**Ist Rekey kostenlos?**
Ja. Es ist kostenlos, ohne Konto und ohne Abo. Derzeit ist es eine öffentliche Beta.

**Läuft es auf Apple Silicon?**
Ja. Ein Universal-Build läuft auf Macs mit Apple Silicon und Intel ab macOS 13 Ventura.

**Welche Sprachen werden unterstützt?**
34 Sprachen, darunter Ukrainisch, Englisch, Deutsch, Französisch, Spanisch, Polnisch,
Tschechisch, Griechisch, Hebräisch und Arabisch. Rekey funktioniert mit jedem Paar und jeder
Kombination installierter Layouts, nicht nur mit Englisch und Russisch.

**Sendet es meine Eingaben irgendwohin?**
Nein. Jedes Wort wird auf Ihrem Mac analysiert. Unter [Datenschutz](#datenschutz) steht die kurze
Liste dessen, was den Rechner tatsächlich verlässt.

**Kann ich das Layout weiterhin von Hand wechseln?**
Ja. Standardmäßig per doppeltem Shift, oder wählen Sie stattdessen Control, Option, Command,
⌃Space, ⌘Space oder ⌥⌘Space.

## Datenschutz

Ihre Tastenanschläge werden auf Ihrem Mac analysiert und nie übertragen. Rekey hat kein Konto,
keine Synchronisierung und keine serverseitige Textverarbeitung.

Vier Dinge können den Rechner verlassen, sonst nichts:

1. **Die Update-Prüfung** — die App fragt bei der Website nach, ob es eine neuere Version gibt.
2. **Ein einziges Installationssignal** — eine einzelne Nachricht, wenn Sie den
   Willkommensbildschirm abschließen. Sie hält fest, welche Berechtigungen Sie erteilt haben und
   ob Sie die Einrichtung beendet haben. Sie enthält keinerlei Kennung, nicht einmal eine
   zufällige, sodass sich Installationen weder unterscheiden noch doppelt zählen lassen.
3. **Absturzberichte** — in Beta-Builds standardmäßig aktiv und in den Einstellungen abschaltbar.
4. **Ihre E-Mail-Adresse** — nur wenn Sie bei der Einrichtung eine eingeben und ein Häkchen
   setzen.

Vollständiger Text: [Datenschutzerklärung (auf Englisch)](https://trishchuk.com/rekey/privacy.html).

## Feedback

Beta-Feedback gehört in die [Issues](../../issues) — Fehlerberichte, falsche Korrekturen, eine
Sprache, die schlecht erkannt wird. Hat Rekey ein Wort verunstaltet, das es hätte in Ruhe lassen
sollen, ist das die nützlichste Meldung überhaupt: Nennen Sie das Wort, die beiden Layouts und
die App, in der Sie getippt haben.

[So melden Sie ein Problem](https://trishchuk.com/rekey/de/feedback/) erklärt, was dazugehört.
Neue Issues beginnen mit einer von drei Vorlagen: **Bug report** (Fehlerbericht), **Language not
detected well** (Sprache schlecht erkannt) und **Idea or feedback** (Idee oder Feedback).
Sicherheitsprobleme melden Sie stattdessen vertraulich — siehe [SECURITY.md](SECURITY.md).

## Über dieses Repository

Rekey ist derzeit nicht Open Source. Dieses Repository dient den Releases und der
Fehlerverfolgung; der Quellcode liegt woanders. Die App ist kostenlos und wird als signierter und
notarisierter Build direkt über [trishchuk.com/rekey](https://trishchuk.com/rekey/de/) verteilt.

Es gibt andere Apps mit dem Namen Rekey. Diese hier stammt von Taras Trishchuk und wird nur auf
[trishchuk.com/rekey](https://trishchuk.com/rekey/de/) und in diesem Repository veröffentlicht.

---

[Website](https://trishchuk.com/rekey/de/) · [Datenschutz (auf Englisch)](https://trishchuk.com/rekey/privacy.html)

[English](README.md) · [Українська](README.uk.md) · [Deutsch](README.de.md) · [Polski](README.pl.md) · [Español](README.es.md) · [Français](README.fr.md) · [Nederlands](README.nl.md) · [Ελληνικά](README.el.md) · [Türkçe](README.tr.md) · [עברית](README.he.md) · [العربية](README.ar.md)
