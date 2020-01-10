# Tutorial-Projects

## 1.MNSIT  
It contains images of digits taken from a variety of scanned documents, normalized in size and centered. Each image is a 28 by 28 pixel square (784 pixels total). The dataset contains 60,000 images for model training and 10,000 images for the evaluation of the model.

The task is to classify a given image of a handwritten digit into one of 10 classes representing integer values from 0 to 9, inclusively.

I have implemented three CNNs on this dataset. 

MODEL 1: A Simple model with 3 layers.

- Train accuracy: 100%
- Validation accuracy: 98.90
- Number of epochs: 50
- Runtime : 13-15mins

MODEL 2: With multiple layers of Conv2D along with batch normalization and dropout. T
- Train accuracy: 99.87%
- Validation accuracy: 99.31
- Number of epochs: 50
- Runtime : 28 - 30 mins

MODEL 3: Same as MODEL 2, except that instead of Flatten, GlobalMaxPooling is used. 
- Train accuracy: 99.84%
- Validation accuracy: 99.31
- Number of epochs: 50
- Runtime : 26 - 28 mins
