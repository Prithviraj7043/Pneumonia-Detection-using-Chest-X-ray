# Pneumonia-Detection-using-Chest-X-ray
Pneumonia Detection using Chest X-ray  

Dataset: Kaggle - Chest X-ray(Pneumonia)

Dataset link: 
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia/data

Tech Stack:

Python

TensorFlow

Keras

Streamlit

Data Preprocessing:

1. Initial train dataset of 5216 images is split into a training set of 4798 images and a validation set of 418 images in order to train the model.
2. Image augmentation applied on training set: width shift, height shift,  brightness shift, rotation, zoom, pixel intensity variation using channel_shift, fill_mode, pixel value normalization using rescale.
3. Rescale applied on both the validation and test datasets for pixel normalization.

Results:

Test Accuracy: 92.95% 

Recall: 98.46%

Precision: 91%

Deployment link:
https://pneumonia-detection-using-chest-x-ray-fgughjsrboqynep3mwbwqy.streamlit.app/

