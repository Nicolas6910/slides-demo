# M1 — Comprendre l'IA et le paysage Claude · démo animée

Version **de démonstration** du module 1 du Parcours Opérateurs (The Shift AI) :
une présentation HTML autonome, animée avec [Anime.js](https://animejs.com) (v3.2.2, vendorée dans `vendor/`).

👉 **Démo en ligne : https://nicolas6910.github.io/slides-demo/**

## Ce que ça démontre

- 54 slides, reprises du deck Marp `slides-m1-comprendre-ia.md` (texte relu et corrigé, voir plus bas)
- les éléments apparaissent **un par un** à chaque « suivant » (build steps)
- **transitions** de slide (glissement + fondu, dans le sens de la navigation)
- **schémas animés** : les trois familles d'IA, frise 2022, prédiction du mot suivant,
  tokenisation, compteurs, fenêtre de contexte, débordement hors fenêtre,
  tailles de fenêtres, les cinq acteurs, la frise de l'AI Act, les quatre briques (liens SVG tracés)
- **logos officiels** : logo The Shift AI issu du thème Marp officiel, et le vrai logo de chaque
  entreprise citée (Anthropic, OpenAI, Google, Microsoft, Mistral AI, Netflix, Spotify, Chrome)
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

## Corrections de fond par rapport au deck d'origine

| Sujet | Avant | Après |
| --- | --- | --- |
| Familles d'IA | IA classique / IA de vision / IA générative | IA symbolique (règles écrites) / machine learning (règles apprises) / IA générative — un seul critère de tri, plus une slide « et la vision ? » qui explique que la vision est un domaine d'application, pas une famille |
| Plan du module | « Quatre étapes » pour cinq parties | Cinq étapes, alignées sur les cinq parties |
| Modèles et fenêtres | Sonnet 4.6 · Opus 4.6 (1 M), Haiku 4.5 (200 k) | Opus 5.5 · Sonnet 5 (1 M), Haiku 4.5 (200 k), lineup de septembre 2026, mention des limites de plan côté `claude.ai` |
| Hallucinations | « sur Claude 4.6 » | « les modèles frontière de 2026 — côté Anthropic, Claude Opus 5.5 » |
| « Il ne cherche pas » | contredisait la slide suivante sur la recherche web | le modèle seul ne consulte rien ; chercher est un **outil** qu'on lui ajoute |
| Mémoire | « pas de mémoire d'une conversation à l'autre » | « pas de mémoire spontanée : il ne retrouve que ce qu'on lui redonne » |
| Prédiction du mot suivant | mot | mot, avec la précision qu'il s'agit d'un **token** |
| Date de ChatGPT | « fin 2022 » | 30 novembre 2022 |
| AI Act | « premier cadre légal au monde », sanctions « à partir d'août 2026 » | règlement (UE) 2024/1689, frise 2024 → 2026, obligation de maîtrise de l'IA depuis le 2 février 2025, application du reste depuis le 2 août 2026, amendes 35 M€ / 7 % et 15 M€ / 3 % |
| Acteurs | « Mistral — France », « Copilot — Microsoft » | « Le Chat — Mistral AI · France », « Copilot — Microsoft 365 », plus la mise en garde add-ins Claude ≠ Microsoft 365 Copilot |
| Écosystème Claude | « le plus complet en 2026 » | « écosystème bureautique » (superlatif invérifiable retiré) |
| Probabilités du schéma | 64 / 21 / 11 / 3 = 99 % | 64 / 21 / 12 / 3 = 100 % |

## Logos

- `assets/logo-the-shift.png` — logo officiel The Shift AI, repris du dépôt de la formation.
- `assets/logos/*.svg` — [Simple Icons](https://simpleicons.org) (Anthropic, Claude, OpenAI, Mistral AI,
  Netflix, Spotify, aux couleurs de marque) et Wikimedia Commons (Google Gemini, Google Chrome,
  Microsoft, Microsoft 365 Copilot, drapeau européen). Usage nominatif, à des fins pédagogiques.

Sources vérifiées : [docs Anthropic — Models overview](https://docs.anthropic.com/en/docs/about-claude/models/overview)
(septembre 2026) et le [calendrier d'application de l'AI Act](https://artificialintelligenceact.eu/implementation-timeline/).

---

Contenu pédagogique : The Shift AI — Parcours Opérateurs, module 1.
Ce dépôt est un **prototype de rendu**, pas le support officiel.
