# Image Colorization [[Project Page]](https://github.com/Computer-Vision-IIITH-2021/project-provision) 

** Team provision -
[Vaibhav Gupta](https://github.com/whynotkush) ,
[Navaneet Singh]() , 
[Suman Mitra]() ,
[Rohit Jamuar]()  . CV project [IIITH 2021](https://www.iiit.ac.in/).

![Einstein](https://github.com/Computer-Vision-IIITH-2021/project-provision/blob/main/colorisation.png)

## Objective
The task is to use a convolutional neural network for image colorization which turns a grayscale image to a colored image.
By converting an image to grayscale, we loose color information, so converting a grayscale image back to a colored version 
is not an easy job.

## Dataset
[MIT Places](http://places.csail.mit.edu/)  Dataset of lanscapes , places and buildings is used for the colorization.
 
The dataset consists of total 41000 colored images.

Each image is of shape (224,224,3) 

Division the of Dataset is as follows :

- Training  : 32800
- validation: 8200

The training Batch contains images in a random order .

MIT also offers a [Places205](http://places.csail.mit.edu/downloadData.html) image dataset which contains a total of 2,448,873 images . We are unable to train the model on this dataset because of the time constraint but reader is welcome to use this dataset. Accuracy of colors in Image Colorization can improve overwhelmingly with larger input data for the model to train on. 



## Convolutional Neural Network (CNN) to Color Grayscale Images
Convert the original 224x224x3 images to grayscale 224x224x1 images. 

The grayscale images are inputs of the network. 
Set up a convolutional neural network with Batch Normalization. Use 3x3 filters and a softmax output layer.
Using the L channel as the input to the network  we train the network to predict the ab channels.

![Model](https://github.com/Computer-Vision-IIITH-2021/project-provision/blob/main/colorization.png)

## Results

![Output](https://github.com/Computer-Vision-IIITH-2021/project-provision/blob/main/output.png)

project-provision created by GitHub Classroom
