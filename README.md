# Data-Science
A list of Case Studies Analysed as part of Data Science Learnings. 


## Analysing Sales Leads Case Study Using Logistic Regression
##### Problem Statement: 
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses. 

The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%. 

#### Business Goal:- 
Help X education select the most promising leads, i.e. the leads that are most likely to convert into paying customers. Build a model  to assign a lead score to each of the leads such that the customers with higher lead score have a higher conversion chance and the customers with lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%. 



## Analysis of Car Price Determining Factors through Linear Regression 
#### Problem Statement:
A Chinese automobile company Geely Auto aspires to enter the US market by setting up their manufacturing 
unit there and producing cars locally to give competition to their US and European counterparts. 

They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. 
Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be
very different from the Chinese market. The company wants to know:

Which variables are significant in predicting the price of a car
How well those variables describe the price of a car

#### Business Goal:- 
Model the price of cars with the available independent variables. It will be used by the management to 
understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars,
the business strategy etc. to meet certain price levels. Further, the model will be a good way for management to understand the pricing dynamics of a new market. 

## Analysis of Factors Affecting Loan Default using EDA
#### Problem Statement
A consumer finance company specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The dataset given contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

In this case study,  use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

#### Business Objective
The lendinc company company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. 
Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

## Analysis of Product Sales  Determining Factors  Through Linear Regression
#### Problem Statement 
A Super store chain has several superstores in various parts of US of different sizes and stocks different commodities. The cost of various items is same across the stores and we are provided with daily item sales of these stores for 3 months

##### Busness Objective
Derive the factors affecting the various prices of items across the superstores.



## Analysis of Supply and Demand Gap of cars at Uber using EDA
#### Problem Statement :-
Uber is an international cab service provider company that provides rides within city and outside city.
Uber customers are facing a problem of cancellation by the driver or non-availability of cars?

These very issues also impact the business of Uber. If drivers cancel the request of riders or if cars are unavailable, Uber loses out on its revenue.

#### Business Objective
The aim of analysis is to identify the root cause of the problem (i.e. cancellation and non-availability of cars) and recommend ways to improve the situation. As a result of your analysis, you should be able to present to the client the root cause(s) and possible hypotheses of the problem(s) and recommend ways to improve them.  


## Data Analysis of various Startups for Investment for a Private Fund
#### Problem Statement
Spark Funds wants to make investments in a few companies. The CEO of Spark Funds wants to understand the global trends in investments so that she can take the investment decisions effectively.

Spark Funds has two minor constraints for investments:
1) It wants to invest between 5 to 15 million USD per round of investment
2) It wants to invest only in English-speaking countries because of the ease of communication with the companies it would invest in.

For our analysis, we will consider a country to be English speaking only if English is one of the official languages in that country

#### Business Objective
The objective is to identify the best sectors, countries, and a suitable investment type for making investments. The overall strategy is to invest where others are investing, implying that the 'best' sectors and countries are the ones 'where most investors are investing'.

Goals of data analysis:
1) Investment type analysis: Comparing the typical investment amounts in the venture, seed, angel, private equity etc. so that Spark Funds can choose the type that is best suited for their strategy.

2) Country analysis: Identifying the countries which have been the most heavily invested in the past. These will be Spark Funds’ favourites as well.

3) Sector analysis: Understanding the distribution of investments across the eight main sectors. (Note that we are interested in the eight 'main sectors' provided in the mapping file. The two files — companies and rounds2 — have numerous sub-sector names; hence, you will need to map each sub-sector to its main sector.)

## Determining Factors Affecting Housing Prices using Lasso and Ridge Regression
##### Problem Statement: 
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in a CSV File.

The company is looking at prospective properties to buy to enter the market
The company wants to know:
1) Which variables are significant in predicting the price of a house, and
2) How well those variables describe the price of a house.
3) Also, determine the optimal value of lambda for ridge and lasso regression.

#### Business Objective:- 
We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for the management to understand the pricing dynamics of a new market.

## Handwritten Digit Recognition Using SVM
#### Problem Statement: 
A classic problem in the field of pattern recognition is that of handwritten digit recognition. Suppose that you have images of handwritten digits ranging from 0-9 written by various people in boxes of a specific size - similar to the application forms in banks and universities.
The goal is to develop a model that can correctly identify the digit (between 0-9) written in an image. 

#### Business Goal:- 
We are required to develop a model using Support Vector Machine which should correctly classify the handwritten digits from 0-9 based on the pixel values given as features. Thus, this is a 10-class classification problem.


## IMDB Movie Database Analysis using Python Pandas amd Numpy
#### Problem Statement:- 
In this assignment, we try to find some interesting insights into a few movies released between 1916 and 2016,from IMDB Database. Explore the data, gain insights into the movies, actors, directors, and collection.


## Recommendations of Countries for Hep International using PCA and Clustering
#### Problem Statement: 
HELP International is an international humanitarian NGO that is committed to fighting poverty and providing the people of backward countries with basic amenities and relief during the time of disasters and natural calamities. It runs a lot of operational projects from time to time along with advocacy drives to raise awareness as well as for funding purposes.

After the recent funding programmes, they have been able to raise around $ 10 million. Now the CEO of the NGO needs to decide how to use this money strategically and effectively. The significant issues that come while making this decision are mostly related to choosing the countries that are in the direst need of aid. 

#### Business Goal:- 
Categorise the given countries using some socio-economic and health factors that determine the overall development of the country. Then  suggest the countries which the CEO needs to focus on the most. The datasets containing those socio-economic factors and the corresponding data dictionary are provided. 
