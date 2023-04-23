# Covid-19 image-classification

* Images from CT-Scan with either Covid 19, Viral Pneumonia or Normal (no disease)
* ![](https://github.com/janS95/major_4_us_sports/blob/main/images/nba_map.png)
* Created some Data Augmentation (slight rotation and flipping the image horizontal) because the dataset is rather small
* Build two CNNs:
  * Used VGG-19 with pre trained weights and added a softmax layer for classification at the end. Got accuracy of about 94 %.
  * Did some experiments with own CNN architecture. Got accuracy of about 86 %.
