# Neural_Network_Charity_Analysis
## Overview 
With the used of machine learning, we will help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results 
### Data processing 
First, we identify the dependent variable which is " IS_SUCCESFULL", this variable reflects if the applicant was successful or not after funding. 
<img src="https://github.com/carolinamedina26/Neural_Network_Charity_Analysis/blob/main/Resources/is_successful.png">

The feature of our dataset are the remaining variables, although, we decided to **drop "ET & NAMES"** since they do not offer relevant information.
<img src="https://github.com/carolinamedina26/Neural_Network_Charity_Analysis/blob/main/Resources/drop_name.png">

### Training & Evaluation of Model
<img src="https://github.com/carolinamedina26/Neural_Network_Charity_Analysis/blob/main/Resources/hidden_layers.png">

For this model, we use two layers for a deep learning model, with 80 and 30 nodes in each one.

### Results
Our model display an 73% accuracy, which is insufficient for the purpose of this analysis. For that reason, we decided to optimize our model. We decided to provide more data and the approached we took was to group names per application times. After having a closer look to the data, we decided to group applicants with <4 application together with the name “OTHER” that way reduced the outliers.

<img src="https://github.com/carolinamedina26/Neural_Network_Charity_Analysis/blob/main/Resources/name_variable.png">

After running our model with more data, **its performance increased with a result of 79% accuracy.**

<ims src="https://github.com/carolinamedina26/Neural_Network_Charity_Analysis/blob/main/Resources/optimaze_model_results.png">
  
