# client_credit-card_ML_problem


## Introduction
This notebook was created for analysis and prediction making of the Default of credit card clients Data Set from UCI Machine Learning Library. The data set can be accessed separately from the UCI Machine Learning Repository page, [here](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients).





## Relevant Papers
In their paper "The comparisons of data mining techniques for the predictive accuracy of probability of default of credit card clients. (Yeh I. C. & Lien C. H.,2009)", which can be found [here](https://bradzzz.gitbooks.io/ga-dsi-seattle/content/dsi/dsi_05_classification_databases/2.1-lesson/assets/datasets/DefaultCreditCardClients_yeh_2009.pdf), Yeh I. C. & Lien C. H. review six data mining techniques (discriminant analysis, logistic regression, Bayesclassifier, nearest neighbor, artificial neural networks, and classification trees) and their applications on credit scoring. Then, using the real cardholders’ credit risk data in Tai-wan, they compare the classification accuracy among them.







## Attribute Information
        Below there are the description of the attributes that will be used in our model for better understanding of the data:

        LIMIT_BAL: Amount of the given credit (NT dollar). It includes both the individual consumer credit and his/her family (supplementary) credit.
        SEX: Gender ( male;  female).
        EDUCATION: Education ( graduate school; university; high school; others).
        MARRIAGE: Marital status ( married; single;others).
        AGE: Age (year).
        PAY_1: the repayment status in September, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for         two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
        PAY_2: the repayment status in August, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two         months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
        PAY_3: the repayment status in July, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two            months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
        PAY_4: the repayment status in June, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two           months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
        PAY_5: the repayment status in May, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two           months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
        PAY_6: the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two         months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
        BILL_AMT1: Amount of bill statement (NT dollar). Amount of bill statement in September, 2005.
        BILL_AMT2: Amount of bill statement (NT dollar). Amount of bill statement in August, 2005.
        BILL_AMT3: Amount of bill statement (NT dollar). Amount of bill statement in July, 2005.
        BILL_AMT4: Amount of bill statement (NT dollar). Amount of bill statement in June, 2005.
        BILL_AMT5: Amount of bill statement (NT dollar). Amount of bill statement in May, 2005.
        BILL_AMT6: Amount of bill statement (NT dollar). Amount of bill statement in April, 2005.
        PAY_AMT1: Amount of previous payment (NT dollar). Amount paid in September, 2005.
        PAY_AMT2: Amount of previous payment (NT dollar). Amount paid in August, 2005.
        PAY_AMT3: Amount of previous payment (NT dollar). Amount paid in July, 2005.
        PAY_AMT4: Amount of previous payment (NT dollar). Amount paid in June, 2005.
        PAY_AMT5: Amount of previous payment (NT dollar). Amount paid in May, 2005.
        PAY_AMT6: Amount of previous payment (NT dollar). Amount paid in June, 2005.
        dpnm: Default payment next month.(Yes = 1, No = 0)
