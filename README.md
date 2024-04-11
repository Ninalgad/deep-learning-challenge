# deep-learning-challenge

# Report
## Overview
Developing a DNN binary classifier to predict success if provided funding by Alphabet Soup.

## Results
### Data Preprocessing
 - Target: `IS_SUCCESSFUL` — Was the money used effectively
 - Features: 
   - `APPLICATION_TYPE` — Alphabet Soup application type
   - `CLASSIFICATION` — Government organization classification
   - `USE_CASE` — Use case for funding
   - `ORGANIZATION` — Organization type
   - `STATUS` — Active status
   - `INCOME_AMT` — Income classification
   - `ASK_AMT` — Funding amount requested
 - Model Hyperparameters: 
   - 3-layers
   - ReLU activation based on performance
   - sigmoid output layer
 - Evaluation:  target model performance was NOT achieved.
 - Feature Selection: 
   - Dropped the `SPECIAL_CONSIDERATIONS` features
 