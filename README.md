
# Logistic Regression on Pima Indians Diabetes Dataset

This project performs logistic regression on the **Pima Indians Diabetes Dataset** to predict the likelihood of diabetes in female patients based on medical predictor variables.

## Dataset
The dataset contains several medical predictor variables (e.g., number of pregnancies, BMI, insulin level) and one target variable (`Outcome`), indicating whether a patient has diabetes (1) or not (0).

### Features
- **Pregnancies**: Number of times pregnant.
- **Glucose**: Plasma glucose concentration after 2 hours in an oral glucose tolerance test.
- **BloodPressure**: Diastolic blood pressure (mm Hg).
- **SkinThickness**: Triceps skin fold thickness (mm).
- **Insulin**: 2-Hour serum insulin (mu U/ml).
- **BMI**: Body mass index (weight in kg/(height in m)^2).
- **DiabetesPedigreeFunction**: Diabetes pedigree function.
- **Age**: Age in years.
- **Outcome**: Class variable (0 or 1).

## Steps in the Notebook

## Installation and Setup

1. Clone the repository.
2. Install the required Python libraries using:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook using:

   ```bash
   jupyter notebook logistic-regression-on-pima-indians-diabetes-data.ipynb
   ```

## Usage
- The notebook performs data preprocessing, exploratory data analysis (EDA), and logistic regression.
- Evaluation metrics include confusion matrix, accuracy score, and precision-recall curves.

## Results
- The logistic regression model demonstrates its ability to classify patients with and without diabetes based on the features provided.
- Detailed evaluation results and visualizations are provided in the notebook.

## Contributions
Contributions are welcome. Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.
