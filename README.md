# Projects 

## [1. Real-time Hand gesture Detection using Mediapipe](https://github.com/SubramanyaGurumurthy/RealTimeHandgestureDetection.git)
Realtime pose detection of the human body is an important task in computer vision as the detected results can be further used for understanding and to analyze person's position, and the task that the person is performing. In this work I have used the [Mediapipe library](https://google.github.io/mediapipe/solutions/hands) by google for the detection and tracking of key points. The proposed application uses the raw pixel values of the captured image to detect different points on the human body. I further use these points for different sub-tasks such as Gesture Volume Control, Paint App using fingers.

### - Gesture Volume Control
In this module, user can control the device's volume using hand gesutre. Basically in this module, the program detects hand using MediaPipe library, within which, the tip of the index finger and tip of the thumb is recognised and used further for controlling the volume. The volume increases as the user elongates the length between tip of index finger and thumb, and vice versa. For details, please refer to gif provided below.

![volume control](https://github.com/SubramanyaGurumurthy/RealTimeHandgestureDetection/blob/main/gif/Volume_control.gif)

### - Paint Module
In this module, user can paint on the camera screen using finger gestures. Similar to Gesture_Volume_control module, here the program first detects the hand and within which the index finger and thumb tip positions are extracted. Using the extracted details, the user's gesture is painted on the screen. The painter module offer 3 different colors to chose from and an eraser options. By using both middle finger and index finger together and closing other fingers, user can switch between colors or eraser which can be found on the top of the screen. After selection, the user can paint or erase by just using just index finger. By default in the beginning, pink color will be selected. For the visual demonstration [click here](https://youtu.be/u2zQ_nwl4WA)

## [2. Semantic Segmentation using Pytorch (On Going)](https://colab.research.google.com/drive/1FnwAzHF5YFaVst41jaXHYwjBXWSFyd0o?usp=sharing)
* Semantic segmentation (SS) is an important perception manner for self-driving cars and robotics, which classifies each pixel into a pre-determined class. 
* Semantic segmentation requires both rich spatial information and sizeable receptive field. However, modern approaches usually compromise spatial resolution to achieve real-time inference speed, which leads to poor performance.
* Understanding the importance and wide area of application of semantic segmentation, I am training a model using [commas10K](https://github.com/commaai/comma10k) dataset which contains images of roads and highways.
* I am using [pytorch-deeplabv3-Resnet101](https://pytorch.org/vision/stable/models/generated/torchvision.models.segmentation.deeplabv3_resnet101.html#torchvision.models.segmentation.DeepLabV3_ResNet101_Weights) pre-trained model to perform semantic segmentation, which can be used in Autonomous driving domain.
*	I am using google colab for training and testing the model
