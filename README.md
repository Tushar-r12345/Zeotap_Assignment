# Zeotap Assignment

## Overview
This project involves exploratory data analysis (EDA), building predictive models, and deriving actionable insights from three provided datasets: `Customers.csv`, `Products.csv`, and `Transactions.csv`. The tasks test data analysis, machine learning, and business insight generation skills.

## File Structure

```
.
├── Customers.csv                 # Dataset containing customer information
├── Products.csv                  # Dataset containing product details
├── Transactions.csv              # Dataset containing transaction records
├── Tushar_Pal_Clustering.ipynb   # Jupyter Notebook for clustering analysis
├── Tushar_Pal_Clustering.pdf     # PDF export of the clustering notebook
├── Tushar_Pal_EDA.ipynb          # Jupyter Notebook for exploratory data analysis
├── Tushar_Pal_EDA.pdf            # PDF export of the EDA notebook
├── Tushar_Pal_Lookalike.csv      # Output file for lookalike modeling
├── Tushar_Pal_Lookalike.ipynb    # Jupyter Notebook for lookalike modeling
└── README.md                     # Documentation for the assignment
```

## Contents

### 1. Exploratory Data Analysis (EDA)
- File: `Tushar_Pal_EDA.ipynb`
- Description: 
  - Conducted an in-depth analysis of the `Customers.csv`, `Products.csv`, and `Transactions.csv` datasets.
  - Identified trends, patterns, and anomalies in the data.
  - Visualized data using charts and graphs to uncover insights.
- Output: `Tushar_Pal_EDA.pdf`

### 2. Clustering Analysis
- File: `Tushar_Pal_Clustering.ipynb`
- Description:
  - Applied clustering techniques to segment customers based on their purchase behavior.
  - Used algorithms like K-Means and evaluated clustering performance using metrics like Silhouette Score.
  - Generated actionable clusters to target specific customer segments.
- Output:
  - Notebook: `Tushar_Pal_Clustering.ipynb`
  - PDF: `Tushar_Pal_Clustering.pdf`
  - Results: `Tushar_Pal_Clustering.csv`

### 3. Lookalike Modeling
- File: `Tushar_Pal_Lookalike.ipynb`
- Description:
  - Built predictive models to identify potential customers who exhibit similar characteristics to existing high-value customers.
- Output:
  - Notebook: `Tushar_Pal_Lookalike.ipynb`
  - Results: `Tushar_Pal_Lookalike.csv`

## How to Run the Notebooks
1. Clone this repository or download the files.
2. Install the necessary Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   *(Note: Ensure `requirements.txt` includes libraries like pandas, numpy, matplotlib, seaborn, and scikit-learn.)*
3. Open the Jupyter Notebooks (`*.ipynb`) in Jupyter Notebook or Jupyter Lab.
4. Run the notebooks sequentially to replicate the analysis.

## Key Insights
### EDA
- Identified top-performing products and high-value customers.
- Highlighted seasonality trends and purchase patterns.

### Clustering
- Segmented customers into meaningful groups to enable targeted marketing.
- Insights into customer loyalty and high-value segments.

### Lookalike Modeling
- Predicted potential customers who could exhibit high-value behaviors.
- Helped in designing effective acquisition campaigns.

## Tools and Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## Deliverables
- Analysis results and insights in PDF format.
- CSV outputs for clustering and lookalike modeling.
- Jupyter Notebooks for reproducibility.
