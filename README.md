# Typologie et prévision des ventes de magasins

**Outil** : Python (pandas, scikit-learn, Prophet) · **Projet 10** · ToutParapharma

**Objectif** : identifier les types de magasins pour mieux prévoir les ventes.

**Démarche**
- Fiabilisation : 935 magasins retenus sur 1 115 (séries complètes)
- Analyse de la série : pic en décembre (+17 %), creux en octobre (-5 %)
- K-means : 4 profils de magasins
- Prévision : moyenne mobile contre Prophet

**Résultats**
- 4 profils : panier élevé, concurrence proche, forte concurrence avec promos, magasins isolés
- Prophet divise l'erreur de prévision par 3 (de 2 404 € à 720 € d'écart moyen par jour, magasin 871)

**Recommandations**
- Adapter les actions à chaque profil : communication, assortiment, promos ciblées, budget promo
- Anticiper les approvisionnements avec les prévisions Prophet

**Compétences** : KPI, mesure de la performance, recommandations

**Fichiers** : `P10_notebook_112026.ipynb`, `P10_presentation_112026.pptx`
