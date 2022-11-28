# Neural Network Analysis

## Objective

On orgnization Alphabet Soup wants to make investments in charitable organizations. With using machine learning techniques and specific neural networks we can review any dataset provided to see if those who apply for charitiable aid were succesful in their attempts. After cleaning the data provided we can use it in a model that was trained using TensorFlow and Neural Network Playground. 

## Results

### Preprocessing Data:

- What variables does your model target?
  
   - The target of the model was the "Is_Successful" column. This column would explain which of the organizations were recieving funding
  
- What variables does your model featuring?
  
   - All columns except "EIN" and "Name" would be considered features as they were removed
  
- What variables could be removed from your data?
  
   - "EIN" and "Name" do not add any potenital benefit for the analysis. They are catagorical data that gave name and number to a certain charity orgnaization.
  
### Compiling, Training, and Evaluating the Model
  
### How many neurons, layers, and activation functions did you select for your neural network model, and why? ###
  
  There are two hidden layers provided with 80 nodes and 30 nodes provided respectively. The model parameters were close to 6,000. After training through 100 epochs, the accuracy was 72.5% rounded.
  
  ![1](https://user-images.githubusercontent.com/107363203/204196831-6a5eb785-e139-4c6c-b331-c6e133618745.png)


![2](https://user-images.githubusercontent.com/107363203/204196857-c5763269-780a-48be-a9b1-39e402860893.png)


When using Neural Network Playground we ran several iterations of hidden layers and neurons. We ended up with several different types of training for the model. Finally we ran through five hidden layers and switched between 50 and 100 epochs for each. 

  **Three Hidden Layers**

 - 50 Epochs

  ![3](https://user-images.githubusercontent.com/107363203/204196869-7fb15556-b21f-4e4b-92ef-9f1b2cf4cd3b.png)

 - 100 Epochs

![4](https://user-images.githubusercontent.com/107363203/204196878-01af3d5a-5b01-4798-b3cf-f4ba908350eb.png)
___
  **Four Hidden Layers**

 - 50 Epochs

![5](https://user-images.githubusercontent.com/107363203/204196882-b2fbdede-0aea-40d6-98ad-e356a4a130d9.png)

 - 100 Epochs

![6](https://user-images.githubusercontent.com/107363203/204196894-8df627b0-2708-4036-9849-6c725e5dedff.png)
___
  **Five Hidden Layers**

  - 50 Epochs

![7](https://user-images.githubusercontent.com/107363203/204196903-c5ef35fd-03c2-4a58-b212-ea9003d3dd38.png)

  - 100 Epochs

![8](https://user-images.githubusercontent.com/107363203/204196910-acd0b172-e6b8-45f1-a092-6f70a0ac1d42.png)
___

**Were you able to achieve the target model performance of 75%?**

No. The best performance we could get for accuracy was 72.6% with using 4 layers at 50 epochs. 

**What steps did you take to try and increase model performance?**

The variables were within the hidden layers and epoch levels. We wanted to see if we were under or over training the model. 

## Summary
Increasing the amount of iterations did not change all that much. Before working on optimizating the code, the accuracy was 72.5%. After adding hidden layers and neurons per layer the greatest we could get was 72.6%.

For furthering the analysis we can either bin certain columns to create smaller data clusters. We could also use scrapping neural networks with this dataset and using a RandomForest or AdaBoost analysis to see if that type of machine learning process would better fit the data provided. 
  
