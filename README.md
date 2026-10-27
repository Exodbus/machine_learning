# Machine Learning – Notes de révision

Notebooks de cours (avec images, figures et jeux de données) pour réviser les bases du Machine Learning.

| # | Dossier | Contenu |
|---|---------|---------|
| 1 | [`01-introduction`](01-introduction) | Introduction au ML, supervisé vs non supervisé, fonction de coût, descente de gradient |
| 2 | [`02-practical-aspects`](02-practical-aspects) | Biais/variance, métriques (confusion matrix, ROC/AUC), cross-validation, feature engineering, tuning |
| 3 | [`03-regression`](03-regression) | Régression linéaire, Ridge / Lasso |
| 4 | [`04-classification`](04-classification) | Régression logistique, arbres de décision, méthodes d'ensemble |
| 5 | [`05-clustering`](05-clustering) | K-means, clustering hiérarchique (CAH), comparaison de méthodes |

## Utilisation

Chaque dossier est autonome : le notebook référence `figures/` et `data/` en chemins relatifs, il faut donc l'ouvrir depuis son propre dossier.

```bash
pip install -r requirements.txt
cd 01-introduction
jupyter lab
```

Sur GitHub, les notebooks (`.ipynb`) s'affichent directement dans le navigateur, images comprises.
