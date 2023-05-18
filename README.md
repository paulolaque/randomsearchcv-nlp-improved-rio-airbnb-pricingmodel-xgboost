# randomsearchcv-nlp-improved-rio-airbnb-pricingmodel-xgboost

Perform feature importance analysis for Airbnb pricing in Rio de Janeiro using a combination of various data preprocessing techniques, including get_dummies for categorical variables and NLP (Natural Language Processing). The model utilized for this task is XGBoost, which was fine-tuned using RandomSearchCV. To enhance its performance, the model was also configured to run on a GPU.

#### Author: Paulo Gabriel Dantas Laque [Linkedin](https://www.linkedin.com/in/paulogabriellaque/) [Github](https://github.com/paulolaque)

---


## Instructions  <a name="installation"></a>
For optimal performance, please run this code on a device equipped with a GPU. Additionally, ensure that the following libraries are installed.

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

### Installation
- Python (Tested on 3.8.10) 
- NumPy (Tested on 1.21.6)
- Pandas (Tested on 1.3.5)
- Matplotlib (Tested on 3.2.2)
- Scikit-learn (Tested on 1.0.2)
- Seaborn (Tested on 0.11.2)
- SciPy (Tested on 1.7.3)
- XGBoost (Tested on 0.90)
- Bar Chart Race (Tested on 0.1.0)
- NLTK (Tested on 3.8.1)

## Project Motivation<a name="motivation"></a>

In this project I wanted investigate as a host or investor how to make the most revenue for a night in a Airbnb stay.
For this I used data from Airbnb (listings.csv) compiled in 20 June, 2022 for Rio de Janeiro available [here](http://data.insideairbnb.com/brazil/rj/rio-de-janeiro/2022-06-20/visualisations/listings.csv) 


## File Descriptions <a name="files"></a>

There are 1 notebooks available here to showcase work related to the above questions:
 [Airbnb_Rio_de_Janeiro_Pricing_Model_using_XGBoost_Random_Forest.ipynb](https://github.com/paulolaque/rio-airbnb-pricingmodel-xgboost-rforest/blob/main/Airbnb_Rio_de_Janeiro_Pricing_Model_using_XGBoost_Random_Forest.ipynb). 


## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://paulolaque.medium.com/this-is-how-to-make-money-with-airbnb-in-rio-de-janeiro-according-to-machine-learning-4bd40271819d).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The data is credited to Airbnb available [here](http://data.insideairbnb.com/brazil/rj/rio-de-janeiro/2022-06-20/visualisations/listings.csv).  You can find the Licensing for the data and other descriptive information available [here](http://insideairbnb.com/get-the-data).

This analysis builds upon and improves the data preprocessing and modeling techniques presented in my previous work. It incorporates the use of a bag of words for amenities, lemmatization, stop word removal, and fine-tuning with RandomSearchCV. The model also got GPU acceleration and a better structure to check runtime, test and change parameters.

For more details, refer to the [Airbnb_Rio_de_Janeiro_Pricing_Model_using_XGBoost_Random_Forest.ipynb](https://github.com/paulolaque/rio-airbnb-pricingmodel-xgboost-rforest/blob/main/Airbnb_Rio_de_Janeiro_Pricing_Model_using_XGBoost_Random_Forest.ipynb) notebook.


#### Author: Paulo Gabriel Dantas Laque [Linkedin](https://www.linkedin.com/in/paulogabriellaque/) [Github](https://github.com/paulolaque)
