# New_user_engagment
## problem defintion
we try to maximize the engagment of the user by predicting who will be engage in the website next month


Zindi is nothing without our users - you are the fuel in the rocket ship, the reason we do what we do. To make sure we are always providing the best possible user experience, we need to know if users will return to Zindi in their second month after signing up. We believe that if a user is constantly active at the start of their Zindi journey, this means that they are seeing value and will stick around. This is a good thing for us and for our users, as an active and healthy community means that we are adding value.
The objective of this challenge is to predict if a new user from a selected cohort will engage with Zindi in their second month on the platform. For example, if a user joined in June, will they be active in July?

This solution will help us establish and track our performance as a data science community and platform, and make sure that we are best serving the needs of you, our users! Help us make Zindi better for all of you.

The error metric for this competition is the F1 score, which ranges from 0 (total failure) to 1 (perfect score). Hence, the closer your score is to 1, the better your model.

F1 Score: A performance score that combines both precision and recall. It is a harmonic mean of these two variables. Formula is given as: 2*Precision*Recall/(Precision + Recall)
Precision: This is an indicator of the number of items correctly identified as positive out of total items identified as positive. Formula is given as: TP/(TP+FP)
Recall / Sensitivity / True Positive Rate (TPR): This is an indicator of the number of items correctly identified as positive out of total actual positives. Formula is given as: TP/(TP+FN)

Where:
TP=True Positive
FP=False Positive
TN=True Negative
FN=False Negative
This challenge has a rolling leaderboard. This means you will need to constantly build on your model. We will be rolling out new user and competition information each month to simulate a real model development pipeline as you receive new data. The final users you will need to predict for are users created in months 5 and 6.

