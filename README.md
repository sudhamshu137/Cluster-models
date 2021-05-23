# Cluster-models
Application of k-means clustering and heirarchial clustering on the dataset given
</br>
Building the clustering models such as k-means clustering model and heirarchial clustering model on the dataset containing the income of customers and spending money.</br>
This dataset is then divided into 5 types that are
- People with high income spending very high
- People with high income spending very less
- People with low income spending very high
- People with low income spending very low
- People with medium income spending in a medium level
</br>
This was the result obtained by both the models.
</br>
![Final result](data:image/png;base64,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)
