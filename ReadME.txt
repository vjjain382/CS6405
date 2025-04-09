Repetition Prediction using Random Forest Regressor
This project loads a pre-trained Random Forest Regressor model to predict the number of repetitions based on sensor features collected during physical activity. The model is evaluated using a test dataset, and performance is visualized through several evaluation plots.

Requirements
Python 3.x

Libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn

joblib

urllib

Dataset
The test dataset is loaded from GitHub:

bash
Copy
Edit
https://raw.githubusercontent.com/andvise/DM_Assignment_2425/refs/heads/main/test_data.csv
It includes time-domain and frequency-domain features from wearable sensors.

Selected Features:
X_Shoulder_acc_MPSD

X_Shoulder_acc_Power_Dominant_Band

X_Shoulder_acc_Total_Power

Y_Shoulder_acc_Freq_MPSD

Y_Shoulder_acc_Total_HighFreq_Power

Y_Shoulder_acc_PSD_Skewness

Y_Torso_acc_MPSD

Target variable: Repetition

Model
The model is a pre-trained Random Forest Regressor, saved in .pkl format and loaded from:

bash
Copy
Edit
https://github.com/vjjain382/CS6405/blob/main/best_random_forest_model.pkl
Evaluation Metrics
R² Score

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

Visualizations
Predicted vs Actual – Compares true and predicted values.

Residuals vs Predictions – Displays error trends.

Histogram of Residuals – Shows the distribution of prediction errors.

How to Run
bash
Copy
Edit
# Clone or copy this script into Google Colab or Jupyter Notebook
# Make sure required libraries are installed
# Run each cell to:
# 1. Load the model
# 2. Load the dataset
# 3. Evaluate the model
# 4. Visualize results
Author
Developed as part of a project for evaluating machine learning regressors using wearable sensor data.

Let me know if you'd like this exported to a .md file or formatted differently!







4o

