# Machine Learning 
This step was used for **training** the machine learning model for identifying phylogenetic clades using SNP data.

## Whole of the processing and training  was done on the `Machine Learning Notebook Rare Variants.ipynb`

The machine learning models that were used in training was from the scikit learn 0.24.2 library.
<br>
<br>
Machine learning models trained in this notebook:

- Multinomial Logistic Regression: **99.80%**
- Random Forest Classifier: **99.87%** 
- Support Vector Machine: **99.76%**
- K Nearest Neighbors: **99.71**

Classification and Cross Validation metrics are inside the notebook.

The best performing model (Random Forest Classifier) was also exported in a pkl file for future use.