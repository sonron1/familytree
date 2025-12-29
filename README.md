# FamilyTree 🌳

Une application moderne de gestion d'arbres généalogiques qui permet à chaque membre de la famille de créer et maintenir sa propre vision de l'histoire familiale tout en restant connecté avec les autres membres.

## 📋 Table des matières

- [Concept](#concept)
- [Fonctionnalités principales](#fonctionnalités-principales)
- [Architecture](#architecture)
- [Technologies envisagées](#technologies-envisagées)
- [Roadmap](#roadmap)
- [Installation](#installation)
- [Contribution](#contribution)

## 💡 Concept

FamilyTree adopte une approche unique : chaque utilisateur possède **son propre arbre généalogique** qu'il gère de manière autonome. Les arbres peuvent ensuite se connecter entre eux pour créer une expérience collaborative enrichie, tout en évitant les conflits de modification et en permettant à chacun de raconter l'histoire familiale selon sa perspective.

### Avantages de cette approche

- Aucun conflit de modifications entre membres
- Chacun raconte l'histoire familiale à sa manière
- Interactions sociales favorisant l'engagement
- Architecture technique simplifiée

## ✨ Fonctionnalités principales

### 👤 Gestion des comptes et membres

#### Informations par personne
- Identité complète (nom, prénom, âge, date de naissance)
- Photo principale et galerie photos
- Biographie détaillée (lieu de naissance, profession, anecdotes, événements marquants)

#### Système d'invitation
- Ajout de membres via ID utilisateur
- **QR Code** pour faciliter les invitations en famille
- Acceptation requise avant visibilité
- Possibilité de se retirer d'un arbre après acceptation

#### Niveaux de visibilité
- **Public** : Nom, prénom, dates, photo principale
- **Restreint** : + galerie photos et informations détaillées
- **Privé** : Profil anonymisé ("Membre de la famille")

### 🔗 Connexions et interactions

#### Entre arbres connectés
- Vue "arbre étendu" montrant les branches communes
- Notifications lors d'ajout d'ancêtres communs
- Comparaison de versions pour détecter les différences d'informations

#### Fonctionnalités sociales
- Système de likes sur les profils et photos
- Commentaires et partages
- Fil d'actualité familial (ex: "Marie a ajouté 5 photos de Grand-mère")
- Stories et souvenirs éphémères
- Événements familiaux à venir

### 🎨 Visualisation

#### Options de vue
- Arbre descendant (ancêtres → descendants)
- Arbre ascendant (personne → ancêtres)
- Vue en éventail
- Vue générale avec branches

Le design adopte un style **moderne et minimaliste** pour une expérience utilisateur optimale.

### 📦 Fonctionnalités techniques

#### Import/Export
- Format **GEDCOM** pour interopérabilité
- Import depuis Ancestry, MyHeritage, etc.
- Export pour sauvegarde et migration

#### Gestion des relations
- Support de différents types de liens (mariage, adoption, partenariat)
- Gestion des familles recomposées

## 🏗️ Architecture

### Principe fondamental
Chaque utilisateur possède **son arbre unique**, sans fusion entre arbres. Cette architecture offre :
- Autonomie complète de gestion
- Pas de conflits de modification
- Connexions sociales entre arbres pour enrichir l'expérience

### Responsabilités
- Chaque utilisateur gère et modifie uniquement son propre arbre
- Les membres connectés peuvent consulter les arbres des autres sans les modifier

## 🛠️ Technologies envisagées

### Visualisation d'arbres
- **D3.js** : Très flexible, idéal pour des arbres personnalisés
- **Cytoscape.js** : Excellent pour les graphes de relations
- **GoJS** : Bibliothèque payante mais puissante
- **vis.js** : Gratuit, adapté pour les réseaux

## 🗓️ Roadmap

### Phase 1 - Fonctionnalités Core
- [ ] Création de compte utilisateur
- [ ] Création d'arbre généalogique
- [ ] Ajout de membres (nom, prénom, dates, photos)
- [ ] Visualisation de base de l'arbre

### Phase 2 - Fonctionnalités sociales
- [ ] Système d'invitation (ID + QR Code)
- [ ] Connexion entre arbres
- [ ] Likes, commentaires, partages
- [ ] Fil d'actualité familial

### Phase 3 - Fonctionnalités avancées
- [ ] Niveaux de visibilité
- [ ] Notifications intelligentes
- [ ] Comparaison d'arbres
- [ ] Stories et événements
- [ ] Import/Export GEDCOM

## 🚀 Installation

```bash
# À compléter lors du développement
git clone https://github.com/votre-username/familytree.git
cd familytree
npm install
npm start
```

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou à soumettre une pull request.

## 📄 Licence

À définir

## 📧 Contact

Pour toute question ou suggestion, n'hésitez pas à nous contacter.

---

**FamilyTree** - Préserver et partager l'histoire familiale, ensemble.