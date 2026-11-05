# 🐍 Python en IA — Des fondamentaux aux librairies, avec *Amora Zone*

Séance pratique du MBA Data & IA (EFAP · dmb).
*Amora Zone* est une entreprise française (fictive pour ce cours) de cosmétiques naturels : produits de soin et ingrédients pour cosmétiques faits maison, vendus dans ses boutiques et sur son site e-commerce.

Le cours a **deux parties** : les fondamentaux de Python, puis les librairies de l'IA (pandas, NumPy, Plotly ; Folium et Prophet en option), sur un vrai fichier de commandes. Une **annexe** va plus loin, jusqu'au machine learning (k-means).

## ▶️ Ouvrir les notebooks (rien à installer)

| Partie | Contenu | Ouvrir |
|---|---|---|
| **Partie 1 · Les fondamentaux** | Première ligne de code, types de données, variables et mémoire du notebook, texte, listes, dictionnaires, conditions, boucles | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SAMIMZOUGHI/MBADMB_python/blob/main/notebooks/partie1_fondamentaux.ipynb) |
| **Partie 2 · La boîte à outils** | pandas (le temps, les regroupements, les tableaux croisés), NumPy (calculs rapides), Plotly (graphiques interactifs) ; Folium (cartes) et Prophet (prévision) en optionnel | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SAMIMZOUGHI/MBADMB_python/blob/main/notebooks/partie2_boite_a_outils.ipynb) |
| **Annexe · Segmentation k-means** | Hors cours : passer des commandes aux clients (RFM), k-means pas à pas, personas et plan d'action | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SAMIMZOUGHI/MBADMB_python/blob/main/notebooks/annexe_kmeans_segmentation.ipynb) |

1. Clique sur le bouton **Open in Colab** de la partie (connecte-toi avec un compte Google).
2. Dans Colab : **Fichier → Enregistrer une copie dans Drive**. Tu travailles sur TA copie.
3. Exécute les cellules une par une avec **Maj + Entrée**.

## 📁 Contenu du dépôt

| Fichier | Description |
|---|---|
| `notebooks/partie1_fondamentaux.ipynb` | Partie 1 : les bases de Python |
| `notebooks/partie2_boite_a_outils.ipynb` | Partie 2 : pandas, NumPy, Plotly ; Folium et Prophet en option |
| `notebooks/annexe_kmeans_segmentation.ipynb` | Annexe : RFM et k-means |
| `data/database.csv` | 4 475 commandes sur 2 ans (une ligne par commande) : client, date et heure, canal, ville et coordonnées, catégorie, nombre d'articles, code promo, montant |

> Les données sont **fictives**, générées pour le cours.

## 📚 Pour continuer à apprendre
- [microsoft/Data-Science-For-Beginners](https://github.com/microsoft/Data-Science-For-Beginners)
- [microsoft/ML-For-Beginners](https://github.com/microsoft/ML-For-Beginners)
- [jakevdp/PythonDataScienceHandbook](https://github.com/jakevdp/PythonDataScienceHandbook)
- [guipsamora/pandas_exercises](https://github.com/guipsamora/pandas_exercises)
- [Documentation du k-means (scikit-learn)](https://scikit-learn.org/stable/modules/clustering.html#k-means)
