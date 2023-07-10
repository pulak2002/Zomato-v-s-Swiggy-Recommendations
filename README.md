# A-comparative-Analysis-between-Zomato-Swiggy
Zomato and Swiggy data helps customers choose the best food ordering app. Compare companies and let customers decide. Clean, imputed, pre-processed data improve comparability. Profitability gains. Sandbox datasets include cuisine, table reservations, two-person cost, famous dishes, and more. Visualising price, quality, and cuisine helps.
The work consists of analyzing and comparing data from Zomato and Swiggy to help customers choose the best app for ordering food. Based on this, we will compare different elements of the both the companies and let the customer choose the best in different scenarios. The data must first be cleaned, certain values must be imputed (if necessary), and the data must be pre-processed in order to have better comparability. This will assist the organization in analyzing the variables influencing the value of its business. The dataset(s) under consideration for the sandbox contain a wide range of features, such as cuisine type, table reservations, average cost for two people, well-known culinary items, and much more. All these characteristics can assist in predicting a better visualization, assisting customers in selecting the pricing, food quality, and culinary style.

## 1.	OBJECTIVES AND GOALS
-	Create a data analytics tool which will help in analyzing the food delivering platforms.
-	Provide insight on the food delivering platforms.
-	Being able to provide the best app for the situations.
-	To able to suggest restaurants based on the user’s order amount and cuisine choice.
-	To reduce the time for user to order the food.
-	Providing relevant information to the questions by the user .

## 2.	APPLICATIONS
-	Choosing the food delivering app
-	Choosing the restaurant

## 3.	FEATURES

-	Plots to understand the difference between each app.
-	Statistics to differentiate between restaurants
-	Ratings of the cuisines in various restaurants.
-	Suggest restaurants based on their delivering time 

## 4. DATASET


### Zomato Dataset

The collected data has been stored in a csv file . Each restaurant in the dataset is uniquely identified by its Restaurant Id. Every Restaurant contains the following variables:

• Restaurant Id: Unique id of every restaurant across various cities of the world
• Restaurant Name: Name of the restaurant
• Country Code: Country in which restaurant is located
• City: City in which restaurant is located
• Address: Address of the restaurant
• Locality: Location in the city
• Locality Verbose: Detailed description of the locality
• Longitude: Longitude coordinate of the restaurant's location
• Latitude: Latitude coordinate of the restaurant's location
• Cuisines: Cuisines offered by the restaurant
• Average Cost for two: Cost for two people in different currencies 👫
• Currency: Currency of the country
• Has Table booking: yes/no
• Has Online delivery: yes/ no
• Is delivering: yes/ no
• Switch to order menu: yes/no
• Price range: range of price of food
• Aggregate Rating: Average rating out of 5
• Rating color: depending upon the average rating color
• Rating text: text based on rating of rating
• Votes: Number of ratings casted by people.



###  Swiggy Dataset

This dataset contains swiggy registered restaurants details of major metropolitan cities of India. In this dataset it contains the swiggy past orders and restaurants in cities such as  
Mumbai Bangalore 
Hyderabad 
Ahmedabad 
Pune 
Surat 
Delhi 
Kolkata 
Chennai 
The Swiggy dataset contains variables such as:

·	Restaurant Name
·	Category
·	Rating	
·	Cost for two	Veg	
·	city	
·	Area	
·	Locality	
·	Address	
·	Long Distance Delivery.



## 5.  ALGORITHM used

Support Vector Machine Algorithm (SVM): It is a supervised algorithm which is used to classify the values in the Swiggy and Zomato dataset. This is used to classify various parameters such as type of cuisine, type of food, restaurants based on their ratings.

Logistic Regression: Logistic regression is a supervised algorithm learning. It is used to calculate or predict the probability. This was used to predict the restaurants that user would prefer based on their preferences etc. This was also used to predict the delivery time and ratings.

K Means: K-Means Clustering is an Unsupervised Learning algorithm, which groups the unlabeled dataset into different clusters from the data available from the Swiggy and Zomato datasets. This was used to cluster the restaurants which have similar ratings, similar cuisine, similar location, or similar delivery time etc. which was helpful for the user to select the restaurant.
















