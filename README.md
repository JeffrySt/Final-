# Final Project Practicum Tripleten
These Final Project consist of 3 projects: A/B Testing, SQL and analyzing retail sales of Home World 

## A/B Testing Project
1. Task
You have received an analytics assignment from an international online store. Your predecessor failed to complete this task: he had run A/B testing before quitting his job (he said, to raise chickens in the village). He left behind only the technical specifications and results of his experiments.
2. Technical Description
  2.1. Experiment name: recommender_system_test
  2.2. Groups: А (control), B (new payment funnel)
  2.3. Experiment start date: 07-12-2020
  2.4. Date when they stopped accepting new users: 21-12-2020
  2.5. The end date of the experiment: 01-01-2021
  2.6. Audience: 15% of new users from the EU region
  2.7. Purpose of the experiment: testing changes related to the introduction of the improved recommendation system
  2.8. Expected result: within 14 days of enrollment, users show an increase in conversions to product page impressions (product_page events), adding items to the shopping cart (product_cart), and purchases. At each stage of the product_page → product_cart → purchase funnel, there will be at least a 10% increase.
  2.9. Expected number of experiment participants: 6.000
Download the test data, see if it is as expected, and analyze the results.
3. Instructions for Completing the Task
  - Describe the purpose of your study.
  - Explore the data:
      > Should the data types be converted?
      > Are there missing values or duplicate values? If so, how would you characterize them?
  - Perform exploratory data analysis:
      > Study conversions at different stages of the funnel.
      > Is the number of events per user evenly distributed across the sample?
      > Are there users who are in both samples?
      > How is the number of events distributed by day?
      > Does your data have any special features that should be considered before starting A/B testing?
  - Evaluate the A/B testing results:
      > What can you say about the A/B testing results?
      > Use the z-test to test for statistical differences between the proportions.
  - Explain your conclusions regarding the EDA stage and the A/B testing results.

## SQL Project
The coronavirus, whose presence has shocked the entire world, has changed everyone's daily routine. Now, city dwellers no longer spend their leisure time outside their homes such as going to cafes and malls. They are more often at home, spending their time reading books. This has prompted startup companies to develop new apps for book lovers.
You have been given a database from one of the companies competing in this industry. The database contains data on books, publishers, authors, and customer ratings and reviews of the books. This information will be used to create a price quote for a new product.
1. Task
  1.1. Count the number of books released after January 1, 2000.
  1.2. Count the number of user reviews and average rating for each book.
  1.3. Identify the publishers that have published the largest number of books, with more than 50 pages (this will help you exclude brochures and similar publications from your analysis).
  1.4. Identify the author with the highest average book rating: find books with a rating of at least 50.
  1.5. Calculate the average number of review texts among users who rated more than 50 books.
2. Instructions for Completing the Task
  2.1. Explain the purpose of your study.
  2.2. Study the table (show the first rows).
  2.3. Make SQL queries for each of your tasks.
  2.4. Display the results of each query in the notebook.
  2.5. Explain your conclusions for each task.

## HOME WORLD - RETAIL
The dataset contains data on purchases made at the building-material retailer Home World. All of its customers have membership cards. Moreover, they can become members of the store's loyalty program for $20 per month. The program includes discounts, information on special offers, and gifts.
### Project background

1. Who's the customer?
   Project 2: Project manager responsible for performance
    
2. Who needs the information? Who is the intended user of the final result?
   The customers who initiated the projects
    
3. What do they want to do?
   Project 2: Formulate a performance metric for sales outlets and analyze their performance
    
4. Are we interested in a particular time period? Or are we investigating the entire period covered by the source data?
   The entire period 
    
5. Is the presentation intended for the customer? If not, who will study it?
   The presentation is for the customer.
    
6. What made this analysis necessary? Why this kind of analysis in particular?
   In order to understand what stores within the large chain need support, we need to develop a performance metric for sales outlets. This data will be used to set priorities for stores and formulate KPI.
    
7. Has research of this kind been carried out before?
   No, this is new. Be as explicit as possible when describing how your solution works.

**Task:** 
Assess the performance of the chain's sales outlets.

**Assess sales outlets' performance**
- Analyze the largest store in the chain separately: the number of unique customers, average purchase size, average number of items in the cart, the share of loyalty program members, and customer retention.
- Analyze the same parameters for other stores in the chain.
- Formulate a metric for sales outlet performance and calculate it for each store.

**Test statistical hypotheses**
- Test the hypothesis that the average purchase size for loyalty program members is higher than it is for non-members.
- Formulate a statistical hypothesis regarding the data from the dataset and test it.
