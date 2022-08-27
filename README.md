# Problem Setting
To predict when a customer might churn for a music company based on the user behavior of the customer and time spent on the website.
The prediction is essential for membership-based businesses because it helps in knowing how to reduce their customer churn rate by working on their services.

# Dataset details
Total instances of data is 2 million 
Dataset contains following details:
User information – userID, FirstName, Last Name, Gender, Location, User agent, Registration
Log Specific Information – Timestamp, Page, Authentication Level, Session ID, itemInSession 
Artist Details: Artist Name, Genre and Song

# Exploratory Data Analysis
We have performed data analysis by checking for any missing values and null values in the dataset. 
We have found many missing values in our data dropped those missing values. 
We have then created churn variable for the users that have opted for cancelling their subscription and analyzed the churn rate based on gender, page visits, user log activity, location, artists, browser and registration date.

# Feature Selection
Here we are selecting the important attributes that will be used for model building based on the churn analysis. 
We are selecting 10 attributes based on the proportion of churn and non-churn customers where we notice a significant difference. 
These attributes are page, artists, gender, sessionid, registration, length and playlist.

# Model Deployment
We are building supervised learning models as know the outcome of our results. 
We have used build logistic regression and gradient boosting model to predict the churn of customers and comparing their accuracy and F-score

# Results:
Most of the customers have churned because they didn’t like the songs and the songs recommended to them by them by their friends
We also see that customers that have had a long registration period have churned in high numbers




