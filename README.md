# COVID-19 Detector using Custom Made CNN

The Project objective is to develop a computer-based system for detecting Covid-19 virus. We employ deep learning techniques(convolution neural networks) to train our model and classify X-Ray chest scans into COVID and non-COVID categories, automating the detection process and allowing for speedier diagnosis. The following are the three stages of our methodology:

A. Preprocessing and Augmentation of Data
We're leveraging built-in features to perform data augmentation, which involves applying a series of actions to each image in the batch, such as zooming, cropping, and resizing, to add more training data.

B. Extraction and Selection of Features
The main goal of this procedure is to improve performance by eliminating duplicate and useless features.Convolution processes images using a series of convolutional filters, each of which activates and extracts different features from the images.
Pooling reduces the number of parameters the network must learn by performing non-linear down sampling on our output.

C. Classification of Images
The output of the last pooling layer works as an input to the fully connected layer at the conclusion of a CNN, and this layer has an activation function called ReLU.
Finally, the prediction layer categorizes the input into one of two outputs (COVID or not).



# Dataset links

https://drive.google.com/drive/folders/1LFDwkeiYT3kGtIiGFFA_l87P-4-DJdud?usp=sharing

https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia?resource=download

https://github.com/ieee8023/covid-chestxray-dataset
