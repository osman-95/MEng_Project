## Instructions

**Notice: ALL codes are still under progress and subjected to change**


1. [**Building_classification_dataset.ipynb**](https://github.com/osman-95/Project_Progress_2/blob/master/Final_Model/Code/Building_classification_dataset.ipynb) contains the code implented for building the [classifiction dataset](https://github.com/osman-95/Project_Progress_2/tree/master/Final_Model/Datasets) from our object detection annotation csv file.


2. [**Classification_data_preprocessing.ipynb**](https://github.com/osman-95/Project_Progress_2/blob/master/Final_Model/Code/Classification_data_preprocessing.ipynb) contains the code implemented so far to prerocess and clean the data generated for classifcation model and train our neural network for classification


3. [**Object_detection_training**](https://github.com/osman-95/Project_Progress_2/blob/master/Final_Model/Code/Object_Detection_training.ipynb) contains the code implemented to setup the environment and train our object detection model(Mobilenetv2) with our custom dataset. This code is recommended to be executed in the [object detection directory](https://github.com/osman-95/Project_Progress_2/tree/master/Project_tasks/Mobilenet/models_Tf/research/object_detection) as it require various essential packages and codes that are configured with respect to this directory. Essential files that are not available on Github repository are included in this [drive](https://drive.google.com/drive/folders/1yfKKVxpYeO937jPCwaGL4C0D4id7lsrs?usp=sharing)


4. [**Object_detection_testing**](https://github.com/osman-95/Project_Progress_2/blob/master/Final_Model/Code/Object_Detection_testing.ipynb) contains the code implemented to test our object detection model on test images and webcam.

5. [**Object_Detection_based_classification.ipynb**](https://github.com/osman-95/Project_Progress_2/blob/master/Final_Model/Code/Object_Detection_based_classification.ipynb) contains the code implemented to test the complete objective of the project by taking and image or a video and an input and detect the object in the frame and the object detected are fed into the classification model to predict the class of the whole image or video. The model was tested on images as well as a webcam  
