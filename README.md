EDX Dash Project
Présentation
Ce projet propose une analyse comparative exhaustive et interactive des offres de cours en ligne EdX, avec un accent particulier sur les domaines des statistiques, de l’intelligence artificielle, de la programmation et des sciences des données. L’objectif principal est de faciliter l’exploration des données relatives aux prix, à l’effort demandé, au nombre d’inscrits, ainsi qu’aux institutions partenaires, grâce à des tableaux de bord dynamiques et des visualisations synthétiques.​

Fonctionnalités
Exploration interactive des données EdX (notamment prix, effort, sessions, institutions)

Identification des tendances par institution, thématique et catégorie de prix

Visualisations avancées grâce à matplotlib et seaborn (diagrammes, barres, nuages de points)

Scripts SQL intégrés pour requêtes dynamiques sur les données

Classement automatisé des meilleures offres selon différents critères pédagogiques et économiques.​

Installation
Cloner le dépôt :

bash
git clone https://github.com/Smaky2019/EDX_Dash_Proj.git
cd EDX_Dash_Proj
Installer l’environnement python requis :

bash
pip install -r requirements.txt
Démarrer le notebook :

bash
jupyter notebook EDX_Dash_Proj.ipynb
Adapter la configuration éventuelle de la base SQLite ou csv selon vos données sources.

Utilisation
Ouvrir le notebook dans Jupyter pour une exploration interactive.

Modifier les requêtes SQL pour des analyses ciblées selon vos besoins.

Générer les graphiques voulus pour présentation ou publication.

Les grandes sections du notebook permettent d’effectuer des analyses sur la difficulté des cours, le coût, le volume d’inscription par institution et la comparaison entre différents domaines (Sciences, IA, Data Science…).​

Pré-requis
Python 3.8+

Jupyter Notebook

Pandas, Matplotlib, Seaborn, sqlite3

Base de données EdX exportée au format SQLite ou CSV

Auteur
Projet développé et documenté par Udemy. Merci de mentionner toute contribution ou suggestion dans la section Issues du repository.

License
Ce projet est distribué sous licence MIT (ou autre au choix).

Contribuer
Toute contribution est la bienvenue. Veuillez ouvrir une issue ou proposer une pull request pour soumettre vos améliorations (corrections de code, nouvelles visualisations, documentation…).
