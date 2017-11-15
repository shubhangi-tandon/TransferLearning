# TransferLearning
Image Classification model for Clothing Category


## In this Ipnyb , I'm going to build a model that can classify the Clothing Attribute Dataset which can be found at https://purl.stanford.edu/tb980qz1002 by the Category label. This is an image recognition and classification task . This dataset has only 1800 samples , out of which around 1100 samples have non - Nan values .

##  ->Therefore , the approach to be followed will be :
## Use Transfer learning ( in this case VGGNet16 trained on Imagenet data ) to learn weights for our features

## -> Train our features against a classifier . Our choice of classifier here is SVM


###  There are two ipython notebooks , one with augmented data and one without . We see , in this case that the data without augmentation does much better as compared to the data with augmentatiom
