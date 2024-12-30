Predictive Maintenance in Manufacturing Sector

Overview
The process of brake manufacturing consists of multiple stages involving different kinds of machines like CNC for cutting the metal sheets, Grinder for grinding the brake parts, Hydraulic Press to make sure the parts are perfectly assembled and Testing machine to ensure the brakes operate as expected without any inaccuracies.Monitoring these machines is crucial as downtime can cause issues like delay in production, quality issues and increased costs. Our model solves this problem by predicting the machine’s current health, remaining utility lifespan and anomaly causing components in these machines.This helps the plant in going for a predictive maintenance rather than reactive. We aim to build the model efficient enough to create an appropriate maintenance schedules in order to avoid unwanted downtimes and therefore reducing costs and saving production time.

This project focuses on implementing predictive maintenance for brake manufacturing machines, including CNC, Grinders, Hydraulic Presses, and Testing machines.By forecasting machine health and potential failures, we aim to reduce downtime, optimize maintenance schedules, and enhance production efficiency.

Algorithms Considered:
1. Logistic Regression: Baseline, linear relationships
2. Random Forest: Non-linear patterns, feature importance
3. XGBoost: Gradient boosting, high accuracy
4. SVM: Good for classification tasks
5. ANN: Captures complex patterns (deep learning)
   
Evaluation Criteria:
1. Accuracy: Model performance on test data
2. Execution Time: Efficiency of training and inference
3. Complexity: Ease of deployment & interpretability
4. Robustness: Ability to handle noisy/missing data

Based on above Criterion the best choosen Algorithm is XGBoost which is used in the main file - predictive_maintenance.ipynb.

This repository contains several Jupyter notebooks, dataset and requirements file implementing different machine learning models for predictive maintenance:

1. maintenance_data.csv: Dataset used for predictive maintenance
2. ANN.ipynb: Artificial Neural Network algorithm
3. logistic_regression.ipynb: Logistic Regression algorithm
4. predictive_maintenance.ipynb: XGBoost algorithm(main file)
5. randomForest.ipynb: Random Forest algorithm
6. svm.ipynb: Support Vector Machine algorithm
7. xgboost.ipynb: XGBoost algorithm
8. requirements.txt: Contains list of all required libraries

Steps to run the code:
1. Clone the repository.
   > Open a terminal and run - "git clone https://github.com/meghanaRABBA/Group_10_ML_Project.git"
2. Run all the ".ipynb" files on Jupyter Notebook one after other
3. The first cell in the ".ipynb" files contains the code "pip install -r requirements.txt". - Running this installs all the required libraries needed to run the code mentioned in the "requirements.txt" file.
4. After running this cell continue to next cell to execute the respective alogrithm code and check the output.
5. The file "predictive_maintenance.ipynb" is the main and final algorithm(XGBoost) which is the final output of this project.









