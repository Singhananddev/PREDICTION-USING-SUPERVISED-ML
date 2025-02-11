![student_score](https://github.com/user-attachments/assets/ffc5ebc5-4bec-4a89-8990-89120b2222ee)


# PREDICTION-USING-SUPERVISED-ML

**Predicting Student Scores with Linear Regression**

This is a machine learning project to create a linear regression model that predicts student test scores based on the number of hours they studied. The model is trained on a dataset of students' study hours and achieved scores.

**Overview**

The goal of this project is to accurately predict the score of a student on a test based on the number of hours they studied. This will help provide insight on how factors like study duration impact test performance.

The data and Jupyter notebook provided here trains a simple linear regression model using PyTorch on data containing a student's study hours and test score. Ideas for extending this basic model are also provided below.

**Contents**

The repository contains the following files:

**student_scores.ipynb:**  Jupyter notebook containing data preparation, model training, evaluation, and predictions.
**student_scores.csv:**  Dataset with each row representing a student's hours studied and achieved test score.
**requirements.txt:**  Python package dependencies for executing the notebook.

**Requirements**

The following packages need to be installed to execute the Jupyter notebook with the model training code:

NumPy
Pandas
Matplotlib
PyTorch
scikit-learn
These can easily be installed via pip install -r requirements.txt

**Possible Extensions**

Here are some ideas for extending the analysis:

Try different ML regression models like random forest to compare performance
Analyze predictions errors - why does the model work well or poorly?
Increase size and diversity of training data for improved accuracy
Feature engineer additional predictive variables like grade level or subject
Deploy model via API to provide study time recommendations based on score goals
Overall this provides the basic scaffolding to start predicting student scores using liner regression techniques in Python. Please use this as a starting point for your own experiments and analyses!
