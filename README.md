# Prediction-Prix-TV
Modèle d'apprentissage basé sur KNN et NB pour prédire le prix d'un article (TV) en fonction de ses caracteristiques

# Données d'apprentissages 
Ce tableau comprend 20 modèles de téléviseurs avec leurs caractéristiques correspondantes, y compris la taille, le poids, la résolution et le prix en FCFA (Franc CFA). 
+------------------+--------+-------+---------+-----------+
|   Modèle TV      | Taille | Poids | Résolution | Prix (FCFA)|
+------------------+--------+-------+------------+-----------+
|   TV 1           |  55''  | 20 kg |   2160     |   800000  |
|   TV 2           |  65''  | 25 kg |   4320     |  1200000  |
|   TV 3           |  43''  | 15 kg |   1080     |   500000  |
|   TV 4           |  32''  | 10 kg |   768      |   250000  |
|   TV 5           |  75''  | 30 kg |   2160     |  1500000  |
|   TV 6           |  50''  | 18 kg |   2160     |   700000  |
|   TV 7           |  55''  | 20 kg |   1080     |   600000  |
|   TV 8           |  43''  | 15 kg |   2160     |   550000  |
|   TV 9           |  65''  | 25 kg |   2160     |  1100000  |
|   TV 10          |  32''  | 10 kg |   768      |   300000  |
|   TV 11          |  40''  | 12 kg |   1080     |    450000 |
|   TV 12          |  55''  | 22 kg |   2160     |    900000 |
|   TV 13          |  48''  | 17 kg |   1080     |    650000 |
|   TV 14          |  70''  | 28 kg |   4320     |   1800000 |
|   TV 15          |  60''  | 23 kg |   2160     |   1000000 |
|   TV 16          |  43''  | 14 kg |   1080     |    550000 |
|   TV 17          |  55''  | 21 kg |   2160     |    950000 |
|   TV 18          |  49''  | 19 kg |   1080     |    700000 |
|   TV 19          |  75''  | 32 kg |   4320     |   2200000 |
|   TV 20          |  65''  | 26 kg |   2160     |   1300000 |
+------------------+--------+-------+------------+-----------+

# Travail à faire:
2.	Réaliser le prétraitement de ces données
3.	Subdiviser l’ensembles des données en données d’entrainement (80%) et en données de test (20%)
4.	Construire un modèle de classification en utilisant l'algorithme de votre choix (Naïve Bayes ou Knn).
5.	Générer la matrice de confusion du modèle de classification construit
6.	Imprimer les rapports de la classification puis évaluer la performance du modèle utilisé.
7.	Utiliser votre modèle pour prédire le prix des TV ci-dessous
+------------------+--------+-------+------------+
|   Modèle TV      | Taille | Poids | Résolution |
+------------------+--------+-------+------------+
|   TV 21          |  58''  | 22 kg |   3840     |
|   TV 22          |  70''  | 27 kg |   7680     |
|   TV 23          |  55''  | 18 kg |   1920     |
|   TV 24          |  48''  | 16 kg |   1366     |
|   TV 25          |  82''  | 35 kg |   3840     |
+------------------+--------+-------+------------+


