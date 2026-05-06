# Design System — Brasserie du Vénasque

> Système de design complet pour Claude Design, basé sur l'identité visuelle existante (étiquettes, bâche, banderole, site brasserie-du-venasque.com). À coller dans Claude Design > Design Systems > Create new design system.

---

## 1. Identité de marque

### Nom
**Brasserie du Vénasque**

### Tagline officielle (telle qu'utilisée sur PLV)
**BIÈRES & LIMONADES ARTISANALES — PAYS DE LUCHON**

### Mission
Brasserie artisanale au cœur des Pyrénées (Comminges, Haute-Garonne), brassée à l'eau de source du village de Montauban-de-Luchon. Bières et boissons gazeuses authentiques, illustrées par la faune pyrénéenne.

### Valeurs visuelles à toujours transmettre
1. **Authenticité pyrénéenne** — montagne, eau de source, terroir local
2. **Convivialité refuge** — chaleur, partage, après l'effort
3. **Savoir-faire artisanal** — passion, qualité, méthodes traditionnelles
4. **Faune locale** — animaux pyrénéens en illustrations linéaires noir & blanc
5. **Audace maîtrisée** — classiques + recettes innovantes (IPA, NEIPA, Stout…)

### À éviter absolument
- Toute référence à **Venasque (Vaucluse / Provence)** — confusion fréquente, vigilance maximale
- Esthétique provençale (lavande, cigales, ocre méditerranéen)
- Visuels génériques de bière (chopes en mousse débordante, lutins de brasserie, style "brasseur belge")
- Ton corporate, marketing creux, jargon élitiste
- Images trop léchées / publicitaires : on privilégie un visuel direct, brut, artisanal

---

## 2. Palette de couleurs

### Couleurs primaires (charte signature)

| Nom | Hex | RGB | CMJN approx | Usage |
|---|---|---|---|---|
| **Noir Vénasque** | `#0A0A0A` | 10, 10, 10 | 0/0/0/100 | Fond signature, bandeaux étiquettes, fond de bâche, typo principale sur clair |
| **Or Pyrénéen** | `#F0B414` | 240, 180, 20 | 0/30/100/0 | Couleur d'accent signature, titres punchy, soleil/cerf de la bâche, CTA |
| **Or Profond** | `#DCA014` | 220, 160, 20 | 5/35/100/5 | Variante or pour gradients ou hover |
| **Blanc Source** | `#FFFFFF` | 255, 255, 255 | 0/0/0/0 | Texte sur noir, illustrations linéaires, logo |
| **Blanc Cassé** | `#FAF7F0` | 250, 247, 240 | 0/2/5/0 | Fond doux alternatif (newsletters, fiches produits) |

### Couleurs secondaires — étiquettes par bière

Chaque bière de la gamme a une couleur d'étiquette signature. Utiliser la couleur correspondante quand on parle d'une bière spécifique.

| Bière | Style | Couleur étiquette | Hex | Animal |
|---|---|---|---|---|
| **Bram's** | Blonde 5% | Jaune Or | `#E8A82C` | Cerf |
| **Bourek** | Ambrée 5% | Vert Tilleul | `#9DBE5A` | Mouflon (cornes) |
| **Mouflon** | Brune 4% | Brun Cuivré | `#A0552B` | Mouflon |
| **Louva** | Blanche 4,5% | Gris Argent | `#C0C0C0` | Loup |
| **Lynx** | Ambrée combava 5% | Bleu Glacier | `#3A9BCB` | Lynx |
| **Aigle Royal** | Ambrée belge 7% | Orange Profond | `#E84E1B` | Aigle |
| **Izard** | Blonde bio 5% | Vert Sapin | `#1E9170` | Izard |
| **Arrian** | Triple 8,5% | Rouge Bordeaux | `#9E2A2B` | Hibou/Rapace |
| **Marmotte** | Milkshake IPA 4,5% | Rose Poudré | `#E8B0BC` | Marmotte |
| **Trueita** | Lager 5% | Cyan Doux | `#7AC4C8` | Truite |
| **Mésange** | Sans alcool 0,5% | Jaune Pâle | `#F0E8B0` | Mésange |
| **OPA Blonde** | Blonde IPA 5% | Beige Sable | `#E8C896` | (Sanglier) |
| **OPA Ambrée** | Pale Ale 6% | Saumon Brique | `#E89478` | (Sanglier) |

