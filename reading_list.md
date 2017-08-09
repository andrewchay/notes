This file tracks all my readings by categories. My comment will be in <span style="color:blue">blue</span>.

# Statistics
## Causal Inference
|Document Name   	|Source   	|Reading Status   	|Category   	|Key Summary   	|Link to Detailed Summary    |
|---	|---	|---	|---	|---	|---  |
|Causal inference in statistics: An overview   	|[link](doi:10.1214/09-SS057)   	|ongoing to section 3.3   	|statistics, causal inference   	|high level causal inference introduction with SEM, d-separation, back door algorithm   	|     |
|Lean Analytics   	|   	|ongoing to chapter 6   	|business analytics, startup   	|aquisition, activation, retention, revenue, referral model, one metric that matters   	|     |
|Lean Analytics   	|ongoing to chapter 13   	|business analytics   	|discussed different models in media site, user-generated content site, two-sided company. Learned the conversion funnel, three types of revenues from ads(display, click, affiliate).   	|   	|     |
|   	|   	|   	|   	|   	|     |
|   	|   	|   	|   	|   	|     |
|   	|   	|   	|   	|   	|     |
|   	|   	|   	|   	|   	|     |
|   	|   	|   	|   	|   	|     |

# Some SQL Notes:

INSERT INTO tblCustomers (CustomerID, [Last Name], [First Name])
VALUES (1, 'Kelly', 'Jill')

UPDATE table name 
SET field name = some value

DELETE FROM tblInvoices
WHERE InvoiceID = 3
# Supervised Machine Learning
## Naive Bayesian
In Naive Bayesian method, the classification is achieved by choosing the class that has the largest posterior probability as $P(C_k|x) = P(x|C_k)P(C_k)/P(x)$.
## SVM
For hard margin problem, the key is to minimize $||w||$ subject to $y(wx + b) >= 1$. The soft margin problem is to minimize $1/n\sum_{i=1}^n\max(0, 1-y(wx + b)) + \lambda||w||^2.$ SVM is an extension of perceptron as can be seen from the hinge loss function.
## Decision Tree
## Random Forest