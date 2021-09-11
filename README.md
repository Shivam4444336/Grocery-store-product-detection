## Grocery store product detection:
- This repository contains scripts for grocery store product detection. 
## Dataset preparation:
- [Grocery Dataset](https://github.com/gulvarol/grocerydataset) had products from 10 categories/brand indexed from 1-10 and one no product category indexed as 0.To leverage no product vs product detection classes 1-10 were assigned an index of 1 with label 'Product' and the other category with 0 index was labelled as 'No Product'.Steps for detailed dataset preparation has been mentioned in [Data_Preparation.ipynb file](https://github.com/Shivam4444336/Grocery-store-product-detection/blob/main/Data_Preparation.ipynb).
## Data Augmentation applied:
 - Data Augmentation :
 - Saturation Augmentation 
 - Random Brightness Augmentation
 - Random Scaling Augmentation
 - Mosiac Augmentation
## Detection Network used:
 - Yolo_v5_P6 model at resolution of 1280 was used for detection.Detection objects in this case are relatively small so higher resolution was used.
## Training Hyperparameters:
 - Batch Size -  4
 - Image resolution - 1280 
 - Optimizer - Adam
 - Epochs - 175
## Test data sample results:
 
