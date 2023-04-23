# Covid-19 image-classification

* Images from CT-Scan with either Covid 19, Viral Pneumonia or Normal (no disease)
* Created some Data Augmentation (slight rotation and flipping the image horizontal) because the dataset is rather small
* Build two CNNs:
  * Used VGG-19 with pre trained weights and added a softmax layer for classification at the end. Got accuracy of about 94 %.
  * <img src="https://github.com/janS95/covid-19_classification/blob/main/images/vgg_loss_curve.png" width="276" height="228">
  * Did some experiments with own CNN architecture. Got accuracy of about 86 %.
  * <img src="https://github.com/janS95/covid-19_classification/blob/main/images/cnn_loss_curve.png" width="282" height="228">

# Example image:
<img src="https://github.com/janS95/covid-19_classification/blob/main/dataset/train/Normal/01.jpeg"  width="300" height="300">
