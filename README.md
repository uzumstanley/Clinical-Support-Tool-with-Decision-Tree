# Clinical-Support-Tool-with-Decision-Tree
Machine Learning, Python



### Introduction
- **Title:** Building a Clinical Decision Support Tool with Decision Trees
- **Objective:** To construct a model from historical patient data to predict the most appropriate medication for a new patient with the same illness.

### Data Description
- **Context:** The data is compiled for a study on patients who have all suffered from the same illness.
- **Features:** Age, Sex, Blood Pressure, and Cholesterol levels of the patients.
- **Target Variable:** The medication to which each patient responded (Drug A, B, C, X, or Y).

### Development Process
1. **Data Loading and Preparation:**
   - Libraries such as pandas and numpy for data manipulation and sklearn for the DecisionTreeClassifier are imported.
   - The patient data is loaded into a DataFrame for further processing.

2. **Exploratory Data Analysis:**
   - An initial exploration of the data is likely performed to understand the distribution and characteristics of the features and response variable.

3. **Model Development:**
   - A decision tree classifier is developed using the sklearn library.
   - The model is trained on the historical patient data to learn the patterns associated with the medication responses.

4. **Model Evaluation:**
   - The accuracy of the model is measured using the `accuracy_score` function from sklearn's metrics module.
   - A confusion matrix is generated to evaluate the performance across different classes.

### Evaluation Results
- **Accuracy:** The model achieved an accuracy of 98.33%, indicating a high level of precision in predicting the correct medication.
- **Confusion Matrix:** The matrix suggests that the classifier performed exceptionally well across all medication classes with the following correct predictions:
  - Drug A: 7
  - Drug B: 5
  - Drug C: 5
  - Drug X: 20
  - Drug Y: 22
  Only one instance of Drug X was misclassified, indicating a nearly perfect classification.

## Conclusion
The decision tree model demonstrates excellent performance in classifying the correct medication for patients based on their profiles.
The high accuracy score and detailed confusion matrix indicate the model's potential as a robust clinical decision support tool.

