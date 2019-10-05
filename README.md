# MercadoLivreDC2019
My solution for Mercado Livre data challenge 2019


## Problem formulation:
1 - Build a product classifier(category) according to the product title;

## A exemple of title and category:

Title = Banco Honda Crf 230 Pro Tork Frete Grátis	

Category = MOTORCYCLE_SEATS

## Solution approach:

0 - Generate a 4kk row dataFrame sample

1 - Preprocess the title to clear unwanted characters, remove stopwords and set maximum word count

2 - Transform the title in a bag of word

3 - Application of a Linear Support Vector machine through one versus rest strategy in 90% of sample dataframe 
and testing the accuracy in the least 10%;


This approach achieved an accuracy of 0.86


