# Adv-Dm-clustering-2

This repository offers a pproach for segmenting Starbucks customers according to their purchasing behaviors at different times of the day. This segmentation helps the Starbucks store manager promotions to improve sales.

Data:
The dataset comprises sales data of hot beverages during peak times on Wednesday.

PTIndex: Ranges from 1 (6 am - 7 am) to 11 (8 pm - 9 pm).
HBIndex: Ranges from 1 (Coffee type 1) to 9 (Coffee Of the Day).

Methodology:

KMeans Clustering:
Apply KMeans clustering to segment the data.

Hierarchical Clustering:
Visualize dendrograms for Single Linkage, Complete Linkage, and Average Linkage.
Apply hierarchical clustering for each linkage method and visualize the resultant clusters.
Recommendations Generation: Generate tailored promotions based on the formed clusters to cater to each customer segment.

Results:
1. Single Linkage: Produced one dominant cluster with a few outliers, suggesting a broad customer behavior with minor variations.
2. Complete Linkage: Yielded distinct and balanced clusters, providing clear insights into varied customer behaviors.
3. Average Linkage: Offered a balanced perspective with clusters representing slightly different behaviors compared to Complete Linkage.

KMeans: 
Revealed three distinct customer segments, each exhibiting diverse purchasing behaviors at different times of the day.
Single Linkage: Produced one dominant cluster with a few outliers, indicating broad customer behavior with minor variations.
Complete Linkage: Generated distinct and balanced clusters, offering clear insights into various customer behaviors.
Average Linkage: Provided a balanced perspective with clusters representing slightly different behaviors compared to Complete Linkage.
