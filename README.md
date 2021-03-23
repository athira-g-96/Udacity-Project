# Udacity-Project

This notebook contains analysis of fertility rates of different countries from 1960s to 2013 as part of Udacity Data Science Nanaodegree.

## Contents

1. [Installation](#Installation)
2. [Project Motivation](#Project-Motivation)
3. [File Description](#File-Descriptions)
4. [Results](#Results)
5. [Acknowledgments](#Acknowledgements)

## Installation
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.

Libraries used are:

* Pandas 
* Numpy
* Scikitlearn 
* Scipy
* Matplotlib

## Project Motivation

For this project, I was interested to know the trends in fertility rates of different countries over the years.
I have used Kaggle dataset provided [here](https://www.kaggle.com/rishidamarla/fertility-rates-of-all-countries-1960present) to do the analysis and get some insights on the following questions.

1. Does African countries have greater fertility rates?
2. Which are the countries that have highest and lowest fertility rates?
3. What are the trends of fertility rates in developed and developing countries? Is there a difference in trends?
4. Can you predict the fertility rates given 53 years fertility rates of the countries?
5. How fertility rates have been changing over the years ?

## File Description

There are 2 files in this repository.

1. `.csv` file : Dataset used for the analysis is provided 
    * Dataset contains the fertiltiy rates of 215 countries from 1963 to 2013
    * 215 rows and 58 columns
    
3. `.ipynb` file : Jupyter notebook with all the analysis code
    * This notebook contains:
        * Data cleansing to get required data
        * Data imputation using KNNImputer
        * 5 questions that was answered using various techniques like EDA and Machine Learning algorithm.
        * Visualisations to support the insights

## Results
 Results after the analysis are :
  1. African countries have greater fertiltiy rates than other regions of the world
  2. Niger is the country with highest fertility rate and Liechtenstien is the country with lowest fertility rates.
  3. Developed countries showed a similar pattern in the variation of fertility rates. Some of the developed countries have maintained its fertilty rate over the years. These results can be seen in detail [here](https://athiragkutty.medium.com/growing-population-and-shrinking-families-a3a04cc56b6a).
  4. A model to predict the fertility rates can be seen in the notebook provided in the repository.

## Acknowledgements

* Credits to Rishi Damarla who published the dataset used for the analysis.[data](https://www.kaggle.com/rishidamarla/fertility-rates-of-all-countries-1960present)
* Credits to  Anthony Cilluffo and Neil G. Ruiz for the the [article](https://www.pewresearch.org/fact-tank/2019/06/17/worlds-population-is-projected-to-nearly-stop-growing-by-the-end-of-the-century/) which was referred for the facts given in the [blogpost](https://athiragkutty.medium.com/growing-population-and-shrinking-families-a3a04cc56b6a)
