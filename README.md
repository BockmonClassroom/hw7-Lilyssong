# HW7
Take the code that was written in class for K-means and make it work for a 3D data sets. Using the Spotify_ YouTube.csv data set, read in the following three columns: Liveness, Energy, Loudness. Using an elbow graph, find the optimal number of K and use that to visualize the data and groups based on that K. Graphs should be appropriately labeled with an x, y, and z axis along with a title and legend. Then write what your results might mean to you.

Then, take each of the individual columns and run hierarchical clustering on them. Are there any? distinct groups. If so, how would you define each group? Graphs should be appropriately labeled. Then write what your results might mean to you.

Grading (Out of 100 points)
• 70 points: Cover what you did to update the code to work for 3D data and visualization along with what number of K you found to be optimal and the graphs showing the results of running K-means and what your results mean.
• 30 points: Report your findings for running Hierarchical clustering.

How to turn in
Turn in the final report and code that you wrote to Githbub


# 🎵 HW7 - Clustering Analysis with Spotify-YouTube Data

This project explores clustering techniques (K-Means and Hierarchical Clustering) on 3D musical features from the Spotify-YouTube dataset.

## 📁 Dataset

Used features:
- `Liveness`
- `Energy`
- `Loudness`

Source: `data/Spotify_Youtube.csv`

---

## 📌 Task Summary

1. **Preprocessing**: Cleaned and standardized the selected features.
2. **K-Means Clustering**:
   - Used the elbow method to find the optimal number of clusters (K=4).
   - Visualized results in a 3D scatter plot.
3. **Hierarchical Clustering**:
   - Applied Ward linkage.
   - Visualized using both dendrogram and 3D scatter plot.

---

## 📈 Visualizations

- Elbow plot (to select K)
- 3D K-Means clustering result
- Dendrogram (hierarchical structure)
- 3D Hierarchical clustering result

---

## 📊 Interpretation

Clusters identified meaningful groupings in songs with similar loudness, energy, and liveness traits. This can be useful for music classification, playlist curation, or recommendation systems.

See the notebook `HW7_KMeans_Hierarchical_Clustering.ipynb` for full analysis and visualizations.

---

## 🚀 How to Run

```bash
pip install pandas matplotlib scikit-learn scipy
