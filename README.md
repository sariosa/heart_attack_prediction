##Overview##

This project uses Machine Learning to predict the likelihood of a heart attack based on medical data. It trains a Random Forest Classifier using a dataset of patient attributes like age, cholesterol levels, and blood pressure.

##Dataset##

The dataset is stored in HeartDataSet.csv and contains the following features:

Age: Age of the person

Sex: Gender (0 = Female, 1 = Male)

CP: Chest pain type

Chol: Serum cholesterol in mg/dl

FBS: Fasting blood sugar (>120 mg/dl)

RestECG: Resting electrocardiographic results

Thalachh: Maximum heart rate achieved

Exng: Exercise-induced angina (1 = Yes, 0 = No)

Oldpeak: ST depression induced by exercise

Slope: Slope of the peak exercise ST segment

Caa: Number of major vessels colored by fluoroscopy

Thall: Thalassemia level

Output: 1 = High chance of heart attack, 0 = Low chance

##How to Use##

Train the Model:
Run Heart-prediction.ipynb to train and evaluate the model.
Model Saving:
The trained model is saved as heart_attack_model.pkl, and the scaler is saved as scaler.pkl.
