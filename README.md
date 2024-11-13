# Final-Capstone-Project-mod24
Final Capstone project Module 24

# Identifying the customers/prospects who will opt out of a marketing campaign.

__Subra Sundaram__

## Problem
Identify the members from the mailing list who have a high probability of opting out of the mailing list, based on the history of others who have opted out in the past.

## Results
The model created during the Captstone project can predict members who will opt out with 99.88% accuracy with a Logistic Regression model. While this seems high, please note that if the algorithm had predicted that every member would not opt out, it would still be correct 93.7% percent of the time. The reason for this is that our input data is skewed, and we have only a few opt out records (1642 records) versus non opt out records (24,722 records = 93.7%).


## Important findings
1.	Only about 10 pieces of information had a high impact on whether a member would opt out or not. These included factors such as specific values in the Email status field (“Unengaged Marketable”, “List Unsubscribe”, etc.), and Lead Source (“social”, “NoneSelected”, etc.). Other factors didn’t have much effect on the outcome.
2.	We should be able to predict the members who would opt out with much more accuracy in the future. The current model’s 93.8% prediction accuracy was surprising and very encouraging.
3.	Even though the data was very sparse, it was enough to predict whether a member would opt out of any future email campaigns or not.



## Suggestions for next steps
1.	The data should be further cleaned up and put through the modeling process again.
2.	Other algorithms such as Bayesian optimization should be tried, as they are more amenable to such data and output predictions.
3.	Since the data is unbalanced now it would be good to oversample the existing “opt out” candidates (i.e duplicate them with small changes to their data) so that the opt out vs non opt out records are equal in number.
4.	Other possibility is also to see which of the members would engage more with the program.
 
