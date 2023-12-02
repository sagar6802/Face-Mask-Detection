
<h1 align="center">Face Mask Detection</h1>

<div align= "center"><img src="https://github.com/Vrushti24/Face-Mask-Detection/blob/logo/Logo/facemaskdetection.ai%20%40%2051.06%25%20(CMYK_GPU%20Preview)%20%2018-02-2021%2018_33_18%20(2).png" width="200" height="200"/>
  <h4>Face Mask Detection System built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.</h4>
</div>



&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Live Demo](https://github.com/chandrikadeb7/Face-Mask-Detection/blob/master/Readme_images/Demo.gif)



## :innocent: Motivation
Amid the ongoing COVID-19 pandemic, there are no efficient face mask detection applications which are now in high demand for transportation means, densely populated areas, residential districts, large-scale manufacturers and other enterprises to ensure safety. The absence of large datasets of __‘with_mask’__ images has made this task cumbersome and challenging. 





<p align="center"><img src="https://github.com/chandrikadeb7/Face-Mask-Detection/blob/master/Readme_images/Screen%20Shot%202020-05-14%20at%208.49.06%20PM.png" width="700" height="400"></p>


## :warning: TechStack/framework used

- [OpenCV](https://opencv.org/)
- [Caffe-based face detector](https://caffe.berkeleyvision.org/)
- [Keras](https://keras.io/)
- [TensorFlow](https://www.tensorflow.org/)
- [MobileNetV2](https://arxiv.org/abs/1801.04381)

## :star: Features
Our face mask detector doesn't use any morphed masked images dataset and the model is accurate. Owing to the use of MobileNetV2 architecture, it is computationally efficient, thus making it easier to deploy the model to embedded systems (Raspberry Pi, Google Coral, etc.).

This system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak of Covid-19. This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.

## :file_folder: Dataset
The dataset used can be downloaded here - [Click to Download](https://github.com/chandrikadeb7/Face-Mask-Detection/tree/master/dataset)

This dataset consists of  belonging to two classes:
*	__with_mask__
*	__without_mask__



## 🚀&nbsp; Installation
1. Clone the repo
```
$ git clone https://github.com/chandrikadeb7/Face-Mask-Detection.git
```

2. Change your directory to the cloned repo 
```
$ cd Face-Mask-Detection
```

3. Create a Python virtual environment named 'test' and activate it
```
$ virtualenv test
```
```
$ source test/bin/activate
```

4. Now, run the following command in your Terminal/Command Prompt to install the libraries required
```
$ pip3 install -r requirements.txt
```

## :bulb: Working

1. Open terminal. Go into the cloned project directory and type the following command:
```
$ python3 train_mask_detector.py --dataset dataset
```

2. To detect face masks in an image type the following command: 
```
$ python3 detect_mask_image.py --image images/pic1.jpeg
```

3. To detect face masks in real-time video streams type the following command:
```
$ python3 detect_mask_video.py 
```
## :key: Results

#### Our model gave 98% accuracy for Face Mask Detection after training via <code>tensorflow-gpu==2.5.0</code>

<a href="https://colab.research.google.com/drive/1AZ0W2QAHnM3rcj0qbTmc7c3fAMPCowQ1?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
####          
![](https://github.com/chandrikadeb7/Face-Mask-Detection/blob/master/Readme_images/Screenshot%202020-06-01%20at%209.48.27%20PM.png)

#### We got the following accuracy/loss training curve plot
![](https://github.com/chandrikadeb7/Face-Mask-Detection/blob/master/plot.png)

## Streamlit app

Face Mask Detector webapp using Tensorflow & Streamlit

command
```
$ streamlit run app.py 
```
## Images

<p align="center">
  <img src="Readme_images/1.PNG">
</p>
<p align="center">Upload Images</p>

<p align="center">
  <img src="Readme_images/2.PNG">
</p>
<p align="center">Results</p>


