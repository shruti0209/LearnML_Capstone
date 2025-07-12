### Lookalike Customer Analysis 

**Shruti Jain**

#### Executive summary
Find and target lookalike customers to increasing feature adoption and measure its impact on customer satisfaction 

#### Rationale
Lookalike analysis is widely used by businesses to find and target new customers who resemble high-value existing customers. For example, 
1. New customer acquisition - Finding lookalikes of existing high-value customers to target for acquisition
2. Preventing churn/attrition - Finding lookalikes of customers who have attrited in the past to prevent their attrition (as they are likely at higher risk of attrition)
3. Feature adoption - Finding lookalikes of new product adopters to increase product adoption within non-adopters 


#### Research Question
I am a data scientist for a tech company. Our product team has launched a new feature that is currently used by a small number of customers. Our customers are small business owners. We are looking to increase the adoption of the feature by more customers. Below are some of the questions I need to solve through my analysis:

1. Find the lookalike customers within our customer base that are currently not using this feature but could be targeted through our marketing
2. Find out if adoption of new feature increases customer satisfaction (by comparing customer satisfaction score for those that adopted vs those that didn't adopt). This could be used by product team as a measure of impact of the feature or could be used by marketing to place marketing claims to promote the feature
3. Describe what attributes or product features drive higher adoption of new features. This will inform future product development roadmap and suggest the profile of customers likely to adopt new features. 

#### Data Sources
I have simulated product usage for customers (small business owners) who use our product. The data can be found [here](https://github.com/shruti0209/LearnML_Capstone/tree/main/data). 

#### Methodology
Following techniques are used in the analysis: 
1. Build supervised models like Logistic Regression, Random Forest, LGBM, XGBoost and Neural Network for flagging lookalike customers using propensity scores
2. Observe feature importance of the best model to identify attributes that have most influence on feature adoption 
3. Use Causal Inference Techniques like Propensity Score Matching (PSM) to compare satisfaction scores of those that used the features to comparable customers who didn't use the feature 

#### Results
1. Logistic regression proved to be the best model based on AUC and Accuracy Scores
2. Past product engagement with key features were most influencial attributes indicative of future adoption of new features
3. Adoption of new feature in question didn't appear to drive higher satisfaction amongst customers that adopted the feature 

#### Next steps
Prepare a non-techical report for business audience 

#### Outline of project

- [Link to notebook 1](https://github.com/shruti0209/LearnML_Capstone/blob/main/Lookalike_Analysis.ipynb) 


##### Contact and Further Information
Reach out to shruti0209@gmail.com for further questions and suggestions with respect to the analysis 

