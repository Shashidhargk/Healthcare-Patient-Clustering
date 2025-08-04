#Healthcare-Patient-Clustering

Patient clustering in healthcare using symptoms and medical records with PCA, K-Means, Silhouette Score, Davies-Bouldin Index (DBI), and disease group profiling.

📌 Overview
This project clusters patients based on their healthcare data to identify similar disease groups. The pipeline includes:
Data preprocessing (handling null values, standardization)
Dimensionality reduction with PCA
K-Means clustering
Evaluation using Silhouette Score and Davies-Bouldin Index
Cluster profiling to interpret disease groups

🛠️ Technologies Used
Python
pandas
scikit-learn
seaborn
matplotlib

📂 Project Structure

Healthcare-Patient-Clustering/
│── data/
│   └── heart_disease_dataset.csv
│── notebooks/
│   └── patient_clustering.ipynb
│── src/
│   ├── preprocessing.py
│   ├── clustering.py
│   └── evaluation.py
│── README.md
│── requirements.txt


🚀 Installation & Usage
Clone the repository:
git clone https://github.com/<your-username>/Healthcare-Patient-Clustering.git
cd Healthcare-Patient-Clustering

Install dependencies:

pip install -r requirements.txt

Run the notebook:

jupyter notebook notebooks/patient_clustering.ipynb

📊 Output
2D PCA scatter plot with clustered patients
Silhouette Score and Davies-Bouldin Index for evaluation
Cluster profiling table showing mean symptom values for each cluster

📌 Dataset
The project uses the UCI Heart Disease dataset, fetched automatically via ucimlrepo.

