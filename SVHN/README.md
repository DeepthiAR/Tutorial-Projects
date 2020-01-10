# SVHN Dataset

Much similar to MNIST(images of cropped digits), but SVHN contains much more labeled data (over 600,000 images) with real world problems of recognizing digits and numbers in natural scene images.

The images are 32x32 cropped images, each image contains a single number. 

73,257 digits(images) for training, 26,032 digits(images) for testing

## Preprocessing

1. Reshaped the the train and test data by converting it from (width, height, channels, size) -> (size, width, height, channels)
2. Converted the images to grayscale
3. Normalized the data
4. Performed One Hot label encoding 

## MODEL

MODEL 1: 
- 3 Conv2D layers with 32,64 and 128 filters respectively, with kernel of size 3x3, followed by Flatten, 2 layers of Dense.
- Adam Optimizer used
- Batch_size = 128
- epochs = 25
- Train accuracy = 91.61%
- Test accuracy = 90.90%
- Time taken: 20 - 25 mins

MODEL 2:
- 4 Conv2D layers with 16,32,64 and 128 filters respectively, with kernel of size 3x3, followed by Flatten and 2 layers of Dense.
- Adam Optimizer used
- Batch size = 128
- epochs = 25
- Train accuracy = 96.56%
- Test accuracy = 92.96%
- Time taken: 37 - 45 mins

