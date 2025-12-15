# Tech for Good – Limoges 2026

Landing page HTML/CSS sans framework

## Présentation du projet

Ce projet sert de support pédagogique pour apprendre à construire une **landing page moderne**, performante et
accessible, **sans aucun framework**.  
L’objectif principal : maîtriser les fondamentaux du **HTML5 sémantique**, du **CSS moderne**, de l’accessibilité, du
SEO et de l’optimisation d’une page web d’événement.

La page présente la conférence fictive **Tech for Good – Limoges 2026**, avec ses intervenants, son programme, ses
ateliers et un formulaire d’inscription.

---

## Objectifs pédagogiques

- Structurer une page avec les balises sémantiques HTML5.
- Créer un hero responsive avec `<picture>`, `srcset` et `sizes`.
- Utiliser des variables CSS, Flexbox et Grid.
- Mettre en place une architecture CSS simple et cohérente.
- Intégrer des contenus responsives (images, cartes, grilles).
- Respecter les bonnes pratiques d’accessibilité (skip link, focus visible, ARIA).
- Configurer SEO, Open Graph et Twitter Cards.
- Écrire JSON-LD : organization, event, faq.
- Styliser un formulaire sans framework.
- Assurer une bonne lisibilité et un contraste suffisant.
- Comprendre les bases du manifest PWA et du fichier robots.txt.

---

## Fonctionnalités et sections de la page

### 1. Hero

- Logo
- Visuel principal
- Texte d’introduction
- Boutons CTA (“S’inscrire”, “Voir le programme”)
- Responsive complet

### 2. Pourquoi cet événement ?

- Présentation de l’initiative Tech for Good
- Trois cartes thématiques (Numérique responsable, Inclusion & accessibilité, Technologies durables)

### 3. Intervenant·es

- Portraits (générés)
- Nom, affiliation
- Sujet de conférence
- Bio courte

### 4. Infos pratiques

- Date
- Lieu
- Adresse
- Modalités d’accès

### 5. Programme

- Matin & après-midi
- Organisation horaire
- Liste détaillée des conférences, ateliers et démos

### 6. Ateliers & actions

- Liste simple d’activités complémentaires

### 7. Formulaire d’inscription

- Nom, prénom, email, organisation
- Checkbox RGPD obligatoire
- Semantics et accessibilité respectées

### 8. Partenaires

- Grille de logos non déformés
- Mise en page propre et responsive

### 9. FAQ

- Composant `<details>` / `<summary>` accessible
- Synthèse des questions clés

### 10. Footer

- Contacts
- Liens utiles
- Mentions

---

## Accessibilité

Le projet inclut :

- Un **skip link** visible au focus
- Des contrastes conformes
- Un focus visible renforcé
- Une navigation clavier fluide
- Une structure propre (titres hiérarchisés, rôles ARIA)
- Un formulaire accessible
- Des composants natifs (ex. : `<details>`) favorisant l’a11y

---

## SEO & Métadonnées

Inclus dans le projet :

- Meta description
- Canonical + hreflang
- OG / Facebook / LinkedIn
- Twitter Cards
- JSON-LD :
    - Organization
    - Event
    - FAQ
- Images optimisées pour le partage

---

## PWA (partiel)

Le projet contient :

- `manifest.json`
- Icons multi-tailles
- Coloration du navigateur (`theme-color`)

Ce n’est pas une PWA complète (pas de service worker), mais c’est une bonne introduction pour les apprenants.

---

## robots.txt

- Version par défaut : indexation autorisée
- Peut être remplacé par une version non indexable pour les environnements de test

---

## Licence

Ce projet est distribué sous licence **GNU GPL v3**.  
Vous êtes libres de l’utiliser, modifier, étudier et redistribuer vos versions dérivées, à condition de conserver la
même licence et les mêmes libertés pour les utilisateurs suivants.
