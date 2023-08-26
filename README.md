# <center><b>Loan Approval Prediction</b><center>
<style> p {text-align: justify;}</style>
<p>

- Topic : Machine Learning
- Programming languages : Python
- Packages : pandas, numpy, sklearn, seaborn, and matplotlib
- Algorithms used : Decision Tree, Random Forest, K-Nearest Neighbor, Logistic Regression, and Gaussian Naive Bayes</p>

## A. Background
<style> p {text-align: justify;}</style>
<p>Loan approval is a popular issue in the credit/banking industry. Loan approval in commercial banks is one of the challenges affecting operational financial processes due to inaccurate estimates or lack of information. Commercial banks usually receive many loan applications. Many of them are rejected for various reasons, such as high loan balances, a low-income level, or too many inquiries regarding one's credit report. Analyzing these applications manually is mundane, error-prone, and time-consuming. 

Fortunately, machine learning helps us with this and almost all commercial banks can do it nowadays. In this project, we have created an automated loan approval predictor using machine learning techniques, just like real banks do.</p>

## B. Data Source
<style> p {text-align: justify;}</style>
<p>The dataset used in this project comes from the Loan Predication dataset from Kaggle. Here is the <a href="https://www.kaggle.com/ninzaami/loan-predication/home"> [Link]</a>.</p>

## C. AI Project Cycle

<style> p {text-align: justify;}</style>
<p>The approach to solve this case is done by applying the AI Project Cycle. The schematic is shown in Figure 1. The stages of data acquisition, data exploration, modeling, and evaluation are described in a notebook that has been provided.</p>

<figure>
  <img src="AI_Project_Cycle.png" alt="Alt Text">
  <figcaption style="text-align:center;"><b>Fig 1. AI Project Cycle.</b></figcaption>
</figure>

### 1. Problem Scoping
<style> p {text-align: justify;}</style>
<p>In problem scoping, we apply the 4Ws problem canvas technique (What, Who, Where, and Why). This is to determine the boundaries of the problem to be solved. Based on the background of the Loan Approval problem, we can make our problem scoping as follows:

  1. What (problem that arises): difficulty in detecting a person's credit score for loan approval.
  
  2. Who (stakeholders in this case): Bank
  
  3. Where (where the problem arises): When the customer has applied for a loan
  
  4. Why (a solution to solve the problem): Help predict and classify the candidate's loan status.</p>

### 2. Solution Approach 
<style> p {text-align: justify;}</style>
<p>The implementation of this approach is shown as follows:

  1. The first step starts with collecting, loading, and viewing the dataset that we will be processing. We will see that the dataset has a combination of numerical and categorical features, contains values from different ranges, and has some missing values.

  2. We need to do data exploration. Exploration includes understanding the dataset, handling missing values in the dataset, and preprocessing the dataset to ensure that the machine learning model we choose can make good predictions. After that, we will analyze the exploratory data to build our intuition on the data.

  3. We will build a machine-learning model. This model will predict whether someone's loan application will be approved. In model building, we apply try and error to get the best result.

  4. The last step is to evaluate the prediction result of the built model.</p>

## D. Summary
<style> p {text-align: justify;}</style>
<p>When building this loan approval predictor, we perform several steps such as converting categorical features to numerical, imputation of missing values, and determination of features used to build the model. We completed it with some machine learning models to predict whether a person's loan application will be approved or not with some information about the person. We have achieved 90% accuracy. 90% is the best we could get from this data using logistic regression model.
</p>