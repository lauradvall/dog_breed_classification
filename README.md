[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview

Given an image of a dog, this CNN will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  The CNN is a basic four-layer convolutional network plus 3 linear layers for classification.

![Sample Output][image1]



## Requirements
The following packages need to be installed in your environment:
- numpy
- glob
- Opencv (cv2)
- matplotlib
- tqdm
- torch
- torchvision
- PIL
