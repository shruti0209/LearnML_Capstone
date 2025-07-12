### Lookalike Customer Analysis 

**Shruti Jain**

#### Executive summary
Find and target look-alike customers to increasing feature adoption and measure its impact on customer satisfaction 

#### Rationale
Lookalike analysis is widely used in business to find and target new customers who resemble high-value existing customers. For example, 
1. New customer acquisition - Finding lookalikes of existing high-value customers to target for acquisition
2. Preventing churn/attrition - Finding looksalikes of customers who have attrited in the past to prevent their attrition (as they are likely at higher risk of attrition)
3. Feature adoption - Finding alikealikes of new product adopters to increase adoption within non-adopters 


#### Research Question
I am a data scientist for a tech company. Our product team has launched a new feature that is currently used by a small number of customers. Our customers are small business owners. We are looking to increase the adoption of the feature by more customers. Below are some of the questions I need to solve through my analysis:

1. Find the look-alike customers within our customer base that are currently not using this feature but could be targeted through our marketing
2. Find out if adoption of new feature increases customer satisfaction (by comparing at customer satisfaction score for those that adopted vs those that didn't adopt). This could be used by product team as a measure of impact of the feature or could be used by marketing to place marketing claims to promote the feature
3. Describe what attributes or product features drive higher adoption of new features. This will inform future product development roadmap as suggest the profile of customers likely to adopt new features. 

#### Data Sources
I have simulated product usage for customers (small business onwers) who use our product. The data can be found [here](https://github.com/shruti0209/LearnML_Capstone/blob/main/data/simulated_product_usage_data.csv). 

#### Methodology
Following techniques are used in the analysis: 
1. Build supervised models like Logistic Regression, Random Forest, LGBM, XGBoost and Neural Network for flagging look-alike customers using propensity scores
2. Observe feature importance of the best model to identify attributes that have most influence on feature adoption 
3. Use Causal Inference Techniques like Propensity Score Matching (PSM) to compare satisfaction scores of those that used the features to comparable customers who didn't use the feature 

#### Results
What did your research find?

#### Next steps
What suggestions do you have for next steps?

#### Outline of project

- [Link to notebook 1](https://github.com/shruti0209/LearnML_Capstone/blob/main/Lookalike_Analysis.ipynb) 


##### Contact and Further Information
