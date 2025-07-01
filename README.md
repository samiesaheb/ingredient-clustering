# 🧪 Ingredient Clustering Explorer

Cluster and visualize cosmetic product formulations based on their INCI ingredient lists using TF-IDF, KMeans, and UMAP.

## 📌 Project Overview

This project uses unsupervised learning to group similar cosmetic product formulations based on their ingredient profiles. It helps uncover formulation trends, hidden product groupings, and common ingredient clusters.

### 🚀 Features
- TF-IDF vectorization of ingredient lists
- KMeans clustering (k=10 optimized via silhouette scores)
- UMAP dimensionality reduction for 2D visualization
- Cluster-wise top ingredient analysis
- CSV export of clustered data

## 📁 Files
- `ingredient_clustering_explorer.ipynb` – Full notebook with analysis
- `formulations_cleaned.csv` – Dataset (not included publicly)
- `clustered_formulations.csv` – Cluster-labeled output
- `requirements.txt` – Python dependencies

## ▶️ How to Run

1. Clone this repository:

```bash
git clone https://github.com/yourusername/ingredient-clustering.git
cd ingredient-clustering
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Launch the notebook:

```bash
jupyter notebook ingredient_clustering_explorer.ipynb
```

4. Or run it in VSCode, JupyterLab, etc.

## 📦 Dependencies

See `requirements.txt`. Key packages:

- pandas, numpy
- scikit-learn
- umap-learn
- matplotlib, seaborn

## 🧪 Example Use Case

> “Show me what types of product formulations tend to group together based on ingredient similarity.”

## 📬 Contact

Built by [Your Name] at Sky High International Co., Ltd.  
For questions, email: [your-email@example.com]

