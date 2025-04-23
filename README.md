📦 **Sales Method Analysis**<br>
A data-driven project that explores and analyzes sales performance to uncover trends, evaluate performance metrics, 
and identify strategic opportunities for growth.<br>
<br>
🧭 **Objective**<br>
The main objectives of this project are:<br>
-To select the most effective sales method that allows the company to minimize efforts while maximizing revenue.<br>
-To provide actionable recommendations for stakeholders<br>
<br>
📁 **Dataset Overview**<br>
The dataset typically includes the following columns:<br>
**week**: Week<br>
**sales_method**: Sales methods consist of "Email", "Call" and "Email + Call" method<br>
**customer_id**: Customer ID<br>
**nb_sold**: Number of new product sold<br>
**revenue**: Revenue<br>
**years_as_customer**: Years as customer <br>
**nb_site_visits**: Number of website visits<br>
**state**: State<br>
<br>
**NOTE** : Each visualization which contain "Total Revenue" metric has been confirmed to have no significant difference between imputing and non-imputing.<br>
Also, 2 additional columns have been added by transforming the provided data.<br>
**conversion rate** : This column represents the ratio of nb_sold to nb_site_visits. It describes how many products were purchased by customers relative to the number of website visits.<br>
**years_group** : This column groups customer loyalty duration into 5-year per group.<br>
<br>
🔧 **Tools & Technologies**<br>
-Python (Pandas, NumPy, Matplotlib, Seaborn)<br>
-Datalab (supported by Datacamp)<br>
-Excel/CSV for initial data format<br>
<br>
📈 **Key Analyses Performed**<br>
-Time Series Analysis: Weekly revenue and conversion rate trends by sales method<br>
-Sales frequency by sales method and years as customer<br>
-Revenue distribution<br>
-Demographic Insights on Revenue<br>
<br>
Check notebook here : https://www.datacamp.com/datalab/w/77f3cf21-54be-4e71-a6d1-47ebd288e46e#sales-methods-analysis<br>
