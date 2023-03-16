# **Student Credit Repayment Prediction Model**

This repository contains a machine learning model that predicts whether a student is eligible for credit and whether they can pay it back. The model is based on a dataset of historical student loan applications and their repayment status.

**Getting Started**

To use this model, you will need to have Python 3 and the following Python libraries installed:

- Pandas
- Scikit-learn
- Numpy

You can install these libraries by running the following command:

pip install pandas scikit-learn numpy

Once you have installed the required libraries, you can run the model by running the student\_credit\_repayment.py script:

python student\_credit\_repayment.py

This will load the dataset, train the model, and output the prediction accuracy.

**Dataset**

The dataset used in this model is a collection of historical student loan applications and their repayment status. The dataset contains the following fields:

- student\_id: unique identifier for each student
- age: age of the student
- sex: gender of the student
- Location: home address of the student
- family\_size: size of the student's family
- income: income of the student's family
- credit\_history: credit history of the student's family
- loan\_amount: amount of the loan requested by the student
- loan\_duration: duration of the loan requested by the student
- repayment\_status: whether the loan was repaid or not (target variable)

**Model**

The model used in this project is a decision tree classifier. The decision tree classifier is a type of supervised learning algorithm that is mostly used for classification problems. It works by partitioning the dataset into smaller subsets based on the values of the input features. The model then selects the feature that results in the best split, and recursively splits the data based on this feature until a stopping criterion is reached.

![](RackMultipart20230316-1-33nvxq_html_fd61b5c737956914.png)

![](RackMultipart20230316-1-33nvxq_html_4fe9ef053622ba9e.png)

![](RackMultipart20230316-1-33nvxq_html_727d9e1001bb7667.png) ![](RackMultipart20230316-1-33nvxq_html_232eea1de0feefa4.png)

![](RackMultipart20230316-1-33nvxq_html_cb12f7f8e7817743.png)

![](RackMultipart20230316-1-33nvxq_html_e69a1ef98d229834.png)

**Results**

The model achieved an accuracy of 85% on the test set. This indicates that the model is able to predict the eligibility and repayment status of student loans with a high degree of accuracy.
