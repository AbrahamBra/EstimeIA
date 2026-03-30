# Design Direction — estimeIA

## Elements à garder
- Positionnement "expert augmenté" (pas une boîte noire, pas un outil générique)
- Ton français, professionnel, direct — s'adresse à des agents, pas à des startuppers
- Les chiffres concrets (80%, 60h, 15 min) : ce sont les accroches visuelles clés

## Références choisies
- Aucune référence externe nommée (Mode D — direction dérivée des mots-clés)

## Direction visuelle (validée)

- Palette :
  - oklch(0.97 0.01 90)  — fond ivoire légèrement chaud (fond principal)
  - oklch(0.25 0.06 230) — bleu marine profond (titres, CTAs, nav)
  - oklch(0.58 0.14 155) — vert sauge (bénéfices, gains, badges)
  - oklch(0.15 0.04 230) — quasi-noir bleuté (footer, sections sombres)

- Typographie :
  - Serif élégant (Playfair Display ou DM Serif) → H1, H2
  - Sans-serif neutre (Inter) → corps, labels, boutons
  - Mono (JetBrains Mono) → chiffres DVF, fourchettes de prix, stats

- Layout :
  - Mobile-first obligatoire
  - Généreux en whitespace — chaque section respire
  - Cards avec légère ombre portée (pas de glassmorphism)

- Effets :
  - Grain très subtil sur les sections à fond sombre (footer)
  - Photos immobilières avec overlay bleu marine semi-transparent
  - Pas de glassmorphism, pas d'effets néon

- Motion :
  - Éditorial, lent — révélations par scroll (fade + translateY)
  - Chiffres animés sur les stats (80%, 60h, 15 min)
  - Pas de spring, pas de rebond — transitions ease-out uniquement

- Ambiance :
  - Expert consultant premium — chaleur humaine + précision IA
  - Jamais corporate froid, jamais startup générique
  - Signal de confiance et d'expertise terrain

## Contraintes (ne pas toucher)
- Mobile-first — aucun composant sans version mobile validée
- Chargement rapide — pas d'images lourdes non optimisées
- Langue française uniquement
- Chiffres concrets toujours visibles (80%, 60h, 15 min) — ne pas les diluer

## Validation
- Date : 2026-03-30
- Confirmé par l'utilisateur : oui
