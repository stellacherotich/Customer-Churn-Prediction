# <b> SYRIATEL CHURN ANALYSIS </b>

#### Author : Stella Kitur
--- 
# <b> Project Overview </b>
The objective of this project was to develop a binary classification model to predict whether a customer of SyriaTel, a telecommunications company, is likely to stop doing business in the near future. The primary goal was to identify predictable patterns in customer behavior in order to help the company reduce financial losses associated with customer churn.
<b> Stakeholder </b>: SyriaTel 
## <b> Business Understanding </b>

Customer churn has emerged as a critical concern for companies like SyriaTel in the fiercely competitive telecommunications industry. With customers having numerous options and increasing expectations, retaining existing customers has become paramount. 
Churn not only leads to immediate revenue loss but also exerts significant pressure on customer acquisition costs. Understanding the factors that contribute to churn and being able to predict it with accuracy is crucial for telecom businesses to develop effective retention strategies. By analyzing historical customer data, telecom companies can gain valuable insights into customer behavior, preferences, and interactions, enabling them to identify potential churners and tailor retention efforts accordingly and proactively.
This proactive approach minimizes revenue loss and enhances customer satisfaction, loyalty, and overall business performance.
### <b> Problem Statement </b>
SyriaTel would like to maintain/increase the customer retention rate as 

### <b> Objectives </b>
The objective of this analysis is to:
1. Develop a highly accurate binary classification model that predicts customer churn for SyriaTel.
2. Identify predictable patterns and insights in customer behavior to proactively identify customers at a high risk of churning.
3. Enable SyriaTel to optimize retention strategies, allocate resources effectively, and minimize financial losses associated with customer churn.


#### <b> Metrics of Success </b>
In this model, the metrics of success are outlined as follows :


## <b> Data Understanding </b>
The SyriaTel Dataset was retrieved from Kaggle and can be found here. 
The original dataset contains 3333 rows and 21 columns. The columns included information that is associated with features of the customer information such as:

        state
        account length
        area code
        phone number  
        international plan
        voice mail plan 
        number vmail messages
        total day minutes 
        total day calls 
        total day charge 
        total eve minutes 
        total eve calls            
        total eve charge           
        total night minutes
        total night calls
        total night charge
        total intl minutes
        total intl call
        total intl charge
        customer service calls
        churn
        total expenditure

To understand the data further, EDA (Exploratory Data Analysis) was conducted especially looking at the target variable which was churn, and how other variables influenced it.

Additionally, a correlation matrix was made in order to see what features were highly correlated.