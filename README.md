# Analyse de Sentiments Twitter - Élection Présidentielle Américaine 2020

## 📖 Description

Ce projet présente une analyse approfondie des données Twitter relatives à l'élection présidentielle américaine de 2020, en se concentrant sur les mentions de Joe Biden et Donald Trump. À travers des techniques de traitement du langage naturel (NLP) et de visualisation de données, ce projet explore les sentiments, les tendances géographiques et temporelles des discussions politiques sur Twitter.

**Projet réalisé dans le cadre de la spécialisation en Analyse d'affaires TI à HEC Montréal (2020)**

## 🎯 Objectifs du Projet

- Analyser les sentiments exprimés dans les tweets mentionnant les candidats présidentiels
- Créer des visualisations innovantes des données textuelles (nuages de mots personnalisés)
- Examiner la distribution géographique des mentions par état américain
- Étudier l'évolution temporelle de l'engagement sur Twitter
- Comparer les plateformes d'utilisation (iPhone, Android, Web)

## 🛠️ Technologies Utilisées

- **Python** - Langage principal
- **Pandas** - Manipulation et analyse des données
- **NLTK** - Traitement du langage naturel
- **WordCloud** - Génération de nuages de mots
- **Matplotlib & Seaborn** - Visualisation statistique
- **Plotly** - Cartes choroplèthes interactives
- **PIL (Pillow)** - Traitement d'images pour les masques

## 📊 Fonctionnalités Principales

### 1. Préparation des Données
- Chargement et fusion des datasets Twitter pour Biden et Trump
- Nettoyage des données (suppression des doublons, conversion des types)
- Identification des tweets mentionnant les deux candidats

### 2. Analyse Textuelle
- **Nettoyage du texte** : Suppression des mentions, URLs, caractères spéciaux
- **Tokenisation** : Découpage des tweets en mots individuels
- **Lemmatisation** : Réduction des mots à leur forme canonique
- **Suppression des mots vides** : Filtrage des mots non-significatifs

### 3. Visualisations Créatives
- **Nuages de mots personnalisés** : Utilisation de masques représentant les visages des candidats
- **Graphiques temporels** : Évolution du nombre de tweets et likes par jour
- **Cartes choroplèthes** : Distribution géographique des mentions par état américain
- **Analyses comparatives** : Visualisations côte-à-côte des résultats

### 4. Analyses Géographiques
- Cartes de chaleur par état pour chaque candidat
- Identification du candidat dominant par état selon les likes
- Analyse de la distribution par continent

### 5. Analyses Comportementales
- Comparaison des plateformes utilisées (iPhone vs Android vs Web)
- Analyse de l'engagement (likes, retweets) par candidat

## 📁 Structure du Projet

```
analyse-sentiments-twitter-presidentielle-2020/
├── Projet_final.ipynb           # Notebook Jupyter principal
├── README.md                    # Ce fichier
├── data/
│   ├── hashtag_joebiden.csv     # Dataset des tweets Biden
│   └── hashtag_donaldtrump.csv  # Dataset des tweets Trump
└── assets/
    ├── joebiden_mask.png        # Masque pour nuage de mots Biden
    └── donaldtrump_mask.png     # Masque pour nuage de mots Trump
```

## 🚀 Installation et Utilisation

### Prérequis
```bash
pip install pandas numpy nltk matplotlib seaborn plotly wordcloud pillow
```

### Configuration NLTK
```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')
nltk.download('wordnet')
```

### Exécution
1. Cloner le repository
2. Installer les dépendances
3. Placer les fichiers de données dans le dossier `data/`
4. Exécuter le notebook Jupyter `Projet_final.ipynb`

## 📈 Résultats Clés

- **Nuages de mots distinctifs** : Identification des termes les plus associés à chaque candidat
- **Tendances temporelles** : Pics d'activité selon les événements politiques
- **Répartition géographique** : Cartographie des préférences par état
- **Analyse des plateformes** : Différences d'usage entre iPhone, Android et Web

## 🎓 Contexte Académique

Ce projet a été développé dans le cadre du programme de spécialisation en **Analyse d'affaires TI** à **HEC Montréal** en 2020. Il démontre l'application pratique des techniques d'analyse de données et de business intelligence dans le contexte de l'analyse des médias sociaux et de l'opinion publique.

### Compétences Développées
- Traitement et analyse de données massives
- Techniques de NLP appliquées aux médias sociaux
- Visualisation de données géospatiales
- Création de tableaux de bord interactifs
- Analyse de sentiments et d'opinions

## 📝 Remarques Techniques

- Le projet utilise des masques d'images personnalisés pour créer des nuages de mots en forme de visages
- Les cartes choroplèthes permettent une visualisation intuitive des données géographiques
- L'analyse temporelle révèle les patterns d'engagement selon les événements politiques
- Les techniques de NLP garantissent une analyse textuelle robuste et significative

## 📧 Contact

Pour toute question sur ce projet ou collaboration, n'hésitez pas à me contacter.

---

*Projet réalisé en 2020 dans le cadre de la spécialisation en Analyse d'affaires TI - HEC Montréal*