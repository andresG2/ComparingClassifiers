### Comparing Classifiers 

Andres Garcia

#### The goal is to compare the performance of the classifiers 
(k-nearest neighbors, logistic regression, decision trees, 
and support vector machines). A dataset related to the marketing 
of bank products over the telephone.

#### Rationale
The data is related with direct marketing campaigns (phone calls) 
of a Portuguese banking institution.

#### Research Question
The classification goal is to predict if the client will subscribe 
a term deposit (variable y).

#### Data Sources
https://archive.ics.uci.edu/ml/datasets/bank+marketing

The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

There are four datasets:
1) bank-additional-full.csv with all examples (41188) and 20 inputs, ordered by date (from May 2008 to November 2010), very close to the data analyzed in [Moro et al., 2014]
2) bank-additional.csv with 10% of the examples (4119), randomly selected from 1), and 20 inputs.
3) bank-full.csv with all examples and 17 inputs, ordered by date (older version of this dataset with less inputs).
4) bank.csv with 10% of the examples and 17 inputs, randomly selected from 3 (older version of this dataset with less inputs).
The smallest datasets are provided to test more computationally demanding machine learning algorithms (e.g., SVM).

The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).

#### Methodology
We compared the performances of the classifiers we encountered in this section,
namely K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines. 
The plot of the 'Probability of Success', and others were created.

#### Results
We found that the month of March as the highest probablity of success, and May is the month 
with the least proabablity of success. 
The Job type with the highest proability of success was Student, Retired, Unemployed, and Admin.

#### Outline of project

Notepad: https://github.com/andresG2/ComparingClassifiers
Readme: https://github.com/andresG2/ComparingClassifiers


##### Contact and Further Information
andy.garcia.usa@gmail.com

