# DS-Assignment-Part-1
Problem statement :

The goal is to understand the relationship between house features and how these variables affect the house price. Using more than one model, predict the price of the house using the given dataset. Please compare the accuracy of the models along with the drawbacks of each technique's assumptions before recommending the final prediction model.

Steps involved in Analysis:

Data preprocessing Performing exploratory data analysis Building prediction model to predict the house prices Conclusion

Summary :

From EDA we found out that , There is a highly positive correlationship between House price per unit area and Number of convenience stores,latitude ,longitude. There is highly negatively correlationship between distance from nearest metro station and House price per unit area because as the distance from the metro station increases the price of house decreases

And from prediction models we found out that , Random forest regressor has given highest R2 score among all the model i.e. 68% for testing data and the important factors according to random forest model are Distance from nearest metro station ,House age,latitude,longitude and house size(sqft) As the R2 score of random forest is highest among all the models so we can use random forest to predict the house prices.

# DS-assignment-Part-2
Problem statement: Using ML/DL techniques, match similar products from the Flipkart dataset with the Amazon dataset. Once similar products are matched, display the retail price from FK and AMZ side by side. Please explore as many techniques as possible before choosing the final technique.
