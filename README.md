
# Customer Churn Prediction

![0_0m_FbTEaOTxwddVk](https://user-images.githubusercontent.com/100334542/178119768-46e0460f-d10e-4a0a-bedc-b28a6a5afcb7.gif)


Churn prediction means detecting which customers are likely to leave a service or to cancel a subscription to a service. It is a critical prediction for many businesses because acquiring new clients often costs more than retaining existing ones. Once you can identify those customers that are at risk of cancelling, you should know exactly what marketing action to take for each individual customer to maximise the chances that the customer will remain.

![image](https://user-images.githubusercontent.com/100334542/176241355-838a431d-9d2d-4225-bafc-03fca93d70d0.png)
## Data 

I have used the Telco Customer Churn dataset which is available on Kaggle.
👇👇👇

https://www.kaggle.com/datasets/blastchar/telco-customer-churn



## Required Libaries

1.Numpy

2.Pandas

3.Matplotlib

4.Seaborn

5.Sklearn

6.Tensorflow

7.Keras

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

