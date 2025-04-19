# Service Prediction of Medical Facility

This project focuses on classifying patient data and uncovering patterns using machine learning techniques such as **Decision Trees** and **Clustering**. It utilizes a healthcare dataset (`quality.csv`) with various patient attributes to predict certain outcomes and visualize important decision-making features.

## 🧠 Project Highlights

- **Classification using Decision Trees** (Scikit-learn)
- **Clustering using KMeans & DBSCAN**
- **Correlation Analysis with Heatmap**
- **Feature Importance Visualization**
- Clean visualizations for model interpretability

---

## 📁 Files in this Repository

| File | Description |
|------|-------------|
| `DEC_Mini_Project(2).ipynb` | Main Jupyter Notebook performing decision tree classification, evaluation, and visualizations. |
| `clustering.ipynb` | Contains KMeans and DBSCAN clustering implementation and evaluation. |
| `quality.csv` | Dataset containing anonymized healthcare records. |
| `tree1.png` | Visualization of the trained Decision Tree. |
| `heatmap_pearson.png` | Correlation heatmap of features. |

---

## 🔧 Technologies Used

- Python 3
- Scikit-learn
- Pandas
- NumPy
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 📊 Key Results

- Decision Tree achieved significant interpretability with key features like `TotalVisits`, `Narcotics`, and `MedicalClaims`.
- Clustering revealed patient groups based on shared health behavior and claim profiles.
- Correlation analysis provided insights into feature relationships.

---

## 🧩 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/medical-ml-analysis.git
   cd medical-ml-analysis
