# Title: Machine Learning Model Ensemble Fitting and Prediction Workflow for Biodiversity Analysis
# Author: Vinicius Marcilio-Silva
![image](https://github.com/user-attachments/assets/cc9a0de8-dcd9-492f-b430-968e959b47d3)

Contact: viniciuschms@gmail.com
Date: October 2024
# ----------------------------------------------------------------------------
Description: This script provides a generalized workflow for fitting models and predicting biodiversity
metrics based on environmental predictors. Developed as supplemental material for the paper
"Integrating remote sensing and field inventories to understand determinants of urban forest diversity and structure"
and based on code from Thiago Sanna F. Silva (tsfsilva@rc.unesp.br) 
available at https://datadryad.org/stash/dataset/doi:10.5061/dryad.6m905qfzp

Explanation of Key Steps:

1. Data Preprocessing: Prepares predictors by centering and scaling.
2. Data Splitting: Divides data into training and testing subsets for model validation.
3. Model Formula Creation: Dynamically creates a formula for each response variable.
4. Visualization: Generates scatter plots to check the relationship between predictors and response.
5. Cross-Validation: Sets up a repeated cross-validation scheme.
6. Model List Setup: Specifies the ensemble of models to be trained.
7. Model Training: Uses caretList to fit multiple models simultaneously.
8. Model Summaries: Extracts and saves a summary of model results.
9. Stacked Ensemble Model: Trains a stacked model to aggregate predictions.
10. Test Set Prediction: Predicts outcomes for the test set and calculates RMSE.
11. Variable Importance: Determines the importance of each variable in the ensemble model.
12. Future Projections: Applies the ensemble model to new data if future predictions are needed. This structure provides a reproducible workflow for analyzing multiple biodiversity metrics using ensemble modeling.
