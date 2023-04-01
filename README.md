## Pandas/Grizzly Image Classification Using Deep Learning

### This project demonstrates the use CNN to classify images of Pandas and Grizzlies.

## Link to use Streamlit based WebApp of this CNN Model:
https://aashutoshdubey0-pandas-grizzly-claassifier-app-0j99f8.streamlit.app/


## Model and Architecture
This is a Convolutional Neural Network (CNN) architecture for binary image classification, with the final output being either a positive or negative class. Here is a brief description of the architecture:

- The first layer is a 2D convolutional layer with 16 filters, each with a 3x3 kernel, a stride of 1, and a ReLU activation function. The input shape of each image is 256x256x3.
- The second layer is a 2D max pooling layer with default parameters, which reduces the spatial dimensions of the feature maps by a factor of 2.
- The third layer is another 2D convolutional layer with 32 filters, each with a 3x3 kernel, a stride of 1, and a ReLU activation function.
- The fourth layer is another 2D max pooling layer with default parameters.
- The fifth layer is a 2D convolutional layer with 16 filters, each with a 3x3 kernel, a stride of 1, and a ReLU activation function.
- The sixth layer is another 2D max pooling layer with default parameters.
- The seventh layer is another 2D convolutional layer with 32 filters, each with a 3x3 kernel, a stride of 1, and a ReLU activation function.
- The eighth layer is another 2D max pooling layer with default parameters.
- The ninth layer flattens the output of the previous layer into a 1D vector.
- The tenth layer is a fully connected dense layer with 256 units and a ReLU activation function.
- The eleventh and final layer is a fully connected dense layer with 1 unit and a sigmoid activation function, which produces the final output of the network.

## Input Shape
The input shape of the network is (256, 256, 3), which means that the input image is of size 256x256 pixels and has 3 channels (RGB).

## Parameters
The first convolutional layer has 16 filters, the second convolutional layer has 32 filters, and the third convolutional layer has 16 filters. The number of filters determine the number of feature maps produced by each layer. The dense layers have 256 and 1 units respectively.
