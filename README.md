# Bank Telemarketing Predictive Analysis
Academic group project utilizing R to perform predictive analysis on the effectiveness of bank telemarketing campaigns. Dataset is from UCI machine learning repository, featuring over 45k observations. Raw code is included after the report section within the uploaded PDF.

### Overview
Our goal was to conduct a thorough exploration of our selected dataset to identify key factors that drive client subscriptions as well as evaluate the effectiveness of these telemarketing campaigns overall by utilizing three relevant classification models; k-nearest neighbors, logistic regression, and a classification tree. 

#### Business Question: Can we predict if a client will subscribe to a term deposit based on demographic variables and previous marketing campaign outcomes?

### Dataset Information
Source: https://archive.ics.uci.edu/dataset/222/bank+marketing

Contains 45,211 observations and 17 variables (16 input + 1 output). Our target variable was the outcome of whether a client subscribes or not in a specific instance (yes/no). Since our target variable is binary in nature, we elected to utilize classification modeling as opposed to regression modeling since we are measuring discrete values.

| Model | Accuracy | Sensitivity | Specificity |
|---|---|---|---|
| K-Nearest Neighbors | 89.8% | 28.4% | 98.0% |
| Logistic Regression | 90.0% | 35.1% | 97.4% |
| Classification Tree | 90.3% | 46.0% | 96.1% |

### Key Findings 

- Call duration showed the strongest separation between subscribers and non-subscribers. Those who subscribed had substantially longer calls on average .

- Campaign contacts are slightly lower for subscribers, and over-contacting is associated with reduced conversion.  

- Account balance and age show modest differences between groups but are not strongly strong correlators on their own  .
