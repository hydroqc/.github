# Hydroqc

[![Discord](https://img.shields.io/badge/Discord-Rejoignez--nous-5865F2?logo=discord&logoColor=white)](https://discord.gg/BTPDntfaXH)
[![Website](https://img.shields.io/badge/Site-hydroqc.ca-blue)](https://hydroqc.ca)
[![License](https://img.shields.io/badge/Licence-AGPL--3.0-green)](https://github.com/hydroqc/hydroqc-ha/blob/main/LICENSE)

> **Une collection d'outils open-source pour intégrer votre compte Hydro-Québec avec vos plateformes de domotique**
>
> *A collection of open-source tools to integrate your Hydro-Québec account with home automation platforms*

## 🏠 À propos d'Hydroqc

Hydroqc est un projet open-source qui fournit des outils pour accéder et surveiller les informations de votre compte d'électricité Hydro-Québec. Connectez les données de votre compte à des systèmes de domotique comme Home Assistant, vous permettant de :

- 📊 **Surveiller la consommation** - Suivez votre consommation d'électricité en temps réel
- 💰 **Consulter les informations de facturation** - Vérifiez votre solde et vos coûts projetés
- ⚡ **Alertes de périodes de pointe** - Recevez des notifications pour les événements de pointe critique
- ❄️ **Crédits hivernaux** - Suivez l'accumulation de vos crédits hivernaux (tarif DCPC)
- 🚨 **Notifications de pannes** - Restez informé des pannes d'électricité
- 🏡 **Automatisation résidentielle** - Créez des automatisations basées sur vos données d'électricité

## 📦 Projets principaux

### [hydroqc-ha](https://github.com/hydroqc/hydroqc-ha) ⭐
**Intégration Home Assistant pour Hydro-Québec**

Composant natif pour Home Assistant permettant de surveiller vos comptes d'électricité Hydro-Québec. Les fonctionnalités incluent :
- Intégration complète du compte (solde, consommation, facturation)
- Support de multiples tarifs (D, DT, DPC/Flex-D, M, M-GDP, DCPC/Crédits hivernaux)
- Surveillance des périodes de pointe et alertes de pointe critique
- Suivi des crédits hivernaux
- Notifications de pannes
- Support multi-contrats
- Mode pointes uniquement (aucun identifiant de compte requis)

**Installation :** Disponible via [HACS](https://hacs.xyz/) ou installation manuelle

### [hydroqc.github.io](https://github.com/hydroqc/hydroqc.github.io)
**Site web de documentation**

Documentation complète pour tous les projets Hydroqc, disponible sur [hydroqc.ca](https://hydroqc.ca)

### [hass-blueprint-hydroqc](https://github.com/hydroqc/hass-blueprint-hydroqc)
**Blueprints Home Assistant**

Blueprints d'automatisation prêts à l'emploi pour Home Assistant afin de démarrer rapidement avec les intégrations Hydroqc.

## 🚀 Démarrage

1. **Pour les utilisateurs de Home Assistant :**
   - Installez l'[intégration hydroqc-ha](https://github.com/hydroqc/hydroqc-ha) via HACS
   - Suivez le [guide d'installation](https://hydroqc.ca/docs/)

2. **Explorez la documentation :**
   - Visitez [hydroqc.ca](https://hydroqc.ca) pour des guides complets et des tutoriels

3. **Rejoignez la communauté :**
   - Connectez-vous avec nous sur [Discord](https://discord.gg/BTPDntfaXH)
   - Signalez des problèmes sur GitHub
   - Contribuez au projet

## 📚 Documentation

- **Site web :** [hydroqc.ca](https://hydroqc.ca)
- **Guides d'installation :** Disponibles pour chaque projet
- **Documentation de l'API :** Consultez les dépôts individuels
- **FAQ :** Questions fréquentes et dépannage

## 💬 Communauté et support

- **Discord :** [Rejoignez notre serveur](https://discord.gg/BTPDntfaXH) pour le support, les discussions et les annonces
- **Problèmes :** Signalez des bogues ou demandez des fonctionnalités sur les dépôts GitHub respectifs
- **Contributions :** Les pull requests sont les bienvenues ! Consultez nos directives de contribution dans chaque dépôt

## 🤝 Contribuer

Nous accueillons les contributions de la communauté ! Que ce soit :
- 🐛 Rapports de bogues
- 💡 Demandes de fonctionnalités
- 📝 Améliorations de la documentation
- 🔧 Contributions de code

Consultez les dépôts individuels pour les directives de contribution spécifiques.

## 💖 Soutenir le projet

Si vous trouvez Hydroqc utile, envisagez de soutenir son développement :
- ⭐ Ajoutez une étoile à nos dépôts
- 💬 Partagez avec la communauté
- 💝 [Faire un don](https://hydroqc.ca/fr/dons)

## 📋 Tarifs supportés

L'intégration Hydroqc supporte tous les principaux tarifs résidentiels d'Hydro-Québec :
- **Tarif D** - Tarif résidentiel standard
- **Tarif DT** - Tarif double énergie
- **Tarif DPC (Flex-D)** - Tarification dynamique avec gestion des pointes
- **Tarif D + CPC** - Programme de crédits hivernaux
- **Tarif DCPC** - Tarification dynamique et crédits hivernaux combinés
- **Tarif M** - Tarif petite entreprise
- **Tarif M-GDP** - Tarif grande puissance

## ⚠️ Avertissement

**Ce projet n'est pas affilié, approuvé ou officiellement connecté à Hydro-Québec.**

Tous les noms de produits et d'entreprises sont des marques de commerce™ ou des marques déposées® de leurs détenteurs respectifs. Leur utilisation n'implique aucune affiliation ou approbation de leur part.

## 📄 Licence

Ce projet et ses composants sont sous licence AGPL-3.0. Consultez les dépôts individuels pour les informations de licence spécifiques.

---

<p align="center">
  <strong>Créé avec ❤️ par la communauté Hydroqc</strong>
</p>