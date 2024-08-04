# Image-caption-generator 
-------Overview of the Project-------
Image caption generator is a process of recognizing the context of an image and annotating it with relevant captions using deep learning and computer vision.
It includes labeling an image with English keywords with the help of datasets provided during model training. The imagenet dataset trains the CNN model called Xception.
Xception is responsible for image feature extraction. These extracted features will be fed to the LSTM model, which generates the image caption.
------------Dataset for Image Caption Generator----------------
The Flickr_8K dataset represents the model training of image caption generators. 
The most important file is Flickr 8k.token, which stores all the image names with captions. 8091 images are stored inside .
The Flicker8k_Dataset folder and the text files with captions of images are stored in the Flickr_8k_text folder.
----Steps to be executed-----
-->Import all the Required Packages
--->Perform Data Cleaning
--->Extract the Feature Vector
-->Load the  dataset for model training
-->Tokenizing the Vocabulary
-->Create a Data generator
--->Define the CNN-RNN model
-->Training the Image Caption Generator model
-->Testing the Image Caption Generator model
