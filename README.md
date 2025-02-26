# NST-2007-HS_CODE_Prediction_Classification_XGboost_Catboot_Lightgbm
NST-2007/HS_CODE_Prediction_Classification_XGboost_Catboot_Lightgbm
Title of the paper: "Machine learning for cargo code prediction in port logistics" 
Abstract: Digital transformation of ports is very important to deal with the problems of security, sustainability and logistics. Precisely identifying various ship types is the aim of ship classification, which is essential for safeguarding interests and rights related to maritime trade and improving early warning systems for coastal defense. In this paper, an attempt is made to identify the impact of various feature selection methods like Chi-square, Correlation, Boruta etc., on decision tree classifier performance in predicting the cargo code (NST2007) of Port of Sines, Portugal. The private dataset was collected by Port of Sines, Portugal for the period of Jan, 2023 to December, 2024. The model is trained on June dataset after pre-processing and tested on remaining months with same pre-processing steps. Various metrics are used to validate the model's performance with various feature section methods. Finally, observed that model accuracy is degraded with the test cases due to non-seen cases which are not available during training the model. 
Steps to use resporitory
  1. Provide path to the dataset
  2. Pre-process dataset includes cleaning and drop the cases with "NaN"
  3. Selection models
  4. Training and testing of the models
  5. Finally matrics AUC, precision, recall and plot of ROC-AUC
