# RECODE — landing page (Irina Sambucini)

Dépôt de la landing page du programme **RECODE** (« the self therapy method »).
Livrable principal : `index.html` (page autonome). Branche de travail : `claude/recode-design-refactor-44orbr`.

## Charte de marque
- **Couleurs** : `#EDECE9` (fond), `#F8F8F8` (surfaces claires), `#DDDBD8` (gris), `#5C0008` (wine — accent unique), `#000000` (texte). Pas d'or ni de tons chauds hors charte.
- **Typo** : Playfair Display (titres, façon logo Didone) + Poppins (corps). Bebas Neue uniquement pour les chiffres du timer.
- **Logo** : mot « RECODE » (Playfair 700, wine) + baseline italique « the self therapy method. ».
- Thème clair unique (l'identité de la marque est claire).

## Contexte produit / copy
La référence de messaging est **`docs/webinaire-recode.md`** (distillation du webinaire de vente). L'utiliser pour toute rédaction. Points clés :
- Cible : femmes qui ont « tout essayé par la tête », épuisées, en décalage dehors/dedans.
- Mécanisme : 95 % des actions pilotées par le subconscient ; le changement passe par le **corps + système nerveux** (EFT, cohérence cardiaque), pas par la volonté.
- Méthode **R-E-C-O-D-E** = **Réguler, Explorer, Connecter, Ouvrir, Décider, Évoluer** (⚠️ Module 1 = **Réguler**, pas « Reconnaître »).
- Ton : tutoiement, bienveillant mais cash, pas de promesse miracle, neurosciences vulgarisées.
- Prix landing actuel : **497 €** (webinaire : 2 248 € → 299 €). Garantie 6 mois, remboursement sur email si lives suivis + modules visionnés + exercices faits.

## Conventions techniques
- Deux formats coexistent : la **page complète** (`index.html`, pour hébergement/fichier .html) et, si demandé, une **version « bloc »** pour systeme.io (sans `<!doctype>/<html>/<head>`, polices en `@import`).
- Ne pas laisser de notes internes / placeholders entre crochets dans la version destinée à la mise en ligne.
- Respecter `prefers-reduced-motion` pour toutes les animations.
