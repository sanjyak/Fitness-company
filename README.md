Business Problem

The market research team at Fitness company wants to identify the characteristics of the target audience for each type of treadmill offered by the company, to provide a better recommendation of the treadmills to the new customers. The team decides to investigate whether there are differences across the product with respect to customer characteristics.

Perform descriptive analytics to create a customer profile for each AeroFit treadmill product by developing appropriate tables and charts.
For each AeroFit treadmill product, construct two-way contingency tables and compute all conditional and marginal probabilities along with their insights/impact on the business.
Dataset

The company collected the data on individuals who purchased a treadmill from the AeroFit stores during the prior three months. The dataset has the following features:

Product Purchased:	KP281, KP481, or KP781
Age:	In years
Gender:	Male/Female
Education:	In years
MaritalStatus:	Single or partnered
Usage:	The average number of times the customer plans to use the treadmill each week.
Income:	Annual income (in $)
Fitness:	Self-rated fitness on a 1-to-5 scale, where 1 is the poor shape and 5 is the excellent shape.
Miles:	The average number of miles the customer expects to walk/run each week
Product Portfolio:

The KP281 is an entry-level treadmill that sells for $1,500.
The KP481 is for mid-level runners that sell for $1,750.
The KP781 treadmill is having advanced features that sell for $2,500.
What good looks like?

Exploration points:

1.Import the dataset and do usual data analysis steps like checking the structure & characteristics of the dataset
2.Detect Outliers (using boxplot, “describe” method by checking the difference between mean and median)
3.Check if features like marital status, age have any effect on the product purchased (using countplot, histplots, boxplots etc)
4.Representing the marginal probability like - what percent of customers have purchased KP281, KP481, or KP781 in a table (can use pandas.crosstab here)
5.Check correlation among different factors using heat maps or pair plots.
6.With all the above steps you can answer questions like: What is the probability of a male customer buying a KP781 treadmill?
7.Customer Profiling - Categorization of users.
8.Probability- marginal, conditional probability.
9.Some recommendations and actionable insights, based on the inferences.
10.Later on, we will see more ways to do “customer segmentation”, but this case study in itself is relevant in some real-world scenarios.
