![Credit_Card_Customer_Attrition_Analysis](screenshots/cover-banner.png)
## Credit Card Customer Attrition: Diagnostic and Early Warning Analysis

### Business Question
#### How can we identify and prevent customer churn before it actually happens?

### Dataset
[Credit Card customers](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)

### Tools
- Power BI
- Power Query (M)
- DAX

### Dashboard Pages
1. Executive Overview
![Executive Overview](screenshots/Page-1-Executive-Overview.png)
### Key Insights
Page 1:
- Customer activity is declining at scale, with most customers transacting less than the prior quarter
- Disengagement precedes churn - activity drops are widespread while attrition remains moderate
- Credit stress is not the driver - utilization is healthy and high-utilization customers are rare
- Inactivity is rising among declining customers, confirming early-stage disengagement

2. Attrition Risk Drivers
![Attrition Risk Drivers](screenshots/Page-2-Attrition-Risk-Drivers.png)
### Key Insights
Page 2:
- Sharp declines in transaction activity are the strongest indicator of churn, with severe drops showing significantly higher attrition rates
- Customers often churn while still recently active, indicating that attrition begins with early disengagement rather than prolonged inactivity
- Moderate credit utilization is associated with the lowest attrition, while both low-use and near-limit customers show elevated churn risk, suggesting different churn mechanisms
- Customer tenure has only a marginal impact on attrition, reinforcing that behavioral changes matter more than lifecycle stage

3. Early Warning Signal Identification
![Early Warning Signal Identification](screenshots/Page-3-Early-Warning-Signal-Identification.png)
### Key Insights
Page 3:
- Declining transaction activity is the earliest and strongest attrition signal, regardless of credit utilization level
- Credit utilization does not show a linear relationship with activity decline, indicating that churn risk is driven more by disengagement than by credit stress
- High-risk customers cluster in declining activity segments, with high utilization amplifying risk but affecting a smaller population

### Business Recommendation
- Target behavioral drops: launch retention offers immediately when transaction volume dips below 80% of the previous quarter. Don't wait for total inactivity
- Try a limited-time points booster or cashback offer for the declining + low-moderate utilization before they disappear entirely: since they have plenty of available credit, they don't need a limit increase
- Optimize utilization: target low-use customers with "Spend and Get" promos to move them into the stable-moderate utilization bracket
- Watch the quiet ones: customers with a sharp drop in activity are the biggest risk, even if they don't have high credit balances
