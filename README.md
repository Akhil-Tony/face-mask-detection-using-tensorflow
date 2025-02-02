<h1 align="center"> Face Mask Detection :mask: </h1>
<div align = "center">
<img src = "https://github.com/Akhil-Tony/Face-Mask-Detection/blob/master/20220814_011941.gif" />
</div>
<h4>Face Mask Detection System built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.</h4>

## :star: Frameworks used
- TensorFlow
- OpenCV
- Keras
- Numpy

## :bulb: Transfer Learning 
- build by reusing lower layers of Xception Model 

## :file_folder: Dataset
This dataset consists of __1984 images__ belonging to two classes:
<br>
*	__with_mask: 984 images__
*	__without_mask: 1000 images__

## :gear: Data Augmentation 

* Used Data Augmentation to reduce overfitting and improve performance even on poor lighting condition.

## :key: Results

- Thanks to Transfer Learning, model gave 98% accuracy for Face Mask Detection after training for 5 Epochs
