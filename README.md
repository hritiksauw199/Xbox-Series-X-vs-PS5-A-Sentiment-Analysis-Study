# PS5 vs Xbox Series X : Sentiment Analysis

# Problem Statement

Confused about which console to buy? Currently there are two popular 
consoles available in the market, namely PS5 and Xbox. Choosing between
a console is a hard decision as the player plans to use it for atleast 5 years 
and hope to experience the best quality games and performance on it.

In this project we aim to analysis users reviews and how their experience was
with each of the consoles. This will help us understand which console
would be a better fit for our use. Now there are lots of youtube video and 
blog detailing their reviews on both consoles but I feel the reviews
are most honest when it comes from buyers. But going through all of the 
reviews manually could be a tedious job instead we will use our analytical 
skills to understand the reviews and help us decide which to buy.

We will use reviews for each product on **Amazon.com**, extract the data
and perform sentiment analysis to gain more insights about users
experience for each console and draw conclusions.


Link to Xbox Series X: https://www.amazon.com/Xbox-X/dp/B08H75RTZ8/ref=sr_1_3?crid=1D7TXXZUI5CWO&keywords=xbox%2Bseries%2Bx&qid=1673517878&sprefix=%2Caps%2C286&sr=8-3&th=1
![xboxb.jpg](images%2Fxboxb.jpg)

Link to PS5: https://www.amazon.com/PlayStation-5-Console/dp/B08FC5L3RG/ref=cm_cr_arp_d_product_top?ie=UTF8
![ps5.png](images%2Fps5.png)

# Steps Carried out

1. Importing Libraries
2. Scraping user reviews for both consoles from Amazon.com
3. Sentiment Analysis for PS5
   - Loading the Data
   - Dealing with Missing Values
   - Cleaning review text
   - EDA
4. Sentiment Analysis for Xbox (we automate the above same procedure using a helper function)
5. Comparing Sentiments of Xbox and PS5
6. Training model for each console
7. Conclusion