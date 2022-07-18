
# Customer Churn Prediction

### Did you know that attracting a new customer costs five times as much as keeping an existing one?

![0_0m_FbTEaOTxwddVk](https://user-images.githubusercontent.com/100334542/178119768-46e0460f-d10e-4a0a-bedc-b28a6a5afcb7.gif)

## Introduction:

Churn prediction means detecting which customers are likely to leave a service or to cancel a subscription to a service. It is a critical prediction for many businesses because acquiring new clients often costs more than retaining existing ones. Once you can identify those customers that are at risk of cancelling, you should know exactly what marketing action to take for each individual customer to maximise the chances that the customer will remain.

Customer churn is defined as when customers or subscribers discontinue doing business with a firm or service.

Customers in the telecom industry can choose from a variety of service providers and actively switch from one to the next. The telecommunications business has an annual churn rate of 15-25 percent in this highly competitive market.

Individualized customer retention is tough because most firms have a large number of customers and can't afford to devote much time to each of them. The costs would be too great, outweighing the additional revenue. However, if a corporation could forecast which customers are likely to leave ahead of time, it could focus customer retention efforts only on these "high risk" clients. The ultimate goal is to expand its coverage area and retrieve more customers loyalty. The core to succeed in this market lies in the customer itself.

Customer churn is a critical metric because it is much less expensive to retain existing customers than it is to acquire new customers.

![image](https://user-images.githubusercontent.com/100334542/179591589-4aa4c943-8700-4acb-8f2d-eb0656da0ff5.png)

#### To reduce customer churn, companies need to predict which customers are at high risk of churn.

To detect early signs of potential churn, one must first develop a holistic view of the customers and their interactions across numerous channels, including store/branch visits, product purchase histories, customer service calls, Web-based transactions, and social media interactions, to mention a few.

As a result, by addressing churn, these businesses may not only preserve their market position, but also grow and thrive. More customers they have in their network, the lower the cost of initiation and the larger the profit. As a result, the company's key focus for success is reducing client attrition and implementing effective retention strategy.

## Data 

I have used the Telco Customer Churn dataset which is available on [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Required Libaries

1.[Numpy](https://github.com/numpy/numpy)

2.[Pandas](https://github.com/pandas-dev/pandas)

3.[Matplotlib](https://github.com/matplotlib/matplotlib)

4.[Seaborn](https://github.com/mwaskom/seaborn)

5.[Sklearn](https://github.com/scikit-learn/scikit-learn)

6.[Tensorflow](https://github.com/tensorflow/tensorflow)

7.[Keras](https://github.com/keras-team/keras)

### The data set includes information about:

         **1.Customers who left within the last month** – the column is called Churn

         **2.Services that each customer has signed up for** – phone, multiple lines, internet, online security, online backup, device protection, tech support, and  
         streaming TV and movies

         **3.Customer account information** - how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges

         **4.Demographic info about customers** – gender, age range, and if they have partners and dependents
        
#### The target the we will use to guide the exploration is Churn



### Get Correlation of "Churn" with other variables
![download (3)](https://user-images.githubusercontent.com/100334542/176256931-0b13c3db-9ec9-4701-99ec-87fb995a971f.png)

Month to month contracts, absence of online security and tech support seem to be positively correlated with churn. While, tenure, two year contracts seem to be negatively correlated with churn.

Interestingly, services such as Online security, streaming TV, online backup, tech support, etc. without internet connection seem to be negatively related to churn.

We will explore the patterns for the above correlations below before we delve into modelling and identifying the important variables.

### Some plotting of churn with respect to tenure,monthly charges and Senior citization

![image](https://user-images.githubusercontent.com/100334542/176259502-4bcf9069-6d23-40d8-9c12-5e1c35eba03a.png)


![image](https://user-images.githubusercontent.com/100334542/176259561-1ba497de-a6ed-4b0b-9f35-d9faea1822c9.png)


![image](https://user-images.githubusercontent.com/100334542/176259605-655a043c-1e32-45aa-942a-8dc5f7d885b3.png)

##Accuracy of the model using variouus model

1.Logistic Regression 👉👉👉👉  0.8038379530916845

2.SVM 👉👉👉👉 0.8045486851457001

3.ANN 👉👉👉👉 0.78

## Conclusion

We went through the various tasks involved in Churn prediction in this article. It is important to note that finding patterns in Exploratory Data Analysis (EDA) is as important as the final prediction itself.

A Churn prediction task remains unfinished if the data patterns are not found in EDA. Most people can do the prediction part but struggle with data visualization and conveying the findings in an interesting way.

This skill is not only limited to Churn prediction but will also help you in the solving of the usual data science problems.

