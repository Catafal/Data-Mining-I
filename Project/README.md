- Preprocessing:
    - Data Cleaning (outliers, missing values, format...)
    - Sampling 
    (In sintesi, bilanciare le classi (es. sampling 50/50) non ha molto senso quando si esegue un algoritmo di clustering, perché il clustering è un metodo non supervisionato che non tiene conto della variabile target. Alterare la distribuzione naturale dei dati potrebbe addirittura peggiorare i risultati del clustering. È più utile eseguire il clustering senza cambiare il dataset e poi osservare come la variabile target si distribuisce tra i cluster trovati.)



- Feature selection:
    - Correlation Analysis for qualitative (pearson)
    - Association Analysis for quantitative (chi quadrat)
    - remove redundant features
    - Remove irrelevant variables
    - Scaling
    - PCA

- Clustering
    - Chamaleon (?)
    - Kmeans
    - Hierarchical
    - (check another advanced method)

- Check cluser validity (correlation, similarity matrix)