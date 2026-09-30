# TP Optimisation — 7 méthodes en NumPy

Implémentation **from scratch** de 7 méthodes d'optimisation en NumPy pur,
comparées sur trois exercices de la fiche TP.

---

## Description

Ce projet implémente et compare les méthodes suivantes :

- **GD** — Descente de gradient (lot complet)
- **GD + LS** — GD avec recherche du pas optimal
- **SGD** — Descente de gradient stochastique (mini-lots)
- **Momentum** — SGD avec inertie
- **AdaGrad** — Pas adaptatif par coordonnée
- **RMSprop** — Moyenne glissante des carrés
- **Adam** — Momentum + RMSprop + correction de biais

Aucune bibliothèque d'optimisation préfabriquée (scikit-learn, PyTorch,
TensorFlow) n'est utilisée. Tous les gradients sont codés manuellement
et vérifiés par différences finies centrées.

---

## Les 3 exercices

| Exercice | Fichier | Problème |
|---|---|---|
| **Exercice 1** | `regression_nonlinear.csv` | Régression (OLS, Ridge, Ridge RBF) |
| **Exercice 2** | `classification_spiral3.csv` | Classification multiclasse (MLP 2→32→16→3) |
| **Exercice 3** | `clustering_blobs3.csv` | Clustering (soft K-means) |

---

## Structure du projet
