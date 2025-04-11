# Market Segmentation using K-Means Clustering

This project performs customer segmentation on McDonald's data using **K-Means Clustering**.

## Overview

Binary preference data (Yes/No) was converted into numerical format (1/0) and analyzed using K-Means for segment sizes from 2 to 8.

## Key Steps

- **Scree Plot**: Visualized within-cluster sum of squares to explore the optimal number of segments.
- **Stability Analysis**: Used bootstrapping and **Adjusted Rand Index (ARI)** to assess how consistent clusters are across resamples.
- **Boxplots**: Displayed clustering stability for each segment count.
- **Segment-Level Insights**: Evaluated how individual segments change as the number of clusters increases.

## Files

- `mcdonalds_data.csv`: Input dataset
- `market_segmentation.ipynb`: Main Python script
- `README.md`: Summary of the project

## Conclusion

K-Means clustering helped identify customer segments, and stability analysis guided the choice of the most reliable segmentation solution.