### Couleurs saisonnières

| Bière saison | Couleur | Hex |
|---|---|---|
| **Bière de Printemps** (Session IPA) | Vert Tendre | `#9CC95C` |
| **Bière d'Été** (blanche fruitée) | Rose Fruité | `#E8748C` |
| **Bière d'Automne au Miel** | Or Miel | `#D89020` |
| **Bière d'Hiver** (épicée) | Rouge Épice | `#A83828` |

### Couleurs fonctionnelles (UI / web / newsletter)

| Nom | Hex | Usage |
|---|---|---|
| Texte principal | `#0A0A0A` | Corps de texte sur fond clair |
| Texte secondaire | `#4A4A4A` | Légendes, métadonnées |
| Fond clair | `#FAF7F0` | Fond newsletter, fiches produits |
| Bordure / séparateur | `#E0DDD5` | Lignes, cadres légers |
| Succès | `#1E9170` | Confirmations, dispo en stock |
| Alerte | `#E84E1B` | Rupture, urgence |

---

## 3. Typographies

### Typographie principale — Titres et accroches
**Famille recommandée : Anton, Oswald, Bebas Neue ou Barlow Condensed Black**

- Caractéristiques : sans-serif **condensée**, capitales, traits épais et géométriques
- Référence visuelle : le mot-clé "VÉNASQUE" du logo, les titres "BIÈRES & LIMONADES ARTISANALES" sur la bâche
- Usage : titres de page, titres de sections, noms de bières, accroches PLV
- **Toujours en MAJUSCULES** pour les titres de marque

```css
font-family: 'Anton', 'Oswald', 'Bebas Neue', 'Barlow Condensed', sans-serif;
font-weight: 700;
text-transform: uppercase;
letter-spacing: 0.02em;
```

### Typographie secondaire — Sous-titres et labels
**Famille recommandée : Montserrat Bold ou Poppins SemiBold**

- Caractéristiques : sans-serif géométrique, lisible, moderne
- Usage : sous-titres ("Bière Ambrée Houblonnée"), labels, mentions ("PRODUIT DU PAYS DE LUCHON")
- Souvent en majuscules avec letter-spacing

```css
font-family: 'Montserrat', 'Poppins', sans-serif;
font-weight: 600;
letter-spacing: 0.05em;
```

### Typographie de texte courant — Corps et descriptions
**Famille recommandée : Inter, Open Sans ou Source Sans Pro**

- Caractéristiques : sans-serif neutre, hautement lisible, moderne
- Usage : descriptifs de produits, paragraphes newsletters, texte de fiches, blogs

```css
font-family: 'Inter', 'Open Sans', 'Source Sans Pro', sans-serif;
font-weight: 400;
line-height: 1.6;
```

### Hiérarchie typographique web

| Élément | Police | Poids | Taille (desktop) | Taille (mobile) |
|---|---|---|---|---|
| H1 | Anton | 700 | 64px / 4rem | 40px / 2.5rem |
| H2 | Anton | 700 | 48px / 3rem | 32px / 2rem |
| H3 | Anton | 700 | 32px / 2rem | 24px / 1.5rem |
| H4 / Sous-titre | Montserrat | 600 | 20px / 1.25rem | 18px / 1.125rem |
| Corps | Inter | 400 | 16px / 1rem | 16px / 1rem |
| Petit / Légende | Inter | 400 | 14px / 0.875rem | 14px / 0.875rem |
| Bouton CTA | Montserrat | 700 | 16px / 1rem | 16px / 1rem |

