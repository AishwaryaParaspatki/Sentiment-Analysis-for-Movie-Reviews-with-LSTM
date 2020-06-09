# Sentiment Analysis for Movie Reviews with LSTM

This is a project depicts a basic LSTM model to analyse sentiments based on IMDB's movie reviews dataset.<br>

### Technology Stack:<br>
Python<br>
Keras - TensorFlow<br>
sklearn<br>
matplolib<br>
seaborn<br>

### Dataset:<br>
I hacve used the IMDB dataset provided in the keras dataset library.<br>

### Workflow of the notebook:<br>
1. Loading the data using the keras dataset for IMDB.<br>
2. Splitting data into training and testing data.<br>
3. Preprocessing the data: Padding sequences to the same length.<br>
4. Building the model:<br>
  a. Converting the vocabulary into integers using embeddings in the first layer of the model.<br>
  b. Add LSTM layer with 128 units.<br>
  c. Add output layer with sigmoid activation.<br>
  d. Used binary cross entropy as the loss function and RMSprop optimizer with accuracy as the evaluation metric.<br>
 5. Plot accuracy for each epoch using the RMSprop optimizer:<br>
 ![TrainvsValidationacc](/images/TrainvsValidationAcc.png)
 6. Plot confusion matrix:<br>
 ![Confusion_Matrix](/images/Confusion_matrix.png)

<br>
Training vs Validation Accuracy with SGD Optimizer:<br>
![SGD](/images/SGD.png)
<br>
Training vs Validation Accuracy with Adam Optimizer:<br>
![Adam](/images/Adam.png)
