# Neural_Network_Charity_Analysis

## Overview
The purpose of this analysis is to produce a binary classifier using machine learning to help predict whether applicants will be successful if  funded by Alphabet Soup.
Data from more than 34,000 organizations that have received funding was used in order to build the model. 

## Results
 - Data Preprocessing
   The variables that were considered the target, or desired value, for our model is were the variables associated with the Successful applications. These were found by taking the column of successful applications and comparing their variables. 
   
   The variables that were considered the features for the model were the 61 input features associated with the successfull applications.
   
   For both the target ad features, python was used to grab the data to make things simpler. There were some variables that did not fit the criteria and needed to be moved. These were the EIN and NAME. 
- Compiling, Training, and Evaluating the Model
  In the end, any model with more than 10 neurons and 2 layers seemed to produce results around 65% accuracy.
  
  In order to improve the model, first more neurons were added. Then an addictional layer was added. Optimizing the neuron and layers was attempted (finding how many would give the best values). The data was analyzed again to see if there were any outliers, but not many were determined. The Ask Amount data showed that most of the asks were around 5000, so everything else was dropped to see if the accuracy could be increased. 
  After these attempts, a dendrogram was used to see if it could produce higher accuracy. This also did not work. 
  
  
 ## Summary
  
  The results of the model was that it could predict around 65% of the successful applications. This model is not as accurate as it needs to be in order to be successful.
  A different model would be able to solve the classification problem, because of the way the data is split. The data shows that the way the Classifications are split up, have no bearings on the successfullness.

According to this data, the business has been accepting all applications and it barely more than a coin flip to predict if it is successful. It is logical to assume that the ask amount has more to do with the successfullness of the applicant. A new model comparing the Ask Amount to the successfullness could be created and assessed to hopefully produce a model that has a higher accuracy than 65%. 
   
I would suggest that more data gets compiled, or new data sets get created, as well as a new prediction model created in order to assess succesfful funding applicants. 
