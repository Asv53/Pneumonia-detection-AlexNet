# Pneumonia-detection-AlexNet
A deep learning model that leverages Transfer Learning approach to accurately detect Pneumonia with AlexNet

In this project we have modified the last layer of the AlexNet model and retrained the model OUT CLASSES = 2 (NORMAL, PNEUMONIA) with CXR Images dataset from Kaggle.

## DATASET

We have used is https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia?rvi=1
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

## CODE is available in alex-cnn.ipynb file.

## RESULTS

Accuracy: *82.7500*

Recall: *90.0000*

Precision: *78.6026*

F1 Score: *83.9161*

Confusion Matrix:
*[[604 196]
 [ 80 720]]*

### *Adjust the dataset paths correctly*
