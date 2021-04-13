# Starbucks Capstone Project - Udacity Data Scientist Nanodegree: A deep dive analysis into the offers/rewards given & consumption of one of Starbucks' product

Starbucks Corporation is an American multinational chain of coffeehouses and roastery reserves headquartered in Seattle, Washington. As the world's largest coffeehouse chain, Starbucks is seen to be the main representation of the United States' second wave of coffee culture. [Wikipedia](https://en.wikipedia.org/wiki/Starbucks)

As any other business, Starbucks frequently gives different offers and rewards to it's customers to promote sales.
This project dives into analyzing simulated data of one of Starbucks' product by looking at offers' data, customer information data & transaction data to understand how different demographics influence customers completing different types of offers. We also go further to understand which factors hugely influence the amount spent on the product.

## Table of Contents
1. [Project Motivation](#motivation)
2. [Installations](#installations)
3. [File Overview](#overview)
4. [Key Results](#results)
5. [Acknowledgements](#acknowledgements)


## <a id="motivation"/> Project Motivation
The key motivation of this project is to use skills learned in the Nanodegree to analyze and get insights into how different demographic groups respond to different type of offers. The project also incoporates the CRISP-DM process in getting the insights.

The business questions that the project seeks to answer are:

- Demographics Questions
    - how do demographics influence the type of offer given
    - how do demographics influence the channels that a customer uses to complete an offer
    - how do demogrpahics influence the customers completing offers of various durations
    - how do demographics influence the customers in completing offers with various rewards
    - how do demographics of customers interact with difficulty (min required spend to complete an offer) of offers

- Key Driver Analysis
Which factors influence highest to the amount spent by a customer ?


## <a id="installations"/> Installations
This project mainly utilized Jupyter Notebook using Python; In addition the  following libraries were used :
- datetime
- json
- math
- mathplotlib
- numpy
- pandas
- relativeImp
- scikit-learn

##  <a id="overview"/> File Overview
- Starbucks_Capstone_notebook.ipynb : Jupyter notebook containing all the analysis
- data: folder containing the raw json data files used in the  project
    - portfolio.json: json file containing offer ids and meta data about each offer (duration, type, etc.)
    - profile.json: json file containing  demographic data for each customer
    - transcript.json: json file containing records for transactions, offers received, offers viewed, and offers completed
- plots: folder containing all plots from the analysis
- utility_images : folder containing some images from Udacity for instructions

## <a id="results"/> Key Results
The insights from this projects are discussed in a data story published on [Medium](https://medium.com/@mumongungu/a-taste-of-offers-at-starbucks-analyzing-which-offers-work-for-different-customer-demographics-378e4769b41c)

## <a id="acknowledgements"/> Licenses and acknowledgements
This project was worked as a Capstone project of the Udacity Data Scientist Nanodegree. The datasets are from Starbucks who have collaborated with Udacity to provide data to be used to complete this project. Special thanks for this collaboration to provide the data.
