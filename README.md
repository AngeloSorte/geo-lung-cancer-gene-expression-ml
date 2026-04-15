# 🧬 GEO Gene Expression Analysis (Lung Cancer vs Normal)

This project analyzes real gene expression data from the **NCBI GEO database (GSE10072)** to distinguish between lung cancer and normal tissue samples using Machine Learning techniques.

---

## 🚀 Project Goals

- Load and process real gene expression data from GEO (NCBI)
- Apply biological preprocessing (log transformation + normalization)
- Reduce dimensionality using PCA
- Discover hidden structure using clustering (KMeans)
- Detect abnormal gene expression patterns (Isolation Forest)

---

## 📊 Dataset

- Source: NCBI Gene Expression Omnibus (GEO)
- Dataset: **GSE10072**
- Problem: Lung cancer vs normal tissue classification
- Data type: Gene expression microarray matrix

---

## 🧠 Methods Used

### 1. Preprocessing
- Handling missing values
- Log transformation (log1p)
- Feature scaling (StandardScaler)

### 2. Dimensionality Reduction
- Principal Component Analysis (PCA)

### 3. Unsupervised Learning
- KMeans clustering (k=2)

### 4. Anomaly Detection
- Isolation Forest for rare gene expression patterns

---

## 📈 Key Insights

- PCA reveals partial separation between cancer and normal tissue samples
- Clustering identifies latent biological structure
- Anomaly detection highlights unusual gene expression profiles
- High-dimensional gene data can be effectively compressed and analyzed with ML

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📌 How to Run

```bash
pip install -r requirements.txt

Run the notebook in Google Colab or Jupyter.

---

**## 📚 Future Improvements
**
Differential gene expression analysis (DESeq-like methods)
Supervised classification (Random Forest / XGBoost)
Gene pathway enrichment analysis (KEGG / GO)
Deep learning autoencoders for gene embeddings

---

**## 👤 Author
**
Angelo Sorte
