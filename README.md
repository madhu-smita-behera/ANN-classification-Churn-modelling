# ANN-classification_-Churn-modelling

## Usage of Keras and Tensorflow
### Chrun modelling dataset
Dataset is from a bank related to whether the person is going to leave the bank or not (exited - output) => BINARY CLASSIFICATION

### Steps
1. Import the libraries
2. Import the dataset
3. Perform basic feature engineering such as convert categorical variable to numerical variable, standardization
4. Create an ANN (input -> hidden layer(s) -> output) (dropout, optimizers)
5. Convert it to a file format (pickle file or H5 file)
6. Streamlit to create a web app (from web app integrate all models and deploy it in streamlit cloud)

### ANN steps
- sequentil neural network
- dense
- activation function (sigmoid/tanH/ReLU/leaky ReLU)
- optimizers (backpropagation - updating the weights)
- loss function
- metrics (accuracy/mse/mae)
- training -> logs -> folder -> tensorboard -> visualization
