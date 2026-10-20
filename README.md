Comparative Analysis of Machine Learning Models for Multiclass Water Quality Classification

 Project Overview
This project uses Machine Learning to classify water samples as **Potable (safe to drink)** or **Not Potable** based on physicochemical water-quality parameters.

 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Jupyter Notebook

 Input Features
- pH
- Hardness
- Solids
- Chloramines
- Sulfate
- Conductivity
- Organic Carbon
- Trihalomethanes
- Turbidity

 Algorithm
**K-Nearest Neighbors (KNN)**

The model uses feature scaling and 5-fold cross-validation to help select the KNN configuration.

 Model Configuration
- K: 3
- Weights: Distance
- Distance Metric: Manhattan

 Results

| Metric | Score |
|---|---:|
| Accuracy | 95.41% |
| Precision | 94.36% |
| Recall | 96.58% |
| F1-Score | 95.46% |
| ROC-AUC | 0.9670 |
| Average Precision | 0.9506 |

These results correspond to the evaluated test split for this experiment.

 How to Run
1. Install the required libraries using `pip install -r requirements.txt`.
2. Open the Jupyter Notebook.
3. Run the notebook cells in order.

 Project Status
Machine learning model development and evaluation completed.
