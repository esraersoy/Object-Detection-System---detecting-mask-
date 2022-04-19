# Real-Time Face Mask Detection

Project Objective is to implement a system that can detect whether a person is wearing a face mask or not, it can be used to help preventing the spread of coronavirus. The system is built using the python language, this process will consist of various steps. The first step is the creation of dataset by capturing images through webcam. We used 23 images with mask and 23 images without mask with total of 46 images. The second step is labeling the dataset using labelIMG API. The third step is training our model using a pre-trained model, the model used here is TensorFlow Object Detection API. Lastly, the model can make real-time predictions.
</br>
</br>Used pre-trained model: SSD ResNet50 V1 FPN 640x640
</br>
Download link for all models: https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md

# Required Installations

* TensorFlow
* TensorFlow Object Detection API (https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html#tf-models-install)

# System Information

* Windows 10
* TensorFlow 2.5.0
* Python 3.9.7
* CUDA Toolkit 11.2
