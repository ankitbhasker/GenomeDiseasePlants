# 🌱 Genomic Trait Analysis for Pest and Drought Resistance

This project provides an interactive Streamlit web application to analyze genomic variants (SNPs) and phenotypic traits to identify associations related to **pest resistance** and **drought tolerance** in plants.

## 🚀 Demo
Upload your **VCF file** (genotypic data) and **CSV file** (phenotypic data), and the app will:
- Perform GWAS
- Identify QTLs
- Run Genomic Selection Models
- Perform PCA Clustering
- Output Top Candidate SNPs

> 📸 Background image is dynamically rendered using base64 encoding for an enhanced visual experience.

---

## 📁 Features

| Module               | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| 📥 File Upload        | Upload `.vcf` and `.csv` phenotype files                                    |
| 🔬 GWAS               | Linear regression (OLS) for trait association, with Manhattan plot output   |
| 🌾 Genomic Selection  | Predict traits using Random Forest & Ridge Regression models                |
| 🧬 QTL Mapping        | Maps genomic regions significantly correlated with traits                   |
| 🧭 PCA Clustering     | Reduces dimensions to visualize genomic diversity and trait clustering      |
| 🎯 Candidate SNPs     | Filters SNPs with high association (p < 1e-5)                               |
| 🔖 Functional Annotation | Placeholder for Biopython/Entrez integration for gene-level insights     |

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **Pandas, NumPy**
- **scikit-allel**
- **scikit-learn**
- **matplotlib, seaborn**
- **statsmodels**
- **scipy**
- **PCA (sklearn.decomposition)**

---

## 🧬 Sample Inputs

- `*.vcf` file: Variant Call Format containing genotypic SNP data.
- `phenotype.csv`: CSV with columns:



---

## 📸 Screenshots
<img width="1097" height="509" alt="image" src="https://github.com/user-attachments/assets/ec637a9e-b2c8-434c-b71b-1dbd858f9bc7" />
<img width="1097" height="723" alt="image" src="https://github.com/user-attachments/assets/ce3bf95b-d426-4495-ba18-fef79e59d539" />
<img width="1097" height="612" alt="image" src="https://github.com/user-attachments/assets/c75a5a41-d19e-4bbd-8058-e725ea395d0b" />

<img width="1097" height="973" alt="image" src="https://github.com/user-attachments/assets/e112bbe5-1142-40ee-8bd0-4ccefd736f99" />


![GWAS Manhattan Plot](./screenshots/manhattan_plot.png)
![QTL Mapping](./screenshots/qtl_mapping.png)
![PCA Clustering](./screenshots/pca_clustering.png)

> Ensure you add these screenshots in a `/screenshots` directory.

---

## 🔧 Installation

### ⚙️ Requirements

Install required Python libraries:

```bash
pip install -r requirements.txt


streamlit
pandas
numpy
matplotlib
seaborn
scikit-learn
statsmodels
scikit-allel
scipy


👨‍🔬 Authors
## 👨‍🔬 Authors

| Name               | 🌐 LinkedIn | 📧 Email | 💻 GitHub |
|--------------------|-------------|----------|-----------|
| **Ankit Kr. Bhasker** | [🔗](https://www.linkedin.com/in/ankit-bhasker) | [✉️](mailto:bhasker.ankit@gmail.com) | — |
| **Ashwini Kumar**     | [🔗](https://www.linkedin.com/mwlite/profile/me?trk=p_mwlite_feed-secondary_nav) | [✉️](mailto:ashwini.verma.564@gmail.com) | — |
| **Aryan**             | [🔗](https://www.linkedin.com/in/aryan-gupta-75aaa7325?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) | [✉️](mailto:aryan40314@gmail.com) | [🐙](https://github.com/aryan4031) |
| **Gurvin Kour**       | — | [✉️](mailto:gurvinkour1@gmail.com) | — |


This project is licensed under the MIT License. See LICENSE for details.
