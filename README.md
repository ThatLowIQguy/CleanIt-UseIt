# Bike-recommended-system
This project deals by recommended bikes to the users based on their interests.

Developed a knowledge-based product recommender system using product as motorbikes. This was implemented using Prolog with Forward-chain interpreter and Bayesian interpreter. This system is used by the store manager of motorbikes based on products that are in a customer's cart. This way, the motorbike store manager can give suggestions/recommend to the customer about other products. 

The implementation is done in two parts. 
Part 1 is the system asking the store manager of motorbikes company to input what products are in the cart. Using it, the system creates a probabilistic "customer model" with the help of Bayesian network. The main focus of the customer model is to know what customer likes/dislikes and/or goals.

After knowing all the details, using the above information we create if-then rules based on the probability and interest of the customer. 

In Part 2, we recommended the products using the forward chaining on the above data when the probability is greater than 50 percent.

