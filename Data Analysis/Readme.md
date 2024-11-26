# Categories Prediction Based on Symptoms
This project is focused on predicting categories based on the symptoms described in textual descriptions. It utilizes machine learning models to classify and predict the category of a given symptom, such as errors, requests, or issues in various domains. The models used include Logistic Regression, Decision Trees, and Random Forest, with further optimization through GridSearchCV.

## Data Preprocessing:

The dataset contains columns for symptoms and their corresponding categories.
TF-IDF (Term Frequency-Inverse Document Frequency) vectorization is applied to transform text data into numerical format.
Label encoding is used to convert categorical labels into numerical values.

## Model Training:

Multiple models (Logistic Regression, Decision Tree, Random Forest) are trained and evaluated on the data.
The best model is selected based on accuracy, and GridSearchCV is used to fine-tune hyperparameters for better performance.
## Evaluation:

The model's performance is evaluated using accuracy, with the Random Forest model initially providing the best results.
GridSearchCV is applied to further enhance model performance, selecting the best-performing configuration.
## Prediction:

The trained model is used to predict categories for new symptoms.
Predictions for both new symptoms (e.g., "mic not working") and real data are provided.
The final predictions are saved in an Excel file, with the model's best predictions from GridSearchCV stored for future use.
## Deployment:

The final predictions are saved in a new Excel file (Predict_cat.xlsx), containing the predicted categories for new data.
The project can be further extended to handle larger datasets, optimize performance, and deploy as a web service.
## Files Included:
Train.xlsx: Original training data with symptoms and categories.
New_Data.xlsx: New data for prediction with 'Subject' column containing symptoms.
Predict_cat.xlsx: The output file containing predicted categories for new data.
Code Script: Python script implementing the entire workflow from data preprocessing to prediction.
## Technologies Used:
Python
Pandas
Scikit-Learn (for machine learning models and GridSearchCV)
TfidfVectorizer
LabelEncoder
Excel for data input/output
Setup:
Install required libraries:
bash
Copy code
pip install pandas scikit-learn openpyxl
Load your dataset (Train.xlsx) and apply the provided script to train the models and predict categories for new data.
## Usage:
Train the model: The model is trained on the data from Train.xlsx.
Predict categories: Input new symptoms via New_Data.xlsx and get the predicted categories in the output Predict_cat.xlsx.
