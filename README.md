# Credit card default predict

Link dataset: https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset

In order to estimate the likelihood that a client will default, this project uses quantitative methods to choose the best models, such as logistics, SVM, decision trees, etc.

In this project, I make use of a number of data preprocessing techniques, including handling missing values, duplicate values, detecting anomalies (Oulier), and creating various data visualization charts.

I apply the models indicated above to select the best machine learning model, however because this dataset has a problem with data imbalance, we must continue with imbalanced data processing. by using the following two primary techniques: UnderSampling (Random UnderSampling and NearMiss) and OverSampling (Random OverSampling - using library and SMOTE). The results were greatly improved after handling the uneven data, and the desired model was discovered.
