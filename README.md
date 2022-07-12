# IIRS-PROJECT

Performing Satellite Image Segmentation using SegNet algorithm.

**Dataset is downloaded from https://www.kaggle.com/c/dstl-satellite-imagery-feature-detection/data**

OBJECTIVE:  Semantic segmentation to detect and classify the types of objects found in these regions.

OVERVIEW:In this project I have used satellite image sgmentation model (SegNet) in order to classify the types of objects found in these regions. 
There are 2 band images in the given dataset format that is 3 band and 16 band images where the image format is GeoTiff format.

The SegNet model(Semantic Model). The core trainable segmentation architecture consists of an encoder network, a corresponding decoder network followed by a pixel-wise classification layer. 

I have used Jaccard Coefficient to compare the memebrs for two sets to see which memebers are shared and which are distinct.
                    
                    J(x,y) = |x∩y| / |x∪y| where J(x,y) is the Jaccard Coefficent for x and y



RESULT: The accuracy obtained is 66.745% and theaccuracy obtained on the validation dataset is 73.97%


