# FACE-MASK-DETECTION-WITH-ALERT-AND-ACCESS-CONTROL
<h1 align="center">Face Mask Detection</h1>

<div align= "center">
  <h3>Face Mask Detection system built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.If the person captured without wearing mask he will captured and send his picture to the concerned authorities </h3>
</div>


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Live Demo](https://github.com/karthik-1105/REAL-TIME-FACE-DETECTION-WITH-ALERT-AND-ACCESS-CONTROLLING-SYSTEM/Demo.gif)



## :warning: Tech/framework used

- [OpenCV](https://opencv.org/)
- [Caffe-based face detector](https://caffe.berkeleyvision.org/)
- [Keras](https://keras.io/)
- [TensorFlow](https://www.tensorflow.org/)
- [MobileNetV2](https://arxiv.org/abs/1801.04381)

## :star: Features
Our face mask detector didn't use any morphed masked images dataset. The model is accurate, and since we used the MobileNetV2 architecture, it’s also computationally efficient and thus making it easier to deploy the model to embedded systems (Raspberry Pi, Google Coral, etc.).

This system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak of Covid-19. This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.


## :bulb: Working and ## :key: Results


#### FACE MASK DETECTION WILL SEND THE PICTURE OF PERSON WHO DOESN'T WEAR THE MASK

![](https://github.com/karthik-1105/REAL-TIME-FACE-DETECTION-WITH-ALERT-AND-ACCESS-CONTROLLING-SYSTEM/11.png)
![](https://github.com/karthik-1105/REAL-TIME-FACE-DETECTION-WITH-ALERT-AND-ACCESS-CONTROLLING-SYSTEM/22.png)
![](https://github.com/karthik-1105/REAL-TIME-FACE-DETECTION-WITH-ALERT-AND-ACCESS-CONTROLLING-SYSTEM/33.png)
![](https://github.com/karthik-1105/REAL-TIME-FACE-DETECTION-WITH-ALERT-AND-ACCESS-CONTROLLING-SYSTEM/44.png)

#### Our model gave 91% accuracy for Face Mask Detection after training via <code>tensorflow-gpu==2.0.0</code>

![](https://github.com/chandrikadeb7/Face-Mask-Detection/6.png)

#### We got the following accuracy/loss training curve plot
![](https://github.com/chandrikadeb7/Face-Mask-Detection/plot.png)

