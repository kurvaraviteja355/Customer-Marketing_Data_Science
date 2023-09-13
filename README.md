# Marketing_Data_Science

Assume you work in marketing and want to see if your advertising investments were worthwhile. In order to find the worth of marketing channels, we can use **Media Mixing model(MMM)**.

**MMM** will tell you which advertising factor is driving your sales. I have also covered **Bayesian marketing mix modeling**, a way to get more robust models and uncertainty estimates for everything you forecast.

I also included the Causal inference using **Pymc** and **Google Bayesian** python package 

## Measurement of Campaign treatment 

**Problem statment** (Casual_inference_casestudy.ipynb)
The company is rapidly expanding, and the marketing team is looking for ways to enhance sales from existing customers by encouraging them to purchase more. The fundamental idea is to use incentives, in this case a discount to unlock the potential of the client base. Of course, we want to know how the discount affected the customer's behavior. Nonetheless, they do not want to waste money by providing ineffective discounts to people. It is always about return on investment (ROI).

**Offline campaign Measurment** (ATE_ measurement_offine_campaign.ipynb)
Based paper [Estimating Ad Effectiveness Using Geo Experiments in a Time-Based Regression](https://research.google/pubs/pub45950/), I implemented time-based regression (TBR) approach to measuring of offline marketing campaign analysis in the context of geo experimentation.

## CLV : Customer Lifetime Value
"understanding and acting on customer lifetime value (CLV) is the most important part of your business’s sales efforts
