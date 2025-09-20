# Machine-Learning-project-
This project predicts diabetes using machine learning. It uses a Support Vector Classifier (SVC) model trained on a health-related dataset. The notebook covers the full workflow from data analysis and preprocessing to model evaluation and a simple predictive system.
### Description

This project predicts diabetes using machine learning. It uses a Support Vector Classifier (SVC) model trained on a health-related dataset. The notebook covers the full workflow from data analysis and preprocessing to model evaluation and a simple predictive system.

-----

### README.md

### Diabetes Prediction Using Machine Learning

This repository contains a Jupyter Notebook that demonstrates a machine learning project for predicting diabetes. The project follows a standard data science workflow, from data collection and analysis to model training and evaluation.

#### Key Features

  * **Data Analysis**: Exploratory data analysis is performed to understand the dataset, including statistical summaries and class distribution. The dataset has 768 rows and 9 columns, with 500 non-diabetic and 268 diabetic outcomes.
  * **Data Preprocessing**: The data is preprocessed using `StandardScaler` to standardize feature values, ensuring they are on a similar scale for effective model training.
  * **Model Training**: A Support Vector Classifier (SVC) is trained to predict the `Outcome` variable (diabetic or not).
  * **Model Evaluation**: The model's performance is evaluated using accuracy scores on both the training and testing data. The training accuracy is approximately 82.9%, while the testing accuracy is 72.7%.
  * **Predictive System**: The notebook includes a function to make predictions on new, single data points.

#### How to Run the Notebook

1.  **Clone the repository:**

    ```bash
    git clone <repository-url>
    ```

2.  **Install the required libraries:**

    ```bash
    pip install pandas numpy scikit-learn
    ```

3.  **Place the dataset:**
    Ensure the `diabetes data set.csv` file is in the correct path as specified in the notebook.

4.  **Open and run:**
    Open the `Diabetes Prediction Using Machine Learning with Python (1).ipynb` file in a Jupyter environment and run the cells sequentially.

#### Dependencies

  * `pandas`
  * `numpy`
  * `scikit-learn`
