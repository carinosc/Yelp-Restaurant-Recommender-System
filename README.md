# Yelp Restaurant Recommender System

In an effort to enable the discovery and support of up and coming restaurants, the Yelp Restaurant Recommender System aims to populate recommendations based on a dataset of predicted reviewer ratings for restaurants they are yet to visit. 

In other words, through the use of machine learning and matrix factorization algorithms, we can use information of known (i.e. occurred) restaurant ratings to understand the factors and their weight in influencing an assessed rating to predict how they may rate restaurants they are yet to visit. 

Allowing for user input on a restaurant food category (i.e. Thai, Comfort, etc.) and the tolerance of how far from a restaurant's average rating the individual is comfortable in trying; we can use the dataset of predicted ratings as a base for similar rating preferences when opting to try new restaurants.

This project serves as an example of my efforts in solidifying my data analysis fundamentals, in addition to my understanding of Machine Learning and associated algorithmic models. Please feel free to watch this brief three minute overview video of my project: https://youtu.be/fcKY2aeeia4

---------

## Installation

Using the conda package manager, the following were the main packages used for my project in addition to python, install at your own risk:

- `conda install pandas`: For JSON importing and DataFrame analysis
- conda install matplotlib`: For visualizations
- `conda install scikit-learn`: For access into the Machine Learning toolbox
- `conda install scikit-surprise`: For the Matrix Factorization algorithm, FunkSVD, and additional functions

Alternatively, I have also provided the `capstone_environment.yml` file to more efficiently clone the environment and its packages from.

---------

## Data Description

The data used for this project derive from the [Yelp Dataset](https://www.yelp.com/dataset) resource webpage, of which the `yelp_academic_dataset_business.json` and `yelp_academic_dataset_review.json` files were used. Information found in the sets include restaurant features and information, in addition to the individual text reviews and ratings assessed by users for respective restaurants.

I touch on the command line processing tool, `jq` (documentation [here](https://stedolan.github.io/jq/manual/)), used to help parse the large JSON files, but the 'data' folder contains a parsed version of the businesses file named `finrestphx.json` and the last sub-file after splitting the toal reviews file; given the size limits of Git.

---------

## File Directory

- `capstone_environment.yml`: Contains all of the packages installed in my environment in which the project was ran (please note, a number of them are base packages).
- `Cesar_Carino_Capstone_Report.pdf`: A summary report of my work and thought process on the project.
- `Cesar_Carino_Yelp_Restaurant_Recommender_System.ipynb`: A cleaned and consolidated notebook of all my work for the project.
- `Data`: Folder containing the samples of parsed Yelp datasets used for the project. As mentioned, the complete original Yelp data files can be obtained [here](https://www.yelp.com/dataset).

Please be advised, to use the Yelp Dataset information, you must adhere to Yelp's "DataSet_User_Agreement.pdf" as I did when first downloading the information.

------

### Thank you

Thank you for your interest and time. Please feel free to reach out via Linked for hiring inquiries or questions on the project: https://www.linkedin.com/in/cesar-steven-carino/

# End
------
