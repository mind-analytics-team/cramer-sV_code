# cramer-sV_code
This repo contain a function which creates confusion matrix for categorical variables. The values in the matrix are cramer's v values for the variables

Input: Dataframe containing only categorical variables

Output: confusion matrix dataframe

eg: confusion_df = cramersV(test_df)
    
    output: 
                        ClmDiagnosisCode_1	ClmDiagnosisCode_2	ClmDiagnosisCode_3
    ClmDiagnosisCode_1	1.000000	          0.176665	          0.187273
    ClmDiagnosisCode_2	0.176665	          1.000000	          0.115215
    ClmDiagnosisCode_3	0.187273	          0.115215	          1.000000


NOTE: Currently code is slow, feel free to update code to improve speed
