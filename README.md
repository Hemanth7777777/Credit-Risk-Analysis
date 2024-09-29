# Credit Risk Analysis

This project analyzes credit risk using machine learning models to predict whether a person will default on their credit. The notebook includes data preparation, model training, and hyperparameter tuning for optimal performance.

## Project Structure

- **Data Preparation**:
  - The dataset is split into training and test sets using `train_test_split`.
  - The target variable is `cb_person_default_on_file`, indicating whether a person has defaulted on their credit.

- **Modeling**:
  - Models used include:
    - **Decision Tree Classifier**: A decision tree model with a maximum depth of 20 and a minimum sample split of 10.
    - **XGBoost Classifier**: A gradient boosting model with hyperparameter tuning.

- **Hyperparameter Tuning**:
  - A grid search is performed to find the best combination of hyperparameters for the XGBoost model.
  - The parameters tuned include `n_estimators`, `max_depth`, and `learning_rate`.

- **Evaluation Metrics**:
  - The models are evaluated using **accuracy**, **precision**, **recall**, and **F1 score**.


## Results

- The model's performance is evaluated based on accuracy and other classification metrics.
- Results from hyperparameter tuning are printed, showing the best-performing model and its parameters.

