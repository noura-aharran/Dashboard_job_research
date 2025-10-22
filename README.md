# 💼 JobPath Dashboard – Visualisation des offres d’emploi au Maroc

##  Description générale
Ce projet présente un **tableau de bord web interactif** développé en **HTML, CSS, JavaScript et Python**, permettant de visualiser et d’analyser les **offres d’emplois au Maroc** dans plusieurs domaines du numérique :  
**Big Data, Data Science, Intelligence Artificielle, Analyse de données, IT, Machine Learning, etc.**

L’application affiche les données sous forme de **tableaux dynamiques** et d’une **carte interactive du Maroc**, localisant les offres par ville.



##  Objectifs du projet
- Centraliser plusieurs fichiers JSON d’offres d’emploi (Data, IA, IT, etc.).
- Fournir une **visualisation géographique** (par ville et région du Maroc 🗺️).
- Permettre une **analyse thématique** selon le domaine, les compétences ou le type de poste.
- Offrir une interface web simple et responsive pour la consultation des offres.


## Technologies utilisées
- **HTML5 / CSS3 / JavaScript** → Interface utilisateur et visualisation.  
- **MapBox.js** → Carte interactive du Maroc (localisation des offres).  
- **Python 3 (Page.py)** → Préparation ou fusion des fichiers JSON.  
- **JSON** → Format de stockage des offres d’emploi.  

## Carte du Maroc – Visualisation
La carte permet de :
- Afficher les **villes avec leurs coordonnées GPS** issues de `Entreprises.json`.  
- Ajouter des **marqueurs dynamiques** selon le domaine (Data, IT, IA…).  
- Cliquer sur un marqueur pour afficher les détails : poste, entreprise, lien, salaire.  

## Données JSON – Exemple
Exemple d’une offre dans `Data_science.json` :

```json
{
  "id": "DS-001",
  "titre": "Data Scientist",
  "entreprise": "InnovaTech",
  "ville": "Casablanca",
  "type": "CDI",
  "competences": ["Python", "Machine Learning", "SQL"],
  "latitude": 33.5731,
  "longitude": -7.5898,
  "salaire": "12k–15k MAD",
  "lien": "https://innova.ma/jobs/ds001"
}

