# 📘 Data Science School 2025

This repository contains a collection of my projects completed during the **Data Science School 2025** program by AI House. Each project is implemented in a separate Jupyter Notebook and demonstrates practical applications of data science — from data preprocessing and visualization to machine learning and geospatial analysis.

---

## 📂 Notebooks

| Notebook | Description |
|----------|-------------|
| `Data_Science_School_Lviv_Geo_Data_Visualization.ipynb` | Geospatial data analysis and visualization of Lviv using OSMnx, GeoPandas, and NetworkX for route generation and spatial insights. |
| `Data_Science_School_Planet_Dataset_Models.ipynb` | Satellite data modeling from the Planet dataset, using regression algorithms (Random Forest, KNN) to make predictions based on Earth observation data. |
| `Data_Science_School_Titanic_Dataset_Models.ipynb` | Classic Titanic survival prediction using supervised learning — logistic regression, random forest, and gradient boosting models with feature preprocessing. |
| `Data_Science_School_Wine_Dataset_Unsupervised_Models.ipynb` | Clustering of wines using PCA, KMeans, DBSCAN; dimensionality reduction and unsupervised learning techniques on a well-known chemical dataset. |
| `Data_Science_School_E_commerce_Customer_Behavior_Dataset.ipynb` | Customer behavior analysis using e-commerce dataset. Exploratory data analysis (EDA), segmentation, and machine learning for behavior prediction and business insight. |

---

## 🛠️ Technologies & Libraries

### 🔧 Core Libraries
- Python 3.x
- `pandas`, `numpy`

### 📊 Data Visualization
- `matplotlib`
- `seaborn`
- `mpl_toolkits.mplot3d` (3D plots)

### 🧠 Machine Learning
- `scikit-learn`
  - Models: `LogisticRegression`, `RandomForestClassifier`, `GradientBoostingClassifier`, `KNeighborsRegressor`, `RandomForestRegressor`, `KMeans`, `DBSCAN`
  - Evaluation: `classification_report`, `confusion_matrix`, `accuracy_score`, `mean_squared_error`, `r2_score`, `mean_absolute_error`, `silhouette_score`
  - Preprocessing: `LabelEncoder`, `StandardScaler`, `train_test_split`
  - Dimensionality Reduction: `PCA`
  - Pipelines: `Pipeline`

### 🌍 Geospatial & Graph Analysis
- `osmnx`
- `geopandas`
- `shapely`
- `networkx`
- `folium` *(optional for map visualization)*

### 🧩 Utilities
- `random`
- `itertools` (`islice`, `permutations`)

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your_username/data-science-school-2025.git
cd data-science-school-2025
jupyter notebook
