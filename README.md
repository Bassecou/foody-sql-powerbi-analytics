# 🍽️ Foody — Analyse Commerciale & Logistique

Projet pédagogique combinant modélisation de base de données SQL et rapport Power BI, pour une société fictive d'import-export alimentaire.

## Contexte

**Foody** est une société fictive d'import-export de produits alimentaires. Ce projet est normalement proposé aux étudiants de niveau Master en version SQL uniquement — j'ai choisi d'aller plus loin en traitant les deux volets : **modélisation et requêtage SQL**, puis **exploration et restitution sous Power BI**, sans problématique imposée : je l'ai définie moi-même à partir des données.

## Objectifs

- Construire une base de données relationnelle propre à partir de 8 fichiers sources bruts
- Interroger les données en SQL pour en extraire les premiers constats
- Formuler une problématique business et y répondre par un rapport Power BI

## Livrable

### 📄 Rapport Power BI

![Foody — Synthèse Globale](assets/foody_rapport.jpg)

[Consulter le rapport complet (PDF, 3 pages)](Foody_Rapport.pdf) — Synthèse Globale, Performance Commerciale, Suivi Logistique

## Démarche

1. **Modélisation de la base SQL** — étude du schéma relationnel (tables *Client, Commande, DetailCommande, Produit, Fournisseur, Employé, Catégorie, Messager*), rédaction du Modèle Physique de Données, et import de 8 fichiers CSV dont les colonnes en anglais ont dû être fait correspondre au schéma en français
2. **Requêtage SQL** — 6 modules progressifs sous SQLite : requêtage simple, calculs et fonctions, agrégats, jointures, sous-requêtes, opérations ensemblistes (UNION/INTERSECT/EXCEPT)
3. **Nettoyage et exploration sous Power Query** — typage des colonnes, gestion des valeurs manquantes, relations entre tables
4. **Définition de la problématique** — formulation d'une question business à partir des tendances observées, structurée via un strategy canvas
5. **Construction du rapport** — 3 pages répondant à la problématique : vue d'ensemble commerciale, performance par employé, suivi des délais et retards de livraison

## Ce que j'en retiens

Le SQL et le Power BI ne sont pas deux blocs indépendants : la rigueur du requêtage (jointures, agrégats) éclaire directement les indicateurs à mettre en rapport, et permet de vérifier chaque chiffre affiché avant de le présenter à un public métier.

## Compétences mobilisées

SQL (SQLite : jointures, sous-requêtes, agrégats, opérations ensemblistes) · Modélisation de données (MPD) · Power BI (Power Query, rapport multi-pages) · Définition de problématique business

## Auteur

**Bassecou Touré** · Data Analyst · Data ESN
[LinkedIn](https://www.linkedin.com/in/bassecou-toure) · [Portfolio](https://bassecou.github.io/portfolio/)
