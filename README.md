# Classifier-to-Detector
Converting Classifier to Object Detector with TensorFlow

This project involves creating a TF object Detection Model using an already trained classifier. For this project, I've converted a pothole image classifier to be able to detect potholes in image frames. 

In order to create the object detection model, there are several steps that need to be followed.

# Steps
1. Annotating training images using labelImg or any other annotation tool. You can also use Amazon SageMaker or Labelbox if you don't want to manually label your data.
2. Perform Data Augmentation on annotated data
3. Export Annotated data in Pascal VOC XML, YoloV3 or TFRecord file.
4. Use this exported to train the model.

Before using this notebook, you'll have to perform steps 1-3 and then insert the annotated data where it is required. Please take time to read the comments in the code.

For more details, please see this tutorials:
https://blog.roboflow.com/object-detection/
https://blog.roboflow.com/getting-started-with-roboflow/


A Big thank you to the team at RoboFlow for making several modifications to their model library to enable it run efficiently on google colab.

Best of Luck.

