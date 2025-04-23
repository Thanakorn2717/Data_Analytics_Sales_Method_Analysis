📦 **Sales Method Analysis**
A data-driven project that explores and analyzes sales performance to uncover trends, evaluate performance metrics, 
and identify strategic opportunities for growth.

🧭 **Objective**
The main objectives of this project are:
-To select the most effective sales method that allows the company to minimize efforts while maximizing revenue.
-To provide actionable recommendations for stakeholders

📁 **Dataset Overview**
The dataset typically includes the following columns:
**week**: Week
**sales_method**: Sales methods consist of "Email", "Call" and "Email + Call" method
**customer_id**: Customer ID
**nb_sold**: Number of new product sold
**revenue**: Revenue
**years_as_customer**: Years as customer 
**nb_site_visits**: Number of website visits
**state**: State

**NOTE** : Each visualization which contain "Total Revenue" metric has been confirmed to have no significant difference between imputing and non-imputing.
Also, 2 additional columns have been added by transforming the provided data.
**conversion rate** : This column represents the ratio of nb_sold to nb_site_visits. It describes how many products were purchased by customers relative to the number of website visits.
**years_group** : This column groups customer loyalty duration into 5-year per group.

🔧 **Tools & Technologies**
-Python (Pandas, NumPy, Matplotlib, Seaborn)
-Datalab (supported by Datacamp)
-Excel/CSV for initial data format

📈 **Key Analyses Performed**
-Time Series Analysis: Weekly revenue and conversion rate trends by sales method
-Sales frequency by sales method and years as customer
-Revenue distribution
-Demographic Insights on Revenue

Check notebook here : https://www.datacamp.com/datalab/w/77f3cf21-54be-4e71-a6d1-47ebd288e46e#sales-methods-analysis
