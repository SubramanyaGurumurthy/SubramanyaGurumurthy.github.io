# Projects 

## 1. [Real-time Hand gesture Detection using Mediapipe](https://github.com/SubramanyaGurumurthy/RealTimeHandgestureDetection.git)

### Gesture Volume Control
In this module, user can control the device's volume using hand gesutre. Basically in this module, the program detects hand using MediaPipe library, 
within which, the tip of the index finger and tip of the thumb is recognised and used further for controlling the volume. The volume increases as the user elongates 
the length between tip of index finger and thumb, and volume decreases as the user decreases it. For details, please refer to gif provided below.
![volume control](https://github.com/SubramanyaGurumurthy/RealTimeHandgestureDetection/blob/main/gif/Volume_control.gif)


### Paint Module
In this module, user can paint on the camera screen using finger gestures. Similar to volume control module, here the program first detects the hand and the tip of 
the index finger and middle finger is extracted from the detected points. The painter module offer 3 different colors to chose from and an eraser options. By using both
middle finger and index finger together and closing other fingers, user can switch between colors or eraser which can be found on the top of the screen. After selection,
the user can paint or erase by just using index finger. By default in the beginning, pink color will be selected. For the visual demonstration [click here](https://youtu.be/u2zQ_nwl4WA)

## [Semantic Segmentation using Pytorch (On Going)](https://colab.research.google.com/drive/1FnwAzHF5YFaVst41jaXHYwjBXWSFyd0o?usp=sharing)
•	In this project, I am training and tuning the hyper-parameters for DeeplabV3_resnet101 model using open source data (comma10k) related to road images, 
  which were taken using camera placed inside the car.
•	I am using google colab for training and testing the model.

![Raw Image](https://github.com/commaai/comma10k/blob/master/imgs/0000_0085e9e41513078a_2018-08-19--13-26-08_11_864.png)
![Segmented Image](https://github.com/SubramanyaGurumurthy/SubramanyaGurumurthy.github.io/blob/main/0000_0085e9e41513078a_2018-08-19--13-26-08_11_864%20(1).png)
