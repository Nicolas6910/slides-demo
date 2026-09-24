# M1 — Comprendre l'IA et le paysage Claude · démo animée

Version **de démonstration** du module 1 du Parcours Opérateurs (The Shift AI) :
une présentation HTML autonome, animée avec [Anime.js](https://animejs.com) (v3.2.2, vendorée dans `vendor/`).

👉 **Démo en ligne : https://nicolas6910.github.io/slides-demo/**

## Ce que ça démontre

- 53 slides, **le texte d'origine** du deck Marp `slides-m1-comprendre-ia.md`
- les éléments apparaissent **un par un** à chaque « suivant » (build steps)
- **transitions** de slide (glissement + fondu, dans le sens de la navigation)
- **schémas animés** : trois familles d'IA, frise 2022, prédiction du mot suivant,
  tokenisation, compteurs, fenêtre de contexte, débordement hors fenêtre,
  tailles de fenêtres, les cinq acteurs, les quatre briques (liens SVG tracés)
- scène 16:9 mise à l'échelle : rendu identique de l'écran du portable au vidéoprojecteur

## Navigation

| Action | Touches |
| --- | --- |
| Élément / slide suivant | `→` `↓` `espace` `Entrée` `PageDown` · clic · swipe ← |
| Retour | `←` `↑` `PageUp` `Retour arrière` · clic bord gauche · clic droit · swipe → |
| Plein écran | `F` |
| Première / dernière slide | `Début` / `Fin` |
| Tout révéler sur la slide | `A` |
| Aide | `?` |

Lien profond : `#12` ouvre directement la slide 12.

## Utilisation

Aucun build, aucune dépendance réseau (hors la police Inter, qui dégrade proprement) :
ouvrez `index.html`, ou servez le dossier (`python3 -m http.server`).

---

Contenu pédagogique : The Shift AI — Parcours Opérateurs, module 1.
Ce dépôt est un **prototype de rendu**, pas le support officiel.
