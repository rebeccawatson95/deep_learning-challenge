# deep_learning-challenge

# Rebecca Watson

## Overview: Explain the purpose of this analysis
Given a dataset containing more than 34,000 organizations that have received funding from Alphabet Soup over the years, I used the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.


## Results: Using bulleted lists and images to support your answers, address the following questions
### Data Preprocessing
    - target(s) for my model: "is_successful"
    - feature(s) of my model: "applcation_type", "affiliation", "classification", "use_case", "organization", "status", "income_amt", "special_considerations", and "ask_amt" 
    - variable(s) that should be removed: "EIN" and "name"

### Compiling, Training, and Evaluaing the Model
    -neurons: 2
     layers: 2
     activation functions: 2
    -target model performance: 75%
     my model performance: 76.73%
    -steps taken to incease model performance:
        -dropped more rows of data into the "other" bucket
        -adjusted the number of epochs to the training regimen
        -added more hidden layers

## Summary: 
Idealy a model would be closer to 100% in model performance. That being said, for this project, the goal was 75% and I was able to exceed that. 


