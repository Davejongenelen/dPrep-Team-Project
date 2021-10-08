# Being a super-host: worth the effort?

__Research Question__
Is there a difference in pricing between super hosts and non-super hosts in Venice?

## Motivation
The purpose of this research is to figure out if there is a difference in pricing between hosts and super-hosts in Venice. Is choosing a Superhost over a host really worth the cost? And is there such a big difference between the two types of hosts?

First of all, we need to explain what "Superhosts" are. Those are experienced hosts who provide a shining example for other hosts and extraordinary experiences for their guests. Airbnb checks Superhosts’ activity four times a year, to ensure that the program highlights the people who are most dedicated to providing outstanding hospitality.

Why did we choose Venice? Venice is one of the three most visited cities in Italy with 12.948.519 of tourists in 2019 (ISTAT website - National Institute of Statistics, Nov, 2020) and with 7947 accommodations on Airbnb (Inside Airbnb, Aug 6, 2021). 

Price is one of the main factors guests consider when choosing where to stay. The price difference and competitiveness in the market leads hosts many times to change their pricing strategy. Usually Superhosts have more visibility and earning potential, but does this mean a higher price than a host without the Superhost label? In this research, we will investigate the correlation between pricing and type of host and as it may change the hosts' strategies.

Our results will help Airbnb hosts and Superhosts get more information on pricing strategy and adjust it based on the type of hosts they are and the experiences they offer.

## Data
The team project draws on datasets from [Inside Airbnb](http://insideairbnb.com/get-the-data.html) which is an independent open-source data tool developed by community activist Murray Cox who aims to shed light on how [Airbnb](http://airbnb.com) is being used and affecting neighborhoods in large cities. The tool provides a visual overview of the amount, availability, and spread of rooms across a city, as well as an approximation of the number of bookings and occupancy rate.
https://idsb.tmgrup.com.tr/ly/uploads/images/2021/06/23/123886.jpg
<img src="https://idsb.tmgrup.com.tr/ly/uploads/images/2021/06/23/123886.jpg" width="40%">

## Method and results

A quantitative analysis will be made on the dataset of Airbnb to answer the research question wether there is difference in pricing between super hosts and non-super hosts. The method is quantitative because we measure in numbers. The columns of the dataset of Venice will be analysed from an CSV file in R-studio and uploaded to Github.

A simple linear regression will be used as our method to analyse if there is a difference in pricing between super hosts and non-superhosts. This due to the fact that our independent variable will be a binary variable. Hereby the independent variable (IV) host_is_superhost will first be transformed into a binary variable, a so-called dummy variable. Furthermore, the dependent variable (DV) price has to be transformed into a numeric.  





First, introduce and motivate your chosen method, and explain how it contributes to solving the research question/business problem.

Second, summarize your results concisely. Make use of subheaders where appropriate.

## Repository overview

Provide an overview of the directory structure and files.

## Running instructions

Explain to potential users how to run/replicate your workflow. Touch upon, if necessary, the required input data, which (secret) credentials are required (and how to obtain them), which software tools are needed to run the workflow (including links to the installation instructions), and how to run the workflow. Make use of subheaders where appropriate.

## More resources

Point interested users to any related literature and/or documentation.

## About
This project is submitted in fulfillment of the requirements for the course [Data Preparation & Workflow Management](https://dprep.hannesdatta.com/)

Team 8: [Dave Jongenelen](https://github.com/Davejongenelen), [Alberto Maria Rizzuti](https://github.com/albirizzu), [Vere Schulpen](https://github.com/VereSchulpen), [Jaromir Weenink](https://github.com/JaromirW99)
