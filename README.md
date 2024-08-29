# Heart-Failure-Deep-Learning
Deep Learning project that predicts heart failure in patients
Best Model Test Accuracy: 0.972

Method: MLP Classifier
Hyperparameter Tuning: Used GridSeachCV to improve hypertuning and used the following: 
hidden_layer_sizes: Configurations of hidden layers and neurons., learning_rate_init: Initial learning rate for weight updates, max_iter: Number of epochs for training, batch_size: Size of mini-batches for stochastic gradient descent

Grid Search with Cross-Validation to reduce overfitting

Dataset information:
5,000 patients where each patient profile has 13 clinical features
Clinical features:
Age: Age of the patient (years)
Anemia: Decrease of red blood cells or hemoglobin (boolean)
Creatinine phosphokinase (CPK): Level of the CPK enzyme in the blood (mcg/L)
Diabetes: If the patient has diabetes (boolean)
Ejection fraction: Percentage of blood leaving the heart at each contraction (percentage)
High blood pressure: If the patient has hypertension (boolean)
Platelets: Platelets in the blood (kiloplatelets/mL)
Sex: woman or man (binary)
Serum creatinine: Level of serum creatinine in the blood (mg/dL)
Serum sodium: Level of serum sodium in the blood (mEq/L)
Smoking: If the patient smokes or not (boolean)
Time:  Follow-up period (days)
DEATH_EVENT: If the patient died during the follow-up period (boolean)

Link to dataset: https://www.kaggle.com/datasets/aadarshvelu/heart-failure-prediction-clinical-records 
