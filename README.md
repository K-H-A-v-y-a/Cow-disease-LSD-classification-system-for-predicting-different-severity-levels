# Cow-disease-(LSD)-classification-system-for-predicting-different-severity-levels

## Different stages or severity levels of LSD
There are three stage in LSD according to the number of lesions visible:
1. Normal - No visible nodules
2. Mildly infected - Less than or equal to 15 lesion nodules
3. Severely infected - More than 15 lesions nodules

## Dataset
Since we didn't have a proper dataset available for our project we manually separated the available dataset with the help of veterinary Doctor, into Severe Lumpy Skin Disease, Mild Lumpy Skin Disease and Normal Skin.

## Data Augmentation
To maximize the number of images in the datasets, data augmentation is used to increase the  dataset size and the area where Lumpy Skin Disease are present is cropped.

| Category      | No of images  | After augmentation |
| ------------- | ------------- | ------------------ |
| Normal        |      686      |        2145        |
| Mild          |      110      |        1896        |
| Severe        |      198      |        2004        |

## Overall Accuracy
| CNN Models  | Overall accuracy |
|------------ | ---------------- |
| DenseNet121 |      0.8456      |
| MobileNetV2 |      0.9182      |
|    VGG19    |      0.6820      |
| Inception V3|      0.8873      |
|  Xception   |      0.8919      |
|  ResNet50   |      0.5030      |


The best model for our project is MobileNetV2 with an overall Accuracy of 91.82%
 
 
 
 










