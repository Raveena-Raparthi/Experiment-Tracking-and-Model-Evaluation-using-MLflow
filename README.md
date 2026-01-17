# Experiment-Tracking-and-Model-Evaluation-using-MLflow
This project explains a simple end-to-end machine learning experimentation workflow using MLflow. The goal of the project is to track multiple machine learning experiments, compare their performance, and select the best model in an organized and reproducible way. The Iris dataset is used along with Logistic Regression models.

**Problem Statement**

In machine learning, we often train the same model multiple times with different settings. Without proper tracking, it becomes hard to compare results or reproduce experiments. This project uses MLflow to solve this problem by tracking experiments, parameters, metrics, and trained models.

**Dataset Used**

The Iris dataset contains 150 data points with four numerical features:

    Sepal length
    Sepal width
    Petal length
    Petal width

The target variable represents three different Iris flower species. The dataset is clean and suitable for learning and experimentation.

**Tools and Technologies**

    Python
    Scikit-learn
    MLflow
    NumPy
    Pandas

**Project Workflow**

First, the Iris dataset is loaded and split into training and testing datasets. Multiple Logistic Regression models are then trained using different solvers such as liblinear, lbfgs, and newton-cg.

Each model training process is tracked using MLflow. For every experiment, MLflow logs the solver used, the accuracy score, and the trained model file. This makes it easy to compare all experiments in one place.

**Model Evaluation**

Model performance is evaluated using accuracy. After comparing all experiments, the best-performing model achieved an accuracy of 96.67% on the test dataset.

**Results**

Created a structured machine learning experimentation pipeline

Trained and compared multiple Logistic Regression models

Achieved 96.67% accuracy

Used MLflow for clear experiment tracking and reproducibility

**Conclusion**

This project shows how MLflow helps in managing machine learning experiments efficiently. It makes model comparison simple, improves reproducibility, and supports better decision-making during model selection.

**Future Scope**

This project can be extended by adding hyperparameter tuning, testing other machine learning algorithms, or deploying the selected model using MLflow Model Registry.
