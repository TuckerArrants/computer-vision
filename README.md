# Computer Vision Projects

Here you will find my notebooks that track some of my tests with different deep learning models on computer vision tasks. This will serve as an ongoing place to store my work and as a reference in the future to look back on.

# Table of Contents
1. Flower Classification with TPUs
2. Melanoma Classification with Course Dropout

# 1. Flower Classification with TPUs
 - Imported and tested popular pre-trained networks like Xception, DenseNet, InceptionResNetV2, and EfficientNet(s) to compare their performance on tensor processing units in classifying over 7,000 images into 104 different types of flowers
 - Explored augmentation techniques ranging from standard practices (random rotations, shears, crops, etc.) and newer techniques like CutMix, mixup, and AugMix to use during both training and testing (TTA)
 ![](https://1.bp.blogspot.com/-oNSfIOzO8ko/XO3BtHnUx0I/AAAAAAAAEKk/rJ2tHovGkzsyZnCbwVad-Q3ZBnwQmCFsgCEwYBhgL/s1600/image3.png)
 
 # 2. Melanoma Detection with Hair Augmentation
 - Experimented with different augmentation techniques like hair augmentation and MixUp to improve the AUC of EfficientNetB6 models 
 - Used TPUs to train over 100GBs of data and perform test time augmentation in under 3 hours
 - Used upsampling techniques to handle extreme class imbalances (~1.8% of training and test sets contained melanoma samples)
