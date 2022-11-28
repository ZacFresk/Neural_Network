# Neural Network Analysis

## Objective

On orgnization Alphabet Soup wants to make investments in charitable organizations. With using machine learning techniques and specific neural networks we can review any dataset provided to see if those who apply for charitiable aid were succesful in their attempts. After cleaning the data provided we can use it in a model that was trained using TensorFlow and Neural Network Playground. 

## Results

### Preprocessing Data:

  **1) What variables does your model target?**
  
  The target of the model was the "Is_Successful" column. This column would explain which of the organizations were recieving funding
  
  **2) What variables does your model featuring?**
  
  All columns except "EIN" and "Name" would be considered features as they were removed
  
  **3) What variables could be removed from your data?**
  
  "EIN" and "Name" do not add any potenital benefit for the analysis. They are catagorical data that gave name and number to a certain charity orgnaization.
  
  ###Compiling, Training, and Evaluating the Model
  
  **How many neurons, layers, and activation functions did you select for your neural network model, and why?**
  
  There are two hidden layers provided with 80 nodes and 30 nodes provided respectively. The model parameters were close to 6,000. After training through 100 epochs, the accuracy was 72.5% rounded.
  
  1

2

When using Neural Network Playground we ran several iterations of hidden layers and neurons. We ended up with several different types of training for the model. Finally we ran through five hidden layers and switched between 50 and 100 epochs for each. 

  **Three Hidden Layers**

 - 1) 50 Epochs

  3

 - 2) 100 Epochs

4

  **Four Hidden Layers**

 - 1) 50 Epochs

5

 - 2) 100 Epochs

6

  **Five Hidden Layers**

  1) 50 Epochs

7
- 2) 100 Epochs

8


**Were you able to achieve the target model performance of 75%?**

No. The best performance we could get for accuracy was 72.6% with using 4 layers at 50 epochs. 

**What steps did you take to try and increase model performance?**

The variables were within the hidden layers and epoch levels. We wanted to see if we were under or over training the model. 

## Summary
Increasing the amount of iterations did not change all that much. Before working on optimizating the code, the accuracy was 72.5%. After adding hidden layers and neurons per layer the greatest we could get was 72.6%.

For furthering the analysis we can either bin certain columns to create smaller data clusters. We could also use scrapping neural networks with this dataset and using a RandomForest or AdaBoost analysis to see if that type of machine learning process would better fit the data provided. 
  
