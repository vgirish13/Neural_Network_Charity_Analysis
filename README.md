# Neural_Network_Charity_Analysis

# Overview

## In this analysis Beks and I used a binary classifier to predict the success of applicants that were funded by Alphabet Soup. Beks' received data from over 34,000 organizations that were funded in the past. In order to find accurate results, we had to build a neural network. 

# Results

## Data Preprocessing

- IS_SUCCESSFUL was the variable considered as the target for our model

- Affiliation, Application Type, Ask Amount, Classification, Use Case, and Special Consideration were the variables considered to be features in our model. 

- EIN and NAME were variables removed from the input data

## Compile, Train, and Evaluate the Model

- We used 80 neurons, 30 nuerons, and 2 layeres. This was to reduce the risk of overfitting. 

- We were unable to achieve target model performance with 72% accuracy

- We increased our neuron count to 80, 60, and 40 respectively, while adding an additional layer

## Summary

- In order to reach the accuracy goal, we must find a new combination of neurons and layers. We were unable to achieve adequate optimization with our combination.
