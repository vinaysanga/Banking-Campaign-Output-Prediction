# Banking Campaign Output Prediction
This project aims to predict the outcomes of direct marketing campaigns conducted by a banking institution for term deposits. The focus is on whether a client will subscribe ('yes') or not ('no') to a term deposit based on historical data, which includes client information and previous campaign interactions. The ultimate goal is to enhance the efficiency of future marketing strategies.

<a target="_blank" href="https://colab.research.google.com/github/vinaysanga/Banking-Campaign-Output-Prediction/blob/master/Model_Notebook.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Data Description
The dataset encompasses information from direct marketing campaigns of a banking institution, primarily conducted via phone calls. It includes various attributes related to bank client data, the last contact of the current campaign, other attributes, and social and economic context attributes.

## Data Preprocessing
- **Feature Removal**: The 'duration' variable was excluded to ensure the model's applicability in real-world scenarios.
- **Missing Values**: Identified and addressed missing values.
- **Categorical Variables**: One-hot encoded to transform them into a numerical format.
- **Feature Scaling**: Standardized data to improve model convergence.
- **Feature Selection**: Identified and removed features with high correlation to prevent multicollinearity.
- **Handling Imbalanced Data**: Applied ADASYN oversampling technique to balance the classes.

## Modelling
- **Algorithms and Training**: Selected Logistic Regression and MLP Classifier for their distinct properties. Both models were trained with their hyperparameters finely tuned.
- **Model Evaluation and Improvement**: Evaluated models based on accuracy, precision, recall, and F1-Score. Adjustments were made to address class imbalance and feature selection, significantly improving model performance.

## Conclusion
- **Performance Improvement**: Rebalancing the data and feature selection notably enhanced the models' ability to accurately predict the minority class.
- **Bottlenecks and Solutions**: Addressed issues related to highly correlated features and imbalanced dataset through feature selection and oversampling.
- **Algorithm Comparison**: The MLP Classifier outperformed Logistic Regression, showcasing superior recall, F1-score, and AUC.

**For the entire info, please check [Project_Report](https://github.com/vinaysanga/Banking-Campaign-Output-Prediction/blob/master/Project_Report.pdf)**
