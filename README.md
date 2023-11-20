
![Alt text](logo-1.PNG)


# OPTIMISER LA GESTION DES DONNEES D'UNE BOUTIQUE AVEC PYTHON

Projet realisé en février 2023 dans le cadre de ma formation Data Analyst avec OpenClassrooms.

## Objectif du projet

Bottleneck est un marchand de vin très prestigieux. 
Actuellement, pour gérer ses ressources, ses clients, etc., la societe utilise un ERP qui n’est absolument pas relié à son site de vente en ligne. Les outils en place sont vraiment artisanaux et dans ces conditions, la
gestion des stocks est complexe et la visibilité en termes d’analyse des ventes en ligne limitée, car très peu de personnes ont accès au back-office. En attendant une solution plus centralisée, un rapprochement
entre les 2 bases, même manuel, est requis et il doit s'articuler autour de 3 missions principales:

* **Rapprocher deux exports :** un export de l’ERP
contenant les références produit, leur prix de vente et leur état de stock, et un export d’une table de l’outil de CMS contenant les informations des produits
commercialisés en ligne (nom, description, nombre de ventes...). L’export issu de la boutique en ligne contient le nombre de ventes pour chaque produit depuis sa mise en ligne, il ne permet pas d’analyser l'évolution des ventes dans le temps. En plus de ces 2 exports, l'ancienne stagiaire a créé un tableau Excel qui permet d’établir le lien entre la référence du produit dans l’ERP
(product_id) et la référence du même produit dans la base de la boutique en ligne (SKU);
* **Calculer le chiffre d'affaires :** une fois le rapprochement effectué, le chiffre d’affaires par produit, ainsi que le total du chiffre d’affaires réalisé en ligne doivent etre calcules; et enfin
* **Detecter et corriger des erreurs de saisie :**
Il semble qu'il y ait des erreurs de saisie dans certains prix des produits.Il convient donc d'effectuer une analyse
sur cette variable afin de détecter d’éventuelles valeurs aberrantes, de les lister et d’en faire une représentation graphique pour plus de lisibilité.

Une présentation par slides n'est pas requise pour ce projet, seul le notebook est a présenter. 


## Liste des dossiers & fichiers

* **dossiers :**
  - **donnees-brutes :** fichiers téléchargés depuis les sources (format .xslx) 


* **fichiers :**
	- **notebook.ipynb :** code Python permettant l'import des fichiers .csv, leur nettoyage et la production des analyses statistiques et graphiques
  - **presentation_notes.pdf :** notes d’accompagnement des diapositives de présentation du projet


## Compétences développées

* Réaliser une analyse univariée pour interpréter des données
* Classifier différents types de données
* Gérer les erreurs et les incohérences présentes sur des données stockées



## Langages & software

* Python 3.9.13
  * matplotlib 3.6.2
  * missingno 0.5.1
  * numpy 1.24.1
  * pandas 1.5.2
  * seaborn 0.12.2
  

* Jupyter Notebook 6.4.12








