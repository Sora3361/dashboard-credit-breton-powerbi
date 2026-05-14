# Dashboard de Pilotage – Crédit Breton 

## Contexte & Problématique

Le Crédit Breton est une agence de crédit dont les équipes n'avaient pas de visibilité claire sur les performances par agence ni sur les taux d'acceptation des dossiers de prêt. Sans outil centralisé, il était difficile d'identifier les agences en difficulté et d'agir rapidement pour réduire les délais de traitement.

**Problématique :** Comment permettre aux managers de piloter efficacement la performance des agences et d'identifier les dossiers à risque en un coup d'œil ?

---

## Objectif

Concevoir un dashboard de pilotage interactif permettant de :
- Suivre la **répartition des dossiers clients par agence** et par ville
- Analyser le **classement des agences** sur plusieurs années
- Visualiser le **taux d'acceptation et de refus** des dossiers par agence
- Identifier rapidement les agences avec les performances les plus basses

---

## Ce que j'ai fait

- Collecte et nettoyage des données brutes
- Modélisation des données et création des relations entre tables sous Power BI
- Création de **mesures DAX** pour calculer les KPI : taux d'acceptation, volume de dossiers par agence, évolution annuelle
- Conception de 4 pages de navigation : Demande de Prêt, Performances Agences, Indicateur Client, Liste des Clients
- Choix des visualisations adaptées aux besoins métier :
  - Carte géographique pour la répartition territoriale
  - Graphique Sankey pour le classement dynamique par année
  - Barres empilées pour les taux d'acceptation/refus

---

## Résultat

Le dashboard permet aux managers d'identifier en un coup d'œil les agences avec les taux d'acceptation les plus bas — par exemple Quimper à **64,71%** contre Rennes à **81,48%** — et d'orienter les actions correctives en priorité.

---

## Aperçu du Dashboard

![Dashboard Crédit Breton](visualisation%20projet.png)
---

## Outils utilisés

| Outil | Usage |
|-------|-------|
| Power BI Desktop | Création du dashboard et des visualisations |
| DAX | Mesures calculées et KPI |
| Power Query | Nettoyage et transformation des données |
| Excel | Préparation des données sources |

---

## Structure du projet

```
dashboard-credit-breton-powerbi/
│
├── README.md
├── screenshot/
│   └── dashboard.png
└── data/
    └── dataset.xlsx
```

---

## Compétences démontrées

`Power BI` `DAX` `Power Query` `Modélisation de données` `Data Visualisation` `Analyse de performance` `KPI`

---

*Projet réalisé dans le cadre de ma formation en Business Intelligence – OpenClassrooms*  
*Portfolio : en cours de construction*
