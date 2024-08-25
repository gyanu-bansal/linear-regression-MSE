# Linear Regression Model for Salary Prediction

This project is a Python script to perform a simple linear regression analysis using the `scikit-learn` library. The script predicts salaries based on years of experience and evaluates the model's performance using Mean Squared Error (MSE).

## How to Use

### Prerequisites

- Python 3.x installed on your system.
- Required libraries: `pandas`, `scikit-learn`.

You can install the necessary libraries using pip:

```bash
pip install pandas scikit-learn
### Running the Script

1. **Save the script** as `iris_splitter.py` or any name you prefer.
2. **Open a terminal or command prompt**.
3. **Navigate to the directory** where the script is saved.
4. **Run the script** by executing the following command:

    ```bash
    python salary_prediction.py
### Script Details

The script performs the following steps:
## Data Preparation

1. ** A sample dataset is created using years of experience and corresponding salaries. This can be replaced with your actual dataset.**

## Feature Selection

1.**The YearsExperience column is selected as the feature (X).**
2.** The Salary column is selected as the target variable (y).**

## Train-Test Split

1.**The dataset is split into training and testing sets using an 80-20 split.**

## Model Training

1.**A linear regression model is created and trained on the training set.**

## Prediction

1.**The model predicts salaries for the test set based on years of experience.**

## Model Evaluation

1.**The Mean Squared Error (MSE) is calculated to evaluate the model's performance on the test set.**

### Example

Here is a sample output of the script:
python
Mean Squared Error on the test set: 25691478.63
