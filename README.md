# Diabetes Prediction Using Decision Tree Regressor
## Introduction
Welcome to Abdallah's Decision Tree project


## Description
This project aims to predict diabetes using a Decision Tree Regressor. The model is trained on the diabetes dataset provided by the `sklearn` library. The project includes data loading, preparation, model training, evaluation, and visualization of the decision tree. The motivation behind this project is to provide insights into diabetes prediction and to demonstrate the effectiveness of decision tree algorithms in regression tasks.

## Data Exploration
The dataset consists of various health metrics, including age, sex, body mass index (BMI), and blood pressure. Each feature plays a crucial role in predicting diabetes progression. The data is explored using correlation analysis to understand the relationships between features.

## Data Preparation
The dataset is converted into a pandas DataFrame, and independent (features) and dependent (target) variables are defined. The data is then split into training and testing sets to evaluate the model's performance.

## Installation
To run this project, you need to have the following libraries installed:
- pandas
- scikit-learn
- matplotlib
- seaborn

You can install the required libraries using pip:
```bash
pip install pandas scikit-learn matplotlib seaborn
```

## Usage
1. Load the Jupyter Notebook `Diabetes Prediction Using Decision Tree Regressor.ipynb`.
2. Run the cells sequentially to load the dataset, train the model, and evaluate its performance.
3. The model's performance metrics, including R² score, Mean Absolute Error, and Mean Squared Error, will be displayed.
4. The decision tree will be visualized at the end of the notebook.
5. Interpret the results to understand how well the model predicts diabetes progression.

## Future Work
Potential improvements to this project could include:
- Experimenting with different regression algorithms.
- Implementing cross-validation for more robust model evaluation.
- Exploring feature engineering techniques to enhance model performance.

## License
This project is licensed under the MIT License.
