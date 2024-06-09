# Loan Prediction

This Data Analytics project aims to predict whether an individual will be eligible to receive a loan from a bank. As we know, obtaining a loan from a bank can be quite challenging. This project addresses the real-time issue by determining eligibility for receiving a loan based on certain criteria and documents. Our model achieves a prediction accuracy of 85%, making it a reliable tool for loan eligibility assessment.

## Technologies

This project is entirely built using Jupyter Notebook and Python for data analysis. We have utilized several powerful Python libraries, including:

- **Pandas**: Used for data analysis and manipulation, filtering data efficiently. Pandas is a powerful, fast, and flexible library essential for data science.
- **NumPy**: Provides multi-dimensional array and matrix data structures. It is generally used to perform mathematical and logical operations on arrays.
- **Matplotlib**: Utilized for data visualization to create static, interactive, and animated visualizations.

Additionally, we have used:

- **Scikit-learn**: A highly useful library with effective tools for machine learning and statistical modeling, including a range of supervised and unsupervised learning algorithms.

## Algorithms

In this project, we employ the following algorithms to predict loan eligibility:

### Decision Tree

A Decision Tree is a non-parametric supervised learning algorithm used for classification and regression tasks. The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features. Decision Trees break down a dataset into smaller subsets while simultaneously developing an associated decision tree incrementally. The final result is a tree with decision nodes and leaf nodes. Key advantages of Decision Trees include:

- Easy to understand and interpret.
- Can handle both numerical and categorical data.
- Requires little data preprocessing.

### Naive Bayes Classification Algorithm

The Naive Bayes algorithm is based on Bayes' Theorem and assumes that the presence of a particular feature in a class is unrelated to the presence of any other feature. Even if these features depend on each other, all these properties independently contribute to the probability of the outcome. Naive Bayes classifiers are highly scalable, requiring a number of parameters linear in the number of variables in a learning problem. Key advantages of Naive Bayes include:

- Fast and easy to implement.
- Performs well in multi-class prediction.
- Particularly effective for large datasets.

## DataSet Train

```plaintext
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 614 entries, 0 to 613
Data columns (total 13 columns):
     Column             Non-Null Count  Dtype  
---  ------             --------------  -----  
 0   Loan_ID            614 non-null    object 
 1   Gender             601 non-null    object 
 2   Married            611 non-null    object 
 3   Dependents         599 non-null    object 
 4   Education          614 non-null    object 
 5   Self_Employed      582 non-null    object 
 6   ApplicantIncome    614 non-null    int64  
 7   CoapplicantIncome  614 non-null    float64
 8   LoanAmount         592 non-null    float64
 9   Loan_Amount_Term   600 non-null    float64
 10  Credit_History     564 non-null    float64
 11  Property_Area      614 non-null    object 
 12  Loan_Status        614 non-null    object 
dtypes: float64(4), int64(1), object(8)
memory usage: 62.5+ KB
```

## DataSet Test

```plaintext
Loan_ID              
Gender               
Married              
Dependents           
Education            
Self_Employed        
ApplicantIncome      
CoapplicantIncome    
LoanAmount           
Loan_Amount_Term     
Credit_History       
Property_Area        
dtype: int64
```

## Conclusion

By leveraging these technologies and algorithms, this project aims to provide a robust solution for predicting loan eligibility with an accuracy of 85%. This can help banks streamline their loan approval process, reduce manual workload, and improve decision-making accuracy.
