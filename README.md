# Neural_Network_Charity_Analysis

## Overview
Using a deep learning neural net model, a dataset was analysed to predict whether or not an applicant that was funded by "Alphabet Soup" would be successful. A dataset of 34,000 organizations that have received funding from Alphabet Soup over the years. 

## Results 
- The target for the model was the IS_SUCCESSFUL column
-The features of the model are
  - APPLICATION_TYPE	
  - AFFILIATION	
  - CLASSIFICATION	
  - USE_CASE	
  - ORGANIZATION	
  - STATUS	
  - INCOME_AMT	
  - SPECIAL_CONSIDERATIONS	
  - ASK_AMT
- The EIN and NAME were neither the target or wanted features, and were removed






## Optimization
After many attempts, I was unable to hit the 75% accuracy for the model. Adding layers and neurons provided similar or even worse results than the original model which is obviously not ideal. I also tried binning the asking amounts, which did give a slight boost to the accuracy. In the end, the maximum accuracy I was able to achieve was ----