---

## 4. Logo et marques

### Logo principal
- **Symbole** : trois montagnes stylisées surmontant le texte, avec une goutte d'eau en dessous (rappel de l'eau de source du village)
- **Texte** : "BRASSERIE DU VÉNASQUE" en sans-serif condensée
- **Format blason** : encadré dans un écu/bouclier blanc sur fond noir (version PLV/bâche)
- **Format rond** : cercle noir avec contour, montagnes + texte (version étiquette)

### Variantes
1. **Logo blanc sur noir** (utilisation principale, PLV, packaging)
2. **Logo noir sur fond clair** (papier, factures, documents)
3. **Logo couleur** (rare — uniquement contextes où la couleur signature de la bière s'applique)

### Zone de protection
Conserver autour du logo une zone vide équivalente à **1× la hauteur des montagnes** sur tous les côtés.

### Tailles minimales
- Web : 80px de large minimum
- Print : 25mm de large minimum

---

## 5. Iconographie & illustrations

### Style général
- **Illustrations linéaires** noir & blanc (outline)
- Traits **épais et constants**, géométriques
- **Symétrie et stylisation** — pas de réalisme photo
- Inspiration : gravures naturalistes modernisées

### Bibliothèque d'illustrations existantes
1. **Faune pyrénéenne** (étiquettes) : cerf (Bram's), mouflon, loup, lynx, aigle, izard, hibou, marmotte, mésange, truite, sanglier
2. **Brasserie** (bâche/banderole) : houblon, épi de blé, feuilles, blason BdV
3. **Géométrique** : trois montagnes, goutte d'eau, sapins (motifs latéraux des étiquettes)

### Pictogrammes recommandés (style à respecter)
- Outline 2px constant
- Coins légèrement arrondis (rayon 2-4px)
- Pas de remplissage couleur (sauf accent or pour l'emphase)
- Style cohérent avec les illustrations existantes des étiquettes

---

## 6. Composants visuels signature

### Le bandeau noir / bandeau étiquette
Élément récurrent : bandeau **noir profond** avec texte blanc en capitales condensées. C'est la signature visuelle.

```
┌─────────────────────────────────────┐
│  AIGLE ROYAL                        │  ← Anton Bold, blanc
│  Bière Ambrée Houblonnée            │  ← Montserrat 600, blanc
└─────────────────────────────────────┘
   Fond noir #0A0A0A
```

### Le pavé "Pays de Luchon"
Mention systématique sur tous les supports produits :
**"PRODUIT DU PAYS DE LUCHON"** ou **"BIÈRES & LIMONADES ARTISANALES — PAYS DE LUCHON"**
Style : Montserrat 600, capitales, letter-spacing 0.1em

### Le motif décoratif (fond)
Sur la bâche et la banderole : éléments graphiques épars (houblon, épis, feuilles) en outline blanc dispersés sur fond noir, certains accentués en or. Crée une ambiance "brasserie" sans surcharge.

### Les sapins miniatures
Petits pictogrammes de sapins (▲) utilisés en encadrement ou séparateurs, présents sur toutes les étiquettes.

---

## 7. Photographie & images

### Style photographique recherché
- **Lumière naturelle**, contexte montagne/refuge
- Bouteilles en situation : main qui tient, table en bois, paysage pyrénéen en arrière-plan
- Couleurs chaudes et authentiques, pas saturées
- Plans rapprochés sur la matière (mousse, bois, eau)

### Sujets prioritaires
- Bouteilles en condition réelle (terrasse, randonnée, refuge)
- Paysages des Pyrénées centrales (Comminges, Luchon, Vénasque)
- Boutique de Bagnères-de-Luchon (place du Maréchal Joffre)
- L'équipe au travail (production, livraisons, boutique)
- Détails artisanaux (cuves, malt, houblon, étiquetage)

### À éviter
- Photos stock génériques de bière
- Mises en scène trop léchées / studio
- Surutilisation de filtres "vintage" caricaturaux

---

## 8. Ton de voix

### Personnalité
**Chaleureux, sincère, sans prétention.** Comme on accueillerait un randonneur qui pousse la porte de la boutique après une journée en montagne.

### Caractéristiques
- Vocabulaire concret et imagé (montagne, refuge, eau de source, terroir)
- Phrases courtes pour les accroches, plus développées pour les descriptifs
- Précision technique sans pédanterie (IBU, EBC, dry-hopping mentionnés quand pertinent)
- Émojis modérés sur les réseaux sociaux : ⛰️ 🍺 💛 🌿 ☀️ — jamais en excès

### Adaptation par cible

| Cible | Ton |
|---|---|
| **B2C particuliers** (newsletter, boutique) | Complice, chaleureux, saisonnier |
| **B2B pros** (CHR, cavistes) | Structuré, utile, factuel |
| **Prospection** | Accrocheur, valorise le local et la qualité |
| **Réseaux sociaux** | Convivial, vivant, avec une touche d'humour |

### Vocabulaire signature
- "Pays de Luchon" plutôt que "Comminges" en signature courte
- "Au cœur des Pyrénées" / "Pyrénées centrales"
- "Eau de source" / "brassée à l'eau de source du village"
- "Faune pyrénéenne"
- "Artisanale" / "savoir-faire" / "passion"
- "Refuge" / "après l'effort" / "convivialité"

---

## 9. Layouts par support

### Newsletter Brevo (B2C particuliers)
- **Largeur** : 600px
- **Hero** : visuel produit ou ambiance + titre Anton blanc sur noir
- **Corps** : sections alternées fond clair `#FAF7F0` et noir
- **CTA** : bouton or `#F0B414` avec texte noir, Montserrat 700
- **Footer** : fond noir, logo blanc, mentions légales en gris

### Newsletter Brevo (B2B pros)
- **Largeur** : 600px
- **Hero** : sobre, axé info (nouveautés, dispo fûts)
- **Corps** : structure en blocs lisibles avec titres clairs
- **Tableaux** de disponibilité possibles
- **CTA** : "Commander sur Easybeer" ou "Contacter Guillaume pour la livraison"
- Mention systématique de la tournée concernée

### Fiche produit
- **Hero** : photo bouteille fond noir/clair selon contexte, format vertical
- **Bandeau noir** sous la photo : nom de la bière + style (réplique de l'étiquette)
- **Onglets** : Description / Caractéristiques techniques / Accords mets-bière / Disponibilité
- **Couleurs** : fond clair `#FAF7F0`, accents avec la couleur d'étiquette de la bière

### PLV (affiche, kakémono, bâche)
- **Fond** : noir profond `#0A0A0A`
- **Typo titre** : Anton blanc ou or, capitales géantes
- **Logo blason** : positionné en bas ou à gauche
- **Mention** : "PRODUIT DU PAYS DE LUCHON" toujours présente
- **Ornements** : motifs houblon/épis blancs et or dispersés

### Site web
- **Header** : noir, logo blanc, nav en Montserrat majuscules
- **Hero** : grand visuel saisonnier ou produit, accroche Anton blanc
- **Sections produits** : grille avec photos bouteilles fond noir, nom Anton, accent couleur d'étiquette
- **Footer** : noir, logo, contact, réseaux

---

## 10. Règles d'utilisation (do / don't)

### ✅ À faire
- **Toujours** mettre en valeur l'ancrage pyrénéen (Pays de Luchon, Comminges)
- **Toujours** mentionner l'animal pyrénéen quand on parle d'une bière
- Utiliser le **noir profond** comme fond signature pour les supports impactants
- Réserver l'**Or Pyrénéen** aux accroches et CTA — il doit rester un accent fort
- Garder les illustrations en **outline blanc** sur fond noir (cohérence)
- Utiliser **"VÉNASQUE"** avec son accent aigu sur le É, en capitales

### ❌ À ne pas faire
- Utiliser "Venasque" (sans accent) ou évoquer la Provence
- Mélanger plusieurs polices condensées différentes (rester sur Anton)
- Surcharger les visuels — l'élégance vient de l'espace et du contraste
- Utiliser des couleurs criardes hors de la palette
- Utiliser le logo couleur sans nécessité
- Faire des photographies trop "premium / luxe" — l'esprit est artisanal et terrien

---

## 11. Exemples d'application — gabarits prêts à l'emploi

### Accroches signature
- "Au cœur des Pyrénées, des bières artisanales à la passion authentique"
- "Brassée à l'eau de source — Pays de Luchon"
- "L'esprit refuge en bouteille"
- "Bières & limonades artisanales — Pays de Luchon"

### Objets de newsletter (B2C, exemples)
- "🍺 Le printemps arrive à la Brasserie : 3 nouveautés à découvrir"
- "⛰️ Newsletter de mai : la Mésange sans alcool, les terrasses, et nos brassins du moment"
- "🌿 Cinq bières à emporter en randonnée ce week-end"

### Objets de newsletter (B2B, exemples)
- "Disponibilité fûts : tournée du mardi (Tarbes/Pau/Lourdes) — semaine du XX"
- "Nouveautés en stock : OPA Ambrée et Bière de Printemps prêtes à commander"
- "Animation été : un jeu-concours places Stade Toulousain pour vos clients"

---

## 12. Variables CSS prêtes à l'emploi

```css
:root {
  /* Couleurs principales */
  --color-noir: #0A0A0A;
  --color-or: #F0B414;
  --color-or-profond: #DCA014;
  --color-blanc: #FFFFFF;
  --color-blanc-casse: #FAF7F0;
  
  /* Couleurs fonctionnelles */
  --color-text: #0A0A0A;
  --color-text-secondary: #4A4A4A;
  --color-bg: #FAF7F0;
  --color-border: #E0DDD5;
  --color-success: #1E9170;
  --color-alert: #E84E1B;
  
  /* Couleurs étiquettes */
  --color-brams: #E8A82C;
  --color-bourek: #9DBE5A;
  --color-mouflon: #A0552B;
  --color-louva: #C0C0C0;
  --color-lynx: #3A9BCB;
  --color-aigle: #E84E1B;
  --color-izard: #1E9170;
  --color-arrian: #9E2A2B;
  --color-marmotte: #E8B0BC;
  --color-trueita: #7AC4C8;
  --color-mesange: #F0E8B0;
  --color-opa-blonde: #E8C896;
  --color-opa-ambree: #E89478;
  
  /* Typographies */
  --font-display: 'Anton', 'Oswald', 'Bebas Neue', sans-serif;
  --font-heading: 'Montserrat', 'Poppins', sans-serif;
  --font-body: 'Inter', 'Open Sans', sans-serif;
  
  /* Tailles */
  --fs-h1: 4rem;
  --fs-h2: 3rem;
  --fs-h3: 2rem;
  --fs-h4: 1.25rem;
  --fs-body: 1rem;
  --fs-small: 0.875rem;
  
  /* Espaces */
  --space-xs: 0.5rem;
  --space-sm: 1rem;
  --space-md: 2rem;
  --space-lg: 4rem;
  --space-xl: 6rem;
  
  /* Rayons */
  --radius-sm: 4px;
  --radius-md: 8px;
  --radius-lg: 16px;
  
  /* Ombres */
  --shadow-sm: 0 2px 4px rgba(10, 10, 10, 0.08);
  --shadow-md: 0 4px 12px rgba(10, 10, 10, 0.12);
  --shadow-lg: 0 8px 24px rgba(10, 10, 10, 0.16);
}
```
