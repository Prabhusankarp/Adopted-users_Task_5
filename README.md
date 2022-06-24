# Adopted-users_Task_5
Adopted users from visitors

Summary:

The objective of the model is to predict the features which determain wheather the visitor will be regular adoptive user/visiter.

207917 times the customer has visited the product. out of 207917 visitors , 8823 customer are unique users whos has visited. users with 3 logins is 2248

The visitors data is classified into adoptive user and not adotive user. Then added this feature in our dataset which is our actual objective.

Account creation feature in our data is categorical Data, so we have used "LabelEncoder()" to convert it into numerical data.

Correlation between the features is shown in heatmap.

Decision Tree algritham is used to find the important features. Therefor the data is splited into training and test dataset.

The model is able to predict the adoptive user/visiter with 88% accuracy.

The Important features is ploted in the bar garph.

The most important features to predict the adoptive user is 1."last_session_creation_time" and 2."org_id"

