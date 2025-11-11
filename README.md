# Human Activity Recognition – Clustering Analysis

This project explores **unsupervised learning methods** for human activity recognition using sensor data. We focus on clustering techniques to discover patterns in labeled activity data and evaluate how well clusters match the true activity classes.


---

## 🧠 Methods

We apply **KMeans clustering** and **DBSCAN** with/without dimensionality reduction techniques:

1. **Dimensionality Reduction (DR):**
   - PCA
   - t-SNE
   - UMAP

2. **Clustering:**
   - KMeans (baseline and with DR)
   - DBSCAN

3. **Evaluation:**
   - Confusion matrix
   - Accuracy
   - Precision, Recall, F1-score (per activity)
   - Macro F1-score
   - Silhouette score for cluster quality

---

## 📊 Results

- Visualizations of DR projections and clusters.
- Confusion matrices showing correspondence between clusters and true activity labels.
- Numeric evaluation metrics printed in the console and saved in `results/`.

---

## ⚙️ Usage

1. Clone the repository:
```bash
git clone https://github.com/rayaneplay/human_activity_recognition.git
cd human_activity_recognition

