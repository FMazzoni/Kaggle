<a href="https://www.kaggle.com/code/fernandomazzoni/titanic-1st-competition-submission?scriptVersionId=101427826" target="_blank"><img align="left" alt="Kaggle" title="Open in Kaggle" src="https://kaggle.com/static/images/open-in-kaggle.svg"></a>

# Titanic - Machine Learning from Disaster


This is my first submission for Kaggle Competitions which I placed in the top $15$ % ($2,279/15,254$) with an submission accuracy score of $78$ %.

Performing analysis on this Classic Titanic Dataset required:
- EDA on the different given feature sets
- Separating out the numerical and categorical features
- Understanding the correlations between different feature sets
- Creating new feature sets by extracting relevant information
- Imputation of data
- Label Encoding, One-Hot Encoding, and Target Encoding feature sets
- Normalizing and preparing Dataset for ML
- Applying Common ML methods to the dataset including:
  - Logistic Regression
  - Support Vector Machines
  - K-Nearest Neighbor 
  - Naive Bayes
  - Stochastic Gradient Decent
  - Decision Tree
  - Random Forest


Here you can see the validation accuracies ordered by best score:

<table border="1" class="dataframe">   <thead>     <tr style="text-align: right;">       <th></th>       <th>Model</th>       <th>Score</th>     </tr>   </thead>   <tbody>     <tr>       <th>6</th>       <td>Random Forest</td>       <td>86.52</td>     </tr>     <tr>       <th>2</th>       <td>KNN</td>       <td>84.27</td>     </tr>     <tr>       <th>0</th>       <td>Logistic Regression</td>       <td>83.15</td>     </tr>     <tr>       <th>1</th>       <td>Support Vector Machines</td>       <td>83.15</td>     </tr>     <tr>       <th>4</th>       <td>Stochastic Gradient Decent</td>       <td>77.53</td>     </tr>     <tr>       <th>5</th>       <td>Decision Tree</td>       <td>77.53</td>     </tr>     <tr>       <th>3</th>       <td>Naive Bayes</td>       <td>75.28</td>     </tr>   </tbody> </table>


