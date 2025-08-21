# Mushroom Classification Project

This project aims to classify mushrooms as edible or poisonous based on their physical characteristics using various machine learning models.

## Dataset

The dataset used in this project is the Mushroom Dataset, which contains 8124 instances with 22 features, all of which are categorical.

## Project Steps

1.  **Data Loading and Exploration**: The dataset was loaded into a pandas DataFrame, and initial exploration was performed to understand the data structure, check for missing values, and view descriptive statistics.
2.  **Data Preprocessing**:
    *   The `veil-type` column was dropped as it had only one unique value and would not contribute to the classification.
    *   All categorical features were converted into numerical representations using Label Encoding.
3.  **Data Visualization**: Visualizations were created to understand the distribution of the target variable ('class') and the relationship between different features and the target variable.
4.  **Model Training and Evaluation**: Several classification models were trained and evaluated using K-Fold cross-validation:
    *   Logistic Regression
    *   Support Vector Classifier (SVC)
    *   K-Nearest Neighbors (KNN)
    *   Decision Tree Classifier
    
    The performance of each model was assessed using confusion matrices and classification reports.
5.  **Conclusion**: The average accuracy of each model was compared to determine the best-performing model.

## Results

The following average accuracies were achieved by the models:

*   Logistic Regression: 94.99%
*   SVC: 99.05%
*   KNN: 99.84%
*   Decision Tree Classifier: 100.00%

The Decision Tree Classifier achieved the highest average accuracy of 100%, indicating it is the most suitable model for this classification task.

## Usage

To run this project, you will need to have Python and the following libraries installed:

*   pandas
*   numpy
*   matplotlib
*   seaborn
*   scikit-learn
*   plotly

You can run the provided Jupyter Notebook to reproduce the analysis and model training.

## Files

*   `mushrooms.csv`: The dataset file.
*   `Mushroom_Classification.ipynb`: The Jupyter Notebook containing the project code.


<!---
DukeAche/DukeAche is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
