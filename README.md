## Google Analytics Customer Revenue Prediction . 
### <i>Predict how much GStore customers will spend. <a href="https://www.kaggle.com/c/ga-customer-revenue-prediction">(kaggle)</a></i>
### Problem Statement
The 80/20 rule has proven true for many businesses–only a small percentage of customers produce most of the revenue. As such, marketing teams are challenged to make appropriate investments in promotional strategies.
This case study is about predicting futuristic transaction revenue per customer for the products sold in Google Store. This case study is based on 80/20 rule also known as Pareto Principle, which is quite true for diverse domains. (Pareto principle states that for many events, roughly 80% of the effects come from 20% of the causes). On similar lines of 80/20 rule, this case study aims to find those 20% customers who account for 80% of the revenue, in order to fine tune usage of marketing budgets for better targeting the revenue generating customers.

### Dataset Info
- <b>train_v2.csv ( 23.67GB )</b> - Contains user transaction data for the period Aug 1st 2016 to April 30th 2018 (638 days)
- <b>test_v2.csv ( 7.09GB )</b>– Contains user transaction data for the period May 1st 2018 to Oct 15th 2018 (168 days)
  - We have to predict log of transaction revenue of each customer for the future period Dec 1st 2018 to Jan 31st 2019(62 days)- 
- <i>fullVisitorId </i>- A unique identifier for each user of the Google Merchandise Store.
- <i>channelGrouping</i> - The channel via which the user came to the Store.
- <i>date</i> - The date on which the user visited the Store.
- <i>device</i> - The specifications for the device used to access the Store.
- <i>geoNetwork</i> - This section contains information about the geography of the user.
- <i>socialEngagementType</i> - Engagement type, either "Socially Engaged" or "Not Socially Engaged".
- <i>totals</i> - This section contains aggregate values across the session like pagviews, hits.
- <i>trafficSource</i> - This section contains information about the Traffic Source from which the session originated.
- <i>visitId</i> - An identifier for this session. This is part of the value usually stored as the _utmb cookie. This is only unique to the user. For a completely unique ID, you should use a combination of fullVisitorId and visitId.
- <i>visitNumber</i> - The session number for this user. If this is the first session, then this is set to 1.
- <i>visitStartTime</i> - The timestamp (expressed as POSIX time).
- <i>hits</i> - This row and nested fields are populated for any and all types of hits. Provides a record of all page visits.
- <i>customDimensions</i> - This section contains any user-level or session-level custom dimensions that are set for a session. This is a repeated field and has an entry for each dimension that is set.

### Evaluation Metric
Root Mean Square Logarithmic Error

###  Blog
https://medium.com/@gsrinivas/google-analytics-customer-revenue-prediction-be5f9d0d9c63
