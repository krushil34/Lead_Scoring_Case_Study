# Lead Scoring Case Study

## Problem Statement

X Education, an online course provider for industry professionals, faces challenges in improving its lead conversion rate. While the company generates many leads daily through websites, search engines, and referrals, only about 30% of these leads convert into paying customers.

The company seeks to improve this conversion rate by identifying and prioritizing high-potential leads—referred to as 'Hot Leads'. By focusing the sales team's efforts on these leads, X Education aims to achieve a target lead conversion rate of approximately 80%.

A typical lead conversion process can be visualized as a funnel:

- The initial stage has many leads entering the pipeline.
- In the middle stage, potential leads need nurturing through communication, product education, and engagement.
- The final stage converts the most promising leads into paying customers.

To streamline this process, the company requires a predictive model that assigns a Lead Score to each lead, indicating their likelihood of conversion. Higher scores will enable the sales team to focus their efforts more efficiently.

## Data Description

The dataset provided by X Education contains 9,000+ data points with several attributes, including:
- Lead Source
- Total Time Spent on Website
- Total Visits  
- Last Activity

The target variable is 'Converted', where:

- 1 indicates the lead converted into a customer.
- 0 indicates the lead did not convert.

### Data Challenges

1.ome categorical variables include a level called 'Select', which is equivalent to missing or null data and must be addressed during preprocessing.

2.The dataset includes both categorical and numerical variables, requiring appropriate feature engineering and encoding techniques.

## Goals of the Case Study:

- There are quite a few goals for this case study.

- Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted. There are some more problems presented by the company which your model should be able to adjust to if the company's requirement changes in the future so you will need to handle these as well. These problems are provided in a separate doc file. Please fill it based on the logistic regression model you got in the first step. Also, make sure you include this in your final PPT where you'll make recommendations.

## Results Expected:

- A well-commented Jupyter note with at least the logistic regression model, the conversion predictions and evaluation metrics. The word document filled with solutions to all the problems. The overall approach of the analysis in a presentation Mention the problem statement and the analysis approach briefly Explain the results in business terms Include visualisations and summarise the most important results in the presentation A brief summary report in 500 words explaining how you proceeded with the assignment and the learnings that you gathered.
