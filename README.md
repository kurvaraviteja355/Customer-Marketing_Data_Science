# Customer-Marketing_Data_Science

Assume you work in customer intelligence or marketing tech want to see if your advertising investments were worthwhile or user behavior trends to improve customer retention/customer segmention to target campaigns. 

**MMM** will tell you which advertising factor is driving your sales. I have also covered **Bayesian marketing mix modeling**, a way to get more robust models and uncertainty estimates for everything you forecast.

For customer retention, we can use cohort retention analysis techniques to learn about user behavior 

I also included the Causal inference using **Pymc** and **Google Bayesian** python package 

## Measurement of Campaign treatment 

**Problem statment** (Casual_inference_casestudy.ipynb)
The company is rapidly expanding, and the marketing team is looking for ways to enhance sales from existing customers by encouraging them to purchase more. The fundamental idea is to use incentives, in this case a discount to unlock the potential of the client base. Of course, we want to know how the discount affected the customer's behavior. Nonetheless, they do not want to waste money by providing ineffective discounts to people. It is always about return on investment (ROI).

**Offline campaign Measurment** (ATE_ measurement_offine_campaign.ipynb)
Based paper [Estimating Ad Effectiveness Using Geo Experiments in a Time-Based Regression](https://research.google/pubs/pub45950/), I implemented time-based regression (TBR) approach to measuring of offline marketing campaign analysis in the context of geo experimentation.


 ## Uplift Modeling (uplift_Model.ipynb)
 
Maximizing the incremental return of your marketing campaigns

**Problem Statement** : Image your marketing team/department wanted a model that could distinguish between customers who would respond positively to a marketing campaign (Responders) and those who would respond negatively if left untreated but positively if targeted (Anti-Responders). In other words, they sought a way to maximize the incremental impact of their marketing efforts.

Uplift modeling, a magical technique, promised to unveil the true impact of marketing interventions on individual customers. It aimed not just to predict who would respond positively to a campaign, but more importantly, who would respond better if treated compared to not being treated.

## CLV : Customer Lifetime Value
"understanding and acting on customer lifetime value (CLV) is the most important part of your business’s sales efforts

## Cohort Rentension Analysis (cohort_rentention_analysis.ipynb)
Cohort retention analysis helps teams understand how well their product is engaging and retaining different groups of users over time. This information can be used to improve the product and customer experience, and to make better business decisions.

## Estimating Causal Impacts when is no control groups using quasi-experimental methods (Causal-impact_synthetic-controls.ipynb)




