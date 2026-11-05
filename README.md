# 🐍 Python en IA — Segmenter les clients d'*Amora Zone*

Séance pratique du MBA Data & IA (EFAP · dmb).
*Amora Zone* est une entreprise française (fictive pour ce cours) de cosmétiques naturels : produits de soin et ingrédients pour cosmétiques faits maison, vendus dans ses boutiques et sur son site e-commerce.

Au programme : les fondamentaux de Python ; puis, à partir d'un vrai fichier de commandes, la segmentation des clients avec un k-means ; enfin, un tour de la boîte à outils Python de l'IA (pandas, NumPy, Plotly, Folium, Prophet).

## ▶️ Ouvrir les notebooks (rien à installer)

| Partie | Contenu | Ouvrir |
|---|---|---|
| **Partie 1 · Les fondamentaux** | Première ligne de code, types de données, variables et mémoire du notebook, texte, listes, dictionnaires, conditions, boucles | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SAMIMZOUGHI/MBADMB_python/blob/main/notebooks/partie1_fondamentaux.ipynb) |
| **Partie 2 · Segmentation** | Charger et explorer les commandes, passer aux clients (RFM), k-means pas à pas, personas et plan d'action | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SAMIMZOUGHI/MBADMB_python/blob/main/notebooks/partie2_segmentation.ipynb) |
| **Partie 3 · La boîte à outils** | pandas (le temps, les tableaux croisés), NumPy (vitesse, simulation), Plotly (graphiques interactifs), Folium (cartes), Prophet (prévision, en bonus) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SAMIMZOUGHI/MBADMB_python/blob/main/notebooks/partie3_boite_a_outils.ipynb) |

1. Clique sur le bouton **Open in Colab** de la partie (connecte-toi avec un compte Google).
2. Dans Colab : **Fichier → Enregistrer une copie dans Drive**. Tu travailles sur TA copie.
3. Exécute les cellules une par une avec **Maj + Entrée**.

## 📁 Contenu du dépôt

| Fichier | Description |
|---|---|
| `notebooks/partie1_fondamentaux.ipynb` | Partie 1 : les bases de Python |
| `notebooks/partie2_segmentation.ipynb` | Partie 2 : pandas, RFM, k-means |
| `notebooks/partie3_boite_a_outils.ipynb` | Partie 3 : pandas, NumPy, Plotly, Folium, Prophet |
| `data/commandes.csv` | 4 475 commandes sur 2 ans (une ligne par commande) : client, date et heure, canal, ville et coordonnées, catégorie, nombre d'articles, code promo, montant |

> Les données sont **fictives**, générées pour le cours.

## 📚 Pour continuer à apprendre
- [microsoft/Data-Science-For-Beginners](https://github.com/microsoft/Data-Science-For-Beginners)
- [microsoft/ML-For-Beginners](https://github.com/microsoft/ML-For-Beginners)
- [jakevdp/PythonDataScienceHandbook](https://github.com/jakevdp/PythonDataScienceHandbook)
- [guipsamora/pandas_exercises](https://github.com/guipsamora/pandas_exercises)
- [Documentation du k-means (scikit-learn)](https://scikit-learn.org/stable/modules/clustering.html#k-means)
