# Rekey

**Ne tapez plus jamais dans la mauvaise langue.**

Rekey est une app gratuite pour la barre des menus de macOS qui remarque quand un mot est sorti
dans la mauvaise disposition de clavier et le réécrit sur place — puis change la disposition
pour vous, pour que vous continuiez simplement à taper. C’est un commutateur automatique de
disposition de clavier pour Mac et une alternative native à Punto Switcher et Caramba Switcher,
créée par [Taras Trishchuk](https://trishchuk.com/) et publiée sur
[trishchuk.com/rekey/fr](https://trishchuk.com/rekey/fr/).

![Rekey corrige un mot tapé dans la mauvaise disposition de clavier](assets/rekey-demo.gif)

*Une seule séquence de touches ininterrompue, rien de mis en scène. `ghbdsn` tapé avec la
disposition anglaise devient `привіт` et la disposition bascule en ukrainien ; `Цщкдв` tapé avec
la disposition ukrainienne devient `World` et la disposition rebascule.*

## Téléchargement

### [⬇ Télécharger Rekey pour macOS](https://trishchuk.com/rekey/download/Rekey.dmg)

macOS 13 Ventura ou version ultérieure · un seul build universel pour Apple Silicon et Intel ·
gratuit

Ceci est une bêta publique. Elle se met à jour toute seule et, sur les builds bêta, envoie par
défaut des rapports de plantage anonymes pour que les problèmes soient vraiment corrigés — les
deux se désactivent dans les Réglages.

## Ce que fait Rekey

- **Corrige le mot, pas votre élan.** Quand un mot obtient un score bien plus élevé dans une
  autre langue que dans celle où vous l’avez tapé, Rekey l’efface, change la disposition et le
  retape correctement. Pas de boîte de dialogue, pas de confirmation.
- **Des passages entiers, pas seulement des mots isolés.** Un mot court qu’on ne peut pas juger
  seul est mis en attente jusqu’à ce que le mot suivant tranche la question : ainsi `f yt`
  devient `а не` au lieu de rester sans correction.
- **Annuler lui apprend.** Appuyez sur ⌘Z dans les cinq secondes qui suivent une correction et
  Rekey ajoute ce mot à sa liste d’exclusions. Il ne refait pas deux fois la même erreur sur le
  même mot.
- **La bascule manuelle aussi.** Double appui sur Shift par défaut — ou Control, Option, Command,
  ⌃Space, ⌘Space, ⌥⌘Space.
- **Reste à sa place.** Les champs de mot de passe, les terminaux et les éditeurs de code sont
  exclus par défaut, et Rekey ignore le texte qui ressemble à une URL, un chemin ou du code.

## Langues

34 langues réparties sur les écritures latine, cyrillique, grecque, hébraïque, arabe,
arménienne, géorgienne et coréenne, dont l’ukrainien, l’anglais, l’allemand, le français,
l’espagnol, le polonais et le tchèque. La liste complète se trouve dans Réglages ▸ Langues.

La détection n’est pas une table de correspondance : chaque mot est évalué à partir des
fréquences de paires et de triplets de lettres propres à chaque langue, plus un dictionnaire,
construits à partir de vrais corpus plutôt que d’une liste de mots saisie à la main.

## Comparaison

| | **Rekey** | Caramba Switcher | Punto Switcher |
|---|---|---|---|
| Langues prises en charge | **34** | EN + RU | EN + RU |
| Votre texte ne quitte jamais votre Mac | ✓ | ✓ | ✕ |
| Correction de phrases entières | ✓ | ✕ | ✕ |
| Respecte les champs de mot de passe | ✓ | ✓ | ✕ |
| Exclut les éditeurs de code par défaut | ✓ | ✓ | ✕ |
| Annulation instantanée (⌘Z) | ✓ | ✓ | ✕ |
| Swift natif, sans Electron | ✓ | ✓ | ✕ |
| Conçu pour le macOS moderne | ✓ | ✓ | ✕ |
| Prix | **Gratuit** | $6.99/an | Gratuit |

Comparaison basée sur des informations publiques, juin 2026.

## Alternative à Punto Switcher et Caramba Switcher pour Mac

Vous cherchez une **alternative à Punto Switcher pour Mac** ? C’est exactement ce qu’est Rekey —
sauf qu’il a été conçu pour les personnes qui tapent dans plus de deux langues. Punto Switcher
est un outil Windows de Yandex ; son ancienne version Mac n’est plus maintenue et ne fonctionne
pas de manière fiable sur Apple Silicon. Caramba Switcher fonctionne sur le macOS moderne, mais
se concentre sur l’anglais et le russe et est vendu par abonnement.

Pour aller plus loin, sur le site :

- [Punto Switcher pour Mac — alternative native avec Rekey](https://trishchuk.com/rekey/fr/punto-switcher-pour-mac/)
- [Les meilleures alternatives à Punto Switcher pour Mac, comparées](https://trishchuk.com/rekey/fr/alternatives-a-punto-switcher/)
- [Les meilleures alternatives à Caramba Switcher pour Mac, comparées](https://trishchuk.com/rekey/fr/alternatives-a-caramba-switcher/)
- Face à face (en anglais) : [Rekey vs Caramba Switcher](https://trishchuk.com/rekey/compare/rekey-vs-caramba-switcher/) ·
  [Rekey vs Boomkey](https://trishchuk.com/rekey/compare/rekey-vs-boomkey/) ·
  [Rekey vs Keyboop](https://trishchuk.com/rekey/compare/rekey-vs-keyboop/) ·
  [Rekey vs MLSwitcher](https://trishchuk.com/rekey/compare/rekey-vs-mlswitcher/) ·
  [Rekey vs Flipio](https://trishchuk.com/rekey/compare/rekey-vs-flipio/)
- Si vous venez de Windows (en anglais) : [alternative à Mahou](https://trishchuk.com/rekey/alternatives/mahou/) ·
  [alternative à EveryLang](https://trishchuk.com/rekey/alternatives/everylang/)

## FAQ

**Existe-t-il un Punto Switcher pour Mac ?**
Pas de version actuelle. L’ancien build Mac de Punto Switcher n’est plus maintenu et ne
fonctionne pas de manière fiable sur Apple Silicon. Rekey fait le même travail — corriger le
texte tapé dans la mauvaise disposition et changer de disposition — sous la forme d’une app
Swift native pour le macOS actuel.

**Rekey est-il gratuit ?**
Oui. Il est gratuit, sans compte ni abonnement. C’est actuellement une bêta publique.

**Fonctionne-t-il sur Apple Silicon ?**
Oui. Un seul build universel tourne sur les Mac Apple Silicon et Intel sous macOS 13 Ventura ou
version ultérieure.

**Quelles langues prend-il en charge ?**
34 langues, dont l’ukrainien, l’anglais, l’allemand, le français, l’espagnol, le polonais, le
tchèque, le grec, l’hébreu et l’arabe. Il fonctionne avec n’importe quelle paire ou combinaison
de dispositions installées, pas seulement l’anglais et le russe.

**Envoie-t-il ce que je tape quelque part ?**
Non. Chaque mot est analysé sur votre Mac. Voir [Confidentialité](#confidentialité) pour la
courte liste de ce qui quitte effectivement la machine.

**Puis-je encore changer de disposition à la main ?**
Oui. Double appui sur Shift par défaut, ou choisissez plutôt Control, Option, Command, ⌃Space,
⌘Space ou ⌥⌘Space.

## Confidentialité

Vos frappes sont analysées sur votre Mac et ne sont jamais transmises. Rekey n’a ni compte, ni
synchronisation, ni traitement du texte côté serveur.

Quatre choses peuvent quitter la machine, et rien d’autre :

1. **La vérification des mises à jour** — l’app demande au site web si une version plus récente
   existe.
2. **Un unique signal d’installation** — un seul message lorsque vous terminez l’écran de
   bienvenue, qui indique les autorisations que vous avez accordées et si vous avez terminé la
   configuration. Il ne contient aucun identifiant d’aucune sorte, pas même aléatoire : les
   installations ne peuvent donc ni être distinguées ni comptées deux fois.
3. **Les rapports de plantage** — sur les builds bêta, activés par défaut et désactivables dans
   les Réglages.
4. **Votre adresse e-mail** — uniquement si vous en saisissez une pendant la configuration et
   cochez une case.

Texte complet : [Politique de confidentialité (en anglais)](https://trishchuk.com/rekey/privacy.html).

## Retours

Les retours sur la bêta vont dans les [Issues](../../issues) — rapports de bug, corrections
erronées, une langue mal reconnue. Si Rekey a abîmé un mot qu’il aurait dû laisser tranquille,
c’est le signalement le plus utile qui soit : indiquez le mot, les deux dispositions et l’app
dans laquelle vous tapiez.

[Comment signaler un problème](https://trishchuk.com/rekey/fr/feedback/) explique quoi inclure.
Les nouvelles issues partent de l’un des trois modèles : **Bug report** (rapport de bug),
**Language not detected well** (langue mal détectée) et **Idea or feedback** (idée ou avis). Les
problèmes de sécurité passent plutôt par un signalement privé — voir [SECURITY.md](SECURITY.md).

## À propos de ce dépôt

Rekey n’est pas open source aujourd’hui. Ce dépôt sert aux versions publiées et au suivi des
issues ; le code source se trouve ailleurs. L’app est gratuite, distribuée sous forme de build
signé et notarié directement depuis [trishchuk.com/rekey/fr](https://trishchuk.com/rekey/fr/).

D’autres apps portent le nom Rekey. Celle-ci est créée par Taras Trishchuk et n’est publiée que
sur [trishchuk.com/rekey/fr](https://trishchuk.com/rekey/fr/) et dans ce dépôt.

---

[Site web](https://trishchuk.com/rekey/fr/) · [Confidentialité (en anglais)](https://trishchuk.com/rekey/privacy.html)

[English](README.md) · [Українська](README.uk.md) · [Deutsch](README.de.md) · [Polski](README.pl.md) · [Español](README.es.md) · [Français](README.fr.md) · [Nederlands](README.nl.md) · [Ελληνικά](README.el.md) · [Türkçe](README.tr.md) · [עברית](README.he.md) · [العربية](README.ar.md)
