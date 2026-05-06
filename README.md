<div align="center">

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

**Projet de Gestion de Pharmacie — Système intégré de gestion des stocks et des opérations pharmaceutiques**

*Application web complète pour la gestion des produits, ventes, fournisseurs, clients et ordonnances dans une pharmacie moderne*

</div>

---

## 📋 Table des matières

- [Aperçu du projet](#-aperçu-du-projet)
- [Objectifs](#-objectifs)
- [Architecture du système](#-architecture-du-système)
- [Modélisation des données](#-modélisation-des-données)
- [Structure des entités principales](#-structure-des-entités-principales)
- [Fonctionnalités](#-fonctionnalités)
- [Sécurité et conformité](#-sécurité-et-conformité)
- [Technologies utilisées](#-technologies-utilisées)
- [Installation](#-installation)

---

## 🎯 Aperçu du projet

Ce projet consiste en une **application web de gestion pharmaceutique complète** permettant de digitaliser les opérations d’une pharmacie :

- Gestion des stocks de médicaments en temps réel  
- Suivi des ventes et commandes  
- Gestion des fournisseurs et contrats  
- Traitement des ordonnances médicales  
- Gestion des clients et du personnel  
- Génération de factures et rapports analytiques  

L’objectif principal est d’améliorer **l’efficacité opérationnelle, la traçabilité et la conformité réglementaire** dans le secteur pharmaceutique.

---

## 🎯 Objectifs

### Objectif principal

Développer un système intégré permettant de centraliser et automatiser la gestion d’une pharmacie.

### Objectifs spécifiques

- Optimiser la gestion des stocks pharmaceutiques  
- Automatiser les ventes et commandes clients  
- Sécuriser les données médicales et financières  
- Améliorer la traçabilité des produits et opérations  
- Faciliter la gestion des fournisseurs et contrats  
- Générer des rapports analytiques et financiers  

---

## 🏗 Architecture du système
┌────────────────────┐
│ Interface Web │
│ HTML / CSS / JS │
│ Bootstrap │
└─────────┬──────────┘
│
▼
┌────────────────────┐
│ Backend PHP │
│ Logique métier │
│ API & traitements │
└─────────┬──────────┘
│
▼
┌────────────────────┐
│ Base de données │
│ MySQL │
│ (toutes entités) │
└────────────────────┘


---

## 🧠 Modélisation des données

Le système repose sur une base de données relationnelle structurée autour de plusieurs modules fonctionnels.

---

## 🧩 Structure des entités principales

### 👤 Gestion des utilisateurs

| Entité | Description |
|--------|-------------|
| Utilisateur | Table mère des comptes |
| Administrateur | Supervision du système |
| Personnel | Gestion opérationnelle |
| Client | Utilisateur final |

---

### 💊 Gestion des produits

| Entité | Description |
|--------|-------------|
| Produits | Médicaments en stock |
| Forme pharmaceutique | Comprimé, sirop, crème… |
| Catégorie | Générique, plante… |
| Type | Avec ou sans ordonnance |
| Unité de stockage | Flacon, plaquette… |
| Historique produits | Traçabilité des actions |

---

### 🏭 Gestion des fournisseurs

| Entité | Description |
|--------|-------------|
| Fournisseurs | Informations fournisseurs |
| Contrats | Accords commerciaux |
| Historique fournisseurs | Suivi des opérations |

---

### 🛒 Gestion des commandes

| Entité | Description |
|--------|-------------|
| Commandes | Demandes clients |
| Produits_Commandes | Détail des articles |
| Historique_Commandes | Suivi des modifications |
| Achats | Historique client |

---

### 💰 Gestion financière

| Entité | Description |
|--------|-------------|
| Factures | Ventes et achats |
| Paiements | Transactions financières |
| Promotions | Réductions appliquées |
| Assurances | Couverture clients |

---

### 🏥 Gestion médicale

| Entité | Description |
|--------|-------------|
| Ordonnances | Prescriptions médicales |
| Validation_ordonnances | Contrôle pharmaceutique |
| Dossiers pharmaceutiques | Historique médical client |

---

### 📊 Gestion des stocks

| Entité | Description |
|--------|-------------|
| Stock_Produits | Niveau de stock actuel |
| Mouvements_Stock | Entrées / sorties |
| Historique opérations | Traçabilité complète |

---

### 💬 Communication

| Entité | Description |
|--------|-------------|
| Messages | Communication interne |
| Notifications | Alertes système |

---

## ⚙️ Fonctionnalités principales

### 👤 Gestion des utilisateurs
- Création et authentification des comptes  
- Gestion des rôles (admin, personnel, client)  
- Activation via email ou SMS  
- Contrôle d’accès sécurisé  

---

### 💊 Gestion des stocks
- Ajout et mise à jour des produits  
- Suivi en temps réel des stocks  
- Alertes produits périmés ou critiques  
- Importation Excel  
- Historique complet des mouvements  

---

### 🛒 Gestion des ventes
- Création des commandes clients  
- Génération automatique des factures  
- Suivi des paiements  
- Historique des achats  

---

### 🏭 Gestion fournisseurs
- Ajout et suivi des fournisseurs  
- Gestion des contrats  
- Historique des transactions  

---

### 🏥 Gestion des ordonnances
- Téléchargement d’ordonnances numérisées  
- Validation pharmaceutique  
- Suivi du traitement médical  

---

### 📊 Analyse et reporting
- Statistiques de ventes  
- Analyse des performances  
- Suivi des produits les plus vendus  
- Rapports d’inventaire  

---

## 🔐 Sécurité et conformité

- Chiffrement des mots de passe  
- Contrôle d’accès basé sur les rôles (RBAC)  
- Traçabilité des opérations  
- Respect des normes pharmaceutiques et légales  

---

## 🧰 Technologies utilisées

### 💻 Frontend
- HTML5  
- CSS3  
- JavaScript  
- Bootstrap  

### ⚙️ Backend
- PHP  

### 🗄️ Base de données
- MySQL  

### 🧪 Outils
- XAMPP / WAMP  
- Visual Studio Code  
- StarUML (diagrammes UML)  
- Excel (import/export données)  

---

## 🚀 Installation

```bash
git clone https://github.com/the18ines/Pharmacy_management.git 

Étapes :
Installer XAMPP / WAMP
Lancer Apache + MySQL
Importer la base de données pharmacie.sql
Configurer config.php
Accéder au projet :
http://localhost/pharmacy-management
