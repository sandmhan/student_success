# student_success

## Contributors
Andrew Wirz

Gianmarco Huaytan

Mounish Kandumalla

Vinh Tang

Austin Sanders

## Overview

Prediction model for assessing student success using the K-Nearest-Neighbor algorithm.
The model will take in a plethora of answers provided by the prediction form. 
These answers will be broken up and passed into each prediction model that correspond with those retrieved features. 
Once each model is ran, the weighted grade predictions are summed up to provide the final academic performance prediction.
From this, we can determine if an individual is expected to have poor academic performance based on the external factors
that are not _explicitely_ associated such as household income, alcohol consumption, etc.. 

## How to run model

1. Overview project_form.md to see the necessary questions that are to be answered
2. Reference the model files for each answer 
3. Input the corresponding answers into each model's sample array
4. Run each model and sum up the weighted results to get final prediction
