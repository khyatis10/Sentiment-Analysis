# Sentiment-Analysis
Analyzing customer reviews for airplane services and trying to predict success for service provided. This code is trying to predict the sentiments of reviews column in data suing VADER pre-trained model. Further the code also shows how we can then use additional features like seat type, ratings etc to this now lablled sentiments and predict sentiments based on these additional feature to see their impact on the sentiment prediction. I am using Random Forest and XGBOOST here with corss validation to for fine tuning the model. 

The project comes handy when business want to understand what is the customer feedabck but at granuality like for food, for amenities the airplane provides, and many such drill down we can decide on by segregating our reviews to such categories the business wants to look into and then visualize which particular service has performed bad through sentiments we have predicted correctly. The more the number of the negative sentiments for given services, the more look through for this services is required. We can than include cross functional team to work together for which feature has space for improvement.

Currently this project is focused on training model to predict the reviews with additional features into three classes using pre-train model of NLTK called VADER which helps tag reviews in positive, negative, and neutral based on compound score calculated. 

Machine Learning models used are Random Forest and XGBOOST for classification problem.

## To view code 
if not able to view from here use https://nbviewer.org/ and enter full path of github path for the code.
