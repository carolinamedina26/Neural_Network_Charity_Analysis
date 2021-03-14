# Neural_Network_Charity_Analysis
## Overview 
With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results 
### Data processing 
First, we identify the dependent variable which is " IS_SUCCESFULL", this row of data displays if the applicant was succesfull or not after funding. 
<img src="https://github.com/carolinamedina26/Neural_Network_Charity_Analysis/blob/main/Resources/is_successful.png">

The feature of our dataset are the reamining variables, althouhg, we decided to **drop "ET & NAMES"** since they do not offer information that will allows to inprove our model. 
<img src="https://github.com/carolinamedina26/Neural_Network_Charity_Analysis/blob/main/Resources/drop_name.png">

### Trainning & Evaluation of Model
<img src="https://github.com/carolinamedina26/Neural_Network_Charity_Analysis/blob/main/Resources/hidden_layers.png">

For this model,we use two layers for a deep learning model, with 80 and 30 nodes in each one.

### Results
Our model display an 73% perfomance. Which is sufficit for the prupose of this analysis. For that reason, we decided to optimize our model by grouping names per application times. 

<img src="https://github.com/carolinamedina26/Neural_Network_Charity_Analysis/blob/main/Resources/name_variable.png">

After this founding, we decided to group applicants with <4 application together, that way reduced the outliers. 

Finally our optomized model **increase its preforming with a result of 79% accuracy.**

<ims src="https://github.com/carolinamedina26/Neural_Network_Charity_Analysis/blob/main/Resources/optimaze_model_results.png">
