# Rekey

**Już nigdy nie pisz w złym języku.**

Rekey to darmowa aplikacja na pasek menu macOS, która zauważa, że słowo wyszło w złym układzie
klawiatury, i przepisuje je na miejscu — a potem sama przełącza układ, więc po prostu piszesz
dalej. To automatyczny przełącznik układu klawiatury dla Maca i natywna alternatywa dla Punto
Switcher i Caramba Switcher. Autor: [Taras Trishchuk](https://trishchuk.com/), strona aplikacji:
[trishchuk.com/rekey/pl](https://trishchuk.com/rekey/pl/).

![Rekey poprawia słowo wpisane w złym układzie klawiatury](assets/rekey-demo.gif)

*Jedna nieprzerwana sekwencja klawiszy, nic nie jest inscenizowane. `ghbdsn` wpisane w układzie
angielskim zmienia się w `привіт`, a układ przełącza się na ukraiński; `Цщкдв` wpisane w układzie
ukraińskim zmienia się w `World` i układ wraca z powrotem.*

## Pobierz

### [⬇ Pobierz Rekey na macOS](https://trishchuk.com/rekey/download/Rekey.dmg)

macOS 13 Ventura lub nowszy · jedna uniwersalna wersja dla Apple Silicon i Intel · za darmo

To publiczna beta. Aktualizuje się sama, a w wersjach beta domyślnie wysyła anonimowe raporty o
awariach, żeby problemy faktycznie były naprawiane — jedno i drugie można wyłączyć w Ustawieniach.

## Co robi

- **Poprawia słowo, nie wybija z rytmu.** Gdy słowo wypada znacznie lepiej w innym języku niż w
  tym, w którym je wpisano, Rekey kasuje je, przełącza układ i wpisuje je poprawnie.
  Bez okien dialogowych, bez potwierdzeń.
- **Całe frazy, nie tylko pojedyncze słowa.** Krótkie słowo, którego nie da się ocenić samego w
  sobie, czeka, aż kolejne słowo rozstrzygnie sprawę, więc `f yt` zmienia się w `а не`, zamiast zostać
  bez zmian.
- **Cofnięcie go uczy.** Naciśnij ⌘Z w ciągu pięciu sekund od poprawki, a Rekey doda to słowo do
  listy ignorowanych. Nie popełni dwa razy tego samego błędu na tym samym słowie.
- **Ręczne przełączanie też jest.** Domyślnie dwukrotne naciśnięcie Shift — albo Control, Option,
  Command, ⌃Space, ⌘Space, ⌥⌘Space.
- **Nie wchodzi w drogę.** Pola haseł, terminale i edytory kodu są domyślnie wyłączone, a tekst,
  który wygląda na adres URL, ścieżkę lub kod, jest pomijany.

## Języki

34 języki zapisywane alfabetem łacińskim, cyrylicą, pismem greckim, hebrajskim, arabskim,
ormiańskim, gruzińskim i koreańskim, w tym ukraiński, angielski, niemiecki, francuski, hiszpański,
polski i czeski. Pełna lista jest w Ustawieniach ▸ Języki.

Wykrywanie to nie tabela odpowiedników: każde słowo jest oceniane na podstawie częstości par i
trójek liter w danym języku oraz słownika, zbudowanych z prawdziwych danych korpusowych, a nie z
listy słów, którą ktoś spisał ręcznie.

## Jak wypada Rekey

| | **Rekey** | Caramba Switcher | Punto Switcher |
|---|---|---|---|
| Obsługiwane języki | **34** | EN + RU | EN + RU |
| Wpisywany tekst zostaje na Macu | ✓ | ✓ | ✕ |
| Korekta całych zdań | ✓ | ✕ | ✕ |
| Respektuje pola haseł | ✓ | ✓ | ✕ |
| Domyślnie wyklucza edytory kodu | ✓ | ✓ | ✕ |
| Natychmiastowe cofnięcie (⌘Z) | ✓ | ✓ | ✕ |
| Natywny Swift, bez Electrona | ✓ | ✓ | ✕ |
| Stworzony dla nowoczesnego macOS | ✓ | ✓ | ✕ |
| Cena | **Za darmo** | $6.99/rok | Za darmo |

Porównanie na podstawie publicznie dostępnych informacji, czerwiec 2026.

## Alternatywa dla Punto Switcher i Caramba Switcher na Maca

Szukasz **alternatywy dla Punto Switcher na Maca**? Właśnie nią jest Rekey — z tą różnicą, że
powstał dla osób, które piszą w więcej niż dwóch językach. Punto Switcher to narzędzie Windows od
Yandex; jego stara wersja na Maca nie jest już utrzymywana i nie działa niezawodnie na Apple
Silicon. Caramba Switcher działa na nowoczesnym macOS, ale skupia się na angielskim i rosyjskim i
jest sprzedawany w subskrypcji.

Dłuższe omówienia na stronie:

- [Punto Switcher na Maca — natywny zamiennik Rekey](https://trishchuk.com/rekey/pl/punto-switcher-na-maca/)
- [Najlepsze alternatywy dla Punto Switcher na Maca — porównanie](https://trishchuk.com/rekey/pl/alternatywy-punto-switcher/)
- [Najlepsze alternatywy dla Caramba Switcher na Maca — porównanie](https://trishchuk.com/rekey/pl/alternatywy-caramba-switcher/)
- Bezpośrednie porównania (po angielsku): [Rekey vs Caramba Switcher](https://trishchuk.com/rekey/compare/rekey-vs-caramba-switcher/) ·
  [Rekey vs Boomkey](https://trishchuk.com/rekey/compare/rekey-vs-boomkey/) ·
  [Rekey vs Keyboop](https://trishchuk.com/rekey/compare/rekey-vs-keyboop/) ·
  [Rekey vs MLSwitcher](https://trishchuk.com/rekey/compare/rekey-vs-mlswitcher/) ·
  [Rekey vs Flipio](https://trishchuk.com/rekey/compare/rekey-vs-flipio/)
- Dla przechodzących z Windows (po angielsku): [Alternatywa dla Mahou](https://trishchuk.com/rekey/alternatives/mahou/) ·
  [Alternatywa dla EveryLang](https://trishchuk.com/rekey/alternatives/everylang/)

## Najczęstsze pytania

**Czy jest Punto Switcher na Maca?**
Nie w aktualnej wersji. Stara wersja Punto Switcher na Maca nie jest już utrzymywana i nie działa
niezawodnie na Apple Silicon. Rekey robi to samo — poprawia tekst wpisany w złym układzie i
przełącza układ — jako natywna aplikacja Swift dla obecnego macOS.

**Czy Rekey jest darmowy?**
Tak. Jest darmowy, bez konta i bez subskrypcji. Obecnie to publiczna beta.

**Czy działa na Apple Silicon?**
Tak. Jedna uniwersalna wersja działa na Macach z Apple Silicon i Intel z macOS 13 Ventura lub
nowszym.

**Jakie języki obsługuje?**
34 języki, w tym ukraiński, angielski, niemiecki, francuski, hiszpański, polski, czeski, grecki,
hebrajski i arabski. Działa z dowolną parą lub zestawem zainstalowanych układów, nie tylko z
angielskim i rosyjskim.

**Czy wysyła gdzieś to, co piszę?**
Nie. Każde słowo jest analizowane na Twoim Macu. Krótka lista tego, co jednak opuszcza komputer,
jest w sekcji [Prywatność](#prywatność).

**Czy nadal mogę przełączać układ ręcznie?**
Tak. Domyślnie dwukrotne naciśnięcie Shift albo, do wyboru, Control, Option, Command, ⌃Space,
⌘Space lub ⌥⌘Space.

## Prywatność

Naciśnięcia klawiszy są analizowane na Twoim Macu i nigdzie nie są przesyłane. Rekey nie ma
konta, synchronizacji ani przetwarzania tekstu po stronie serwera.

Komputer mogą opuścić cztery rzeczy i nic poza nimi:

1. **Sprawdzanie aktualizacji** — aplikacja pyta stronę, czy jest dostępna nowsza wersja.
2. **Jeden sygnał instalacji** — pojedyncza wiadomość po zakończeniu ekranu powitalnego, która
   zapisuje, jakie uprawnienia nadano i czy konfiguracja została dokończona. Nie zawiera żadnego
   identyfikatora, nawet losowego, więc instalacji nie da się od siebie odróżnić ani policzyć
   dwa razy.
3. **Raporty o awariach** — w wersjach beta, domyślnie włączone i do wyłączenia w Ustawieniach.
4. **Twój adres e-mail** — tylko jeśli wpiszesz go podczas konfiguracji i zaznaczysz pole.

Pełny tekst: [Polityka prywatności](https://trishchuk.com/rekey/privacy.html) (po angielsku).

## Opinie

Opinie o becie zgłaszaj w [Issues](../../issues) — błędy, fałszywe poprawki, język, który
wypada słabo. Jeśli Rekey zepsuł słowo, które powinien był zostawić w spokoju, to najcenniejsza
rzecz, jaką możesz zgłosić: podaj to słowo, oba układy i aplikację, w której to się stało.

[Jak zgłosić problem](https://trishchuk.com/rekey/pl/feedback/) wyjaśnia, co warto podać. Nowe
zgłoszenia zaczynają się od jednego z trzech szablonów: **Bug report** (zgłoszenie błędu),
**Language not detected well** (język źle wykrywany) i **Idea or feedback** (pomysł lub opinia).
Problemy z bezpieczeństwem zgłaszaj prywatnie — zobacz [SECURITY.md](SECURITY.md).

## O tym repozytorium

Rekey nie jest dziś open source. To repozytorium służy do wydań i śledzenia zgłoszeń; kod
źródłowy jest gdzie indziej. Aplikacja jest darmowa i dystrybuowana jako podpisana i
notaryzowana wersja bezpośrednio z [trishchuk.com/rekey/pl](https://trishchuk.com/rekey/pl/).

Inne aplikacje też noszą nazwę Rekey. Tę tworzy Taras Trishchuk i jest publikowana wyłącznie na
[trishchuk.com/rekey/pl](https://trishchuk.com/rekey/pl/) i w tym repozytorium.

---

[Strona](https://trishchuk.com/rekey/pl/) · [Prywatność (po angielsku)](https://trishchuk.com/rekey/privacy.html)

[English](README.md) · [Українська](README.uk.md) · [Deutsch](README.de.md) · [Polski](README.pl.md) · [Español](README.es.md) · [Français](README.fr.md) · [Nederlands](README.nl.md) · [Ελληνικά](README.el.md) · [Türkçe](README.tr.md) · [עברית](README.he.md) · [العربية](README.ar.md)
