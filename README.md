# Computer Vision Projects

Here you will find my notebooks that track some of my tests with different deep learning models on computer vision tasks. This will serve as an ongoing place to store my work and as a reference in the future to look back on.

Please note that for some reason, the Jupyter Notebook will not render in my browser, so on the off chance that this is also the case for the user, please try to following hack: press on raw button and then go back. It should render now. If that doesn't work, you can download the notebook and upload it in your own environment.

# Table of Contents
1. Flower Classification with TPUs
2. Melanoma Classification with TPUs

# 1. Flower Classification with TPUs
 - Imported and tested popular pre-trained networks like Xception, DenseNet, InceptionResNetV2, and EfficientNet(s) to compare their performance on tensor processing units in classifying over 7,000 images into 104 different types of flowers
 - Explored augmentation techniques ranging from standard practices (random rotations, shears, crops, etc.) and newer techniques like CutMix, mixup, and AugMix to use during both training and testing (TTA)
 ![](https://1.bp.blogspot.com/-oNSfIOzO8ko/XO3BtHnUx0I/AAAAAAAAEKk/rJ2tHovGkzsyZnCbwVad-Q3ZBnwQmCFsgCEwYBhgL/s1600/image3.png)
 
 # 2. Melanoma Detection with Hair Augmentation
 - Experimented with different augmentation techniques like hair augmentation and MixUp to improve the AUC of EfficientNetB6 models 
 - Used upsampling techniques to handle extreme class imbalances (~1.8% of training and test sets contained melanoma samples)
