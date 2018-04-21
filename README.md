# handwritten_digits

Recognize handwritten digits from 0 to 9. 

## ex3.m
- uses logistic regression where a regressio model is trained for each label (0-9). 
- Performs one vs. all classification.Each sample is run for all 10 models, and the label whose corresponding regression model gives the highest h(x) value is selected. 

## ex3_nn.m 
- uses a three-layer neural network with one hidden layer
