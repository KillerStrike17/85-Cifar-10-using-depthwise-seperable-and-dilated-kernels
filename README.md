## Model

Here we have used Dilated Convolutions instead of Strided or Max pooling layers. 
We have also used depthwise seperable convolution as the last kernel of out C4 block.
The following is the full architecture. 
Total Parameters are - 1,76,574

![Model1](https://github.com/KillerStrike17/85-Cifar-10-using-depthwise-seperable-and-dilated-kernels/raw/main/Assets/Model1.PNG)

![Model2](https://github.com/KillerStrike17/85-Cifar-10-using-depthwise-seperable-and-dilated-kernels/raw/main/Assets/Model2.PNG)


## Augmentation

Here we have applied
1. Horizontal Flip
2. Shift Scale Rotate
3. Coarse Dropout. 

The code is implemented like this

![code](https://github.com/KillerStrike17/85-Cifar-10-using-depthwise-seperable-and-dilated-kernels/raw/main/Assets/code.PNG)

## Results

Training Max Accuracy - 76.98%
Testing Max Accuracy - 85.24%
Total Epochs - 100

### Logs

![logs1](https://github.com/KillerStrike17/85-Cifar-10-using-depthwise-seperable-and-dilated-kernels/raw/main/Assets/logs1.PNG)

![logs2](https://github.com/KillerStrike17/85-Cifar-10-using-depthwise-seperable-and-dilated-kernels/raw/main/Assets/logs2.PNG)

![logs3](https://github.com/KillerStrike17/85-Cifar-10-using-depthwise-seperable-and-dilated-kernels/raw/main/Assets/logs4.PNG)

![logs4](https://github.com/KillerStrike17/85-Cifar-10-using-depthwise-seperable-and-dilated-kernels/raw/main/Assets/logs4.PNG)


### Curves

![graphs](https://github.com/KillerStrike17/85-Cifar-10-using-depthwise-seperable-and-dilated-kernels/raw/main/Assets/graphs.png)

### Misclassified images

![misclassifiedimages](https://github.com/KillerStrike17/85-Cifar-10-using-depthwise-seperable-and-dilated-kernels/raw/main/Assets/misclassified%20images.png)

![matrix](https://github.com/KillerStrike17/85-Cifar-10-using-depthwise-seperable-and-dilated-kernels/raw/main/Assets/matrix.png)

