Project Summary: Gold Mine Recovery Prediction
Objective
The goal of this project was to develop a machine learning prototype for Zyfra, a company specializing in efficiency solutions for heavy industry. The model aimed to predict the amount of gold recovered from gold ore to optimize production processes and eliminate unprofitable parameters.

Tasks
The project was divided into three key phases:

Data Preparation:

Open and examine the datasets: gold_recovery_train.csv, gold_recovery_test.csv, and gold_recovery_full.csv.

Validate the calculation of gold recovery (e.g., for rougher.output.recovery) and identify any discrepancies using Mean Absolute Error (MAE).

Examine parameters absent in the test set and identify their types for proper handling.

Perform comprehensive data preprocessing, including handling missing values.

Data Analysis:

Analyze the concentration changes of metals (Au, Ag, Pb) at various stages of purification to identify trends.

Compare feed particle size distributions between training and test sets to ensure consistency for accurate model evaluation.

Investigate total substance concentrations across different stages (raw feed, rougher concentrate, and final concentrate) to identify and handle anomalies.

Model Development:

Write a custom function to calculate the final Symmetric Mean Absolute Percentage Error (sMAPE).

Train and cross-validate multiple machine learning models, comparing performance to identify the best one.

Use the selected model to predict gold recovery and evaluate it against the test sample.

Tools and Techniques
Libraries: pandas, matplotlib, sklearn.

Models: Various machine learning models were trained and evaluated, with cross-validation used to ensure model robustness.

Metrics: The sMAPE metric was chosen to evaluate model performance due to its effectiveness in handling percentage errors.

Results
The final model provided accurate predictions of gold recovery, optimizing the extraction and purification process for Zyfra. The comprehensive data analysis and preprocessing ensured the reliability of the model by addressing inconsistencies and anomalies in the data.

This project demonstrated the power of machine learning in industrial applications, showcasing a pathway for enhanced production efficiency and cost minimization.


*Note: The combined data file is over 22,717 rows, 85 columns, and over 33Mb it can be download by this link. 
https://practicum-content.s3.us-west-1.amazonaws.com/datasets/gold_recovery_full.csv
