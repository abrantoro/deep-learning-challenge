# Analysis 
1) What variable(s) are the target(s) for your model?
The target variable had to be  'IS_SUCCESSFUL' column in the dataframe. It helped identify whether certain funding applications were approved or not.

2) What variable(s) are the features for your model?
The features had to be every other column that was in the dataframe. Especially when the 'IS_SUCCESSFUL' is dropped from the dateframe.

3) What variable(s) should be removed from the input data because they are neither targets nor features?
The 'EIN' and 'Name' columns were dropped because they were not targets or features for the dataset. Organization names in 'Name' were not prodictive in the dataset and the 'EIN' it was a distinct identifier that would not have impacted the predictions.


#Compiling, Training, and Evaluating the Model
1) How many neurons, layers, and activation functions did you select for your neural network model, and why?
The neural networks were gathered in steps/procceses. It has the input layer which defines the number of input features in the model. Then we have First Hidden layer which is 80 neurons, ReLU activation. Then Second Hidden Layer 30 neurons, ReLU activation. Thirdly, Output Layer which is 1 neuron, Sigmoid activation (for binary output).
The number of neurons was selected based on experimentation and general output for more efficient and training time performance.

2)Were you able to achieve the target model performance?
No I was unable to reach a model accuracy of 75%. The model got in a stagnate state after tuning and could not reach the desired target.

3) What steps did you take in your attempts to increase model performance?
I tried to do another test with random forrest and adding layers but I kept getting tabular errors which I could not figure out. So after a great deal of trial and error I decided to cut it short on the performance.
