In this project, we aim to predict the “cancer” status and the relation of 50 predictors to cancer risk of an individual based on one’s demographic, environmental factors, sun exposure, and other lifestyle behaviors using data from 50,000 patients. The goal was to identify the best-performing model and the most significant predictors of skin cancer risk.

The dataset consists of 50 features including age, skin tone, UV exposure, family history, immunosuppressive status, lesion size, tanning bed use, sunscreen habits, BMI, and more. Our target variable "cancer" is a categorical variable with two outcomes: Benign or Malignant.

Models Compared: Logistic Regression, Random Forest, XGBoost, Decision Tree
Final model: Logistic Regression — selected for highest AUC of the four (0.639), lowest mean error, and best generalization across 10-fold cross-validation.

Top predictors: immunosuppressive status, skin tone (fair/very fair), family history of cancer, and age UV exposure and lesion size were strong predictors in tree-based models. BMI and gender showed little predictive power in this dataset
