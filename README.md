# Conception d'un Panneau Photovoltaïque Mural avec Dispositif Suiveur Solaire

**Rapport de Projet de Fin d'Année**  
**2ᵉ Année Génie Mécanique**  
**École Nationale d'Ingénieurs de Tunis (ENIT)**  
**Université de Tunis El Manar**  
**Année universitaire : 2025/2026**

**Réalisé par :**  
- Snoussi Syrine Sara  
- Taamallah Haithem  

**Encadré par :**  
M. Jemmali Mohamed

## 📌 Contexte du projet

Ce projet vise à concevoir un **panneau photovoltaïque mural** destiné à l’autoconsommation, équipé d’un **dispositif suiveur solaire à un axe** permettant d’optimiser l’orientation du panneau tout au long de la journée afin de maximiser la quantité d’énergie solaire récupérée.

## 🎯 Objectifs principaux

- Étudier le contexte énergétique tunisien et le fonctionnement des cellules photovoltaïques
- Modéliser géométriquement la trajectoire solaire et calculer l’angle d’incidence
- Développer un code Python pour simuler l’irradiance et l’énergie annuelle récupérable selon différentes inclinaisons fixes et suiveuses
- Concevoir mécaniquement un suiveur à un axe actionné par vérin électrique (modélisation CAO sous CATIA V5)
- Dimensionner les composants et valider la cinématique du mécanisme

## 🗂 Structure du dépôt


## 📊 Contenu détaillé du rapport

### 1. Contexte et problématique
- Situation énergétique actuelle en Tunisie
- Structure et fonctionnement d’une cellule PV
- Effet de l’angle d’incidence sur la production

### 2. Modélisation et simulation numérique
- Modèle géométrique du mouvement solaire (déclinaison δ, angle horaire ω)
- Calcul de l’angle d’incidence θ
- Algorithme Python + validation des résultats
- Comparaison énergie annuelle : fixe vs suiveur (différentes valeurs de β)

### 3. Conception mécanique du suiveur
- Choix du type de suiveur : 1 axe (rotation β)
- Solutions cinématiques étudiées :
  - Moteurs / accouplements
  - Crémaillère-pignon
  - Poulies-courroies
  - **Vérin électrique + biellettes** (solution retenue)
- Dimensionnement global du panneau et du mécanisme
- Modélisation 3D détaillée sous CATIA V5
- Vues éclatées, assemblages, jeux fonctionnels

## 🛠 Technologies & Outils utilisés

- **CAO** : CATIA V5  
- **Programmation** : Python (numpy, matplotlib, calculs astronomiques)  
- **Concepts clés** : Rayonnement direct / diffus, suivi solaire, cinématique, dimensionnement mécanique

## Aperçu visuel du projet

<!-- Tu peux remplacer par tes vraies images quand tu les uploades -->

<p align="center">
  <img src="figures/schema-global-systeme.png" alt="Schéma global du système" width="600"/>
  <br><em>Schéma global du panneau avec suiveur à 1 axe</em>
</p>

<p align="center">
  <img src="figures/solution-catia.png" alt="Modélisation CATIA" width="600"/>
  <br><em>Assemblage 3D final sous CATIA</em>
</p>

<p align="center">
  <img src="figures/panneau-journee.png" alt="Panneau en cours de journée" width="600"/>
  <br><em>Position du panneau au cours de la journée</em>
</p>


