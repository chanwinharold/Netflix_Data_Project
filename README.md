📊 Analyse des Données Netflix

📝 Présentation du Projet

Ce projet analyse le dataset Netflix en utilisant Python et des bibliothèques populaires comme Pandas, 
Matplotlib et Seaborn. L'objectif est de nettoyer, explorer et visualiser le dataset afin d'extraire des 
informations pertinentes sur le contenu de Netflix.


## 📊 Objectifs

📌 Objectifs

1. Chargement et Exploration des Données

    📥 Charger le dataset Netflix avec Pandas.
    
    👀 Afficher les 5 premières et 5 dernières lignes du dataset.
    
    📊 Afficher les informations générales du dataset avec .info().
    
    🔍 Identifier les valeurs manquantes et proposer des stratégies pour les traiter.
    
    🔄 Vérifier l'existence de doublons et justifier leur suppression si nécessaire.
    
    📽️ Analyser la distribution des types de contenu (Films vs Séries TV).

2. Nettoyage et Préparation des Données

    📅 Convertir la colonne date_added au format datetime.
    
    🎬 Créer une colonne is_movie (True pour les Films, False pour les Séries TV).
    
    🧹 Remplacer ou supprimer les valeurs manquantes de manière appropriée.
    
    🔠 Standardiser les noms des colonnes (minuscules et sans espaces).
    
    ⏳ Extraire la durée des films en minutes dans une nouvelle colonne duration_minutes.
    
    🗑️ Supprimer les colonnes peu informatives si nécessaire.

3. Analyse Statistique et Manipulation des Données

    🌍 Identifier les 10 pays ayant le plus de films et séries sur Netflix.
    
    📆 Analyser la répartition des films et séries par année de sortie.
    
    🎥 Identifier le réalisateur ayant le plus de films sur Netflix.
    
    ⭐ Identifier les 5 acteurs les plus présents dans le catalogue Netflix.
    
    📚 Déterminer les genres de contenu les plus fréquents.
    
    ⌛ Calculer la durée moyenne des films en minutes.
    
    📊 Évaluer la proportion de contenu classé "TV-MA" par rapport aux autres classifications.
    
    📈 Déterminer la proportion de films par rapport aux séries TV.
    
    📺 Identifier les 5 pays qui produisent le plus de séries TV sur Netflix.

4. Visualisation des Données

    📊 Tracer un histogramme de la répartition des années de sortie.
    
    📊 Créer un graphique en barres du top 10 des pays ayant le plus de contenus.
    
    🥧 Afficher un diagramme circulaire (pie chart) des classifications d'âge.
    
    📊 Montrer un graphique en barres du nombre de films/séries par catégorie.
    
    🔎 Créer un scatterplot de la durée des films en fonction de leur année de sortie.
    
    📈 Tracer un graphique en courbe de l'évolution du nombre de contenus ajoutés sur Netflix.
    
    📦 Afficher un boxplot de la durée des films en fonction de leur classification d'âge.

5. Conclusion et Interprétation

    🌐 Quels sont les principaux pays producteurs de contenus sur Netflix ?
    
    📊 Y a-t-il une tendance dans l'ajout de nouveaux contenus au fil du temps ?
    
    🔞 Quelle est la classification d'âge la plus fréquente sur Netflix ?
    
    📏 La durée des films varie-t-elle en fonction de leur année de sortie ?
    
    📚 Quels sont les genres de contenu les plus populaires sur Netflix ?



## 📁 Structure du Projet

```
├── data/                   # Dossier contenant le dataset
├── notebooks/              # Notebooks Jupyter pour l'analyse
├── resultats/              # Page Web contenant les conclusions et interprétations de l'analyse
├── README.md               # Documentation du projet
└── requirements.txt        # Dépendances du projet
```

## 🛠️ Prérequis

Assurez-vous d'avoir Python installé sur votre machine. Créez un environnement virtuel et installez les dépendances :

```bash
python -m venv venv
source venv/bin/activate  # Sur Windows : .\venv\Scripts\activate
pip install -r requirements.txt
```

## 📊 Exécution du Projet

1. Lancez un notebook Jupyter pour explorer le dataset :

```bash
jupyter notebook
```

2. Exécutez les différentes étapes d'analyse dans l'ordre :
   - Chargement et exploration
   - Nettoyage des données
   - Analyse statistique
   - Visualisation

🔮 Améliorations Futures

    📊 Ajouter des visualisations interactives avec Plotly.
    
    🤖 Intégrer des modèles de machine learning pour prédire les tendances.
    
    🔄 Automatiser la mise à jour du dataset à partir de sources externes.

📜 Licence

    Ce projet est sous licence MIT.

👤 Auteur

    Harold CHANWIN

🙌 Remerciements
    
    📊 Dataset fourni par Kaggle.
    
    🐍 Communauté open-source Python.
