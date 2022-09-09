# A experimental demo of  FaceShifter (Model C)

## Most of codes are referenced from [Research_Project](https://github.com/richarduuz/Research_Project) and  [FaceShifter](https://github.com/taotaonice/FaceShifter). Thank these authors.


## Project Objective
Our project aims to find a suitable DeepFake model, in terms of visual quality, inferencing speed and easiness of deploying, to deploy on as Android demo application server. We have uploaded and referenced code of all 3 potential models we selected in addition with our Android application package and server.

## Code Reference
In this repo, there are 3 models we referenced from 3 authors.

**Model C**: [FaceShifter](https://github.com/taotaonice/FaceShifter)

## Image Results by Model C

<img src="https://github.com/richarduuz/Research_Project/blob/master/model_c_image_result.jpg" width="400">

## Video Results by Model C
Here we show a short gift instead of the actual videos.

- This is the result generated from Model C. Inputs are a image and a video. 
  <img src="https://github.com/richarduuz/Research_Project/blob/master/Model_C_Video_Gif.gif" width="400">

## What you can try
Feel free to give these models a try if you are interested. Simply click on the following links and try them on Colab. Remember to set the hardware accelerator in the notebook setting as GPU. More details are in directory of each model and their notebook. You don't need to train any model before trying them.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/richarduuz/Research_Project/blob/master/ModelC/ModelC.ipynb) Try **Model C** in Colab Notebook, the colab notebook only has the demo for swap face between two images. Other demo like video face swapping, training, server deployment can be seen in directory ModelC. You can download code and run them locally. The detailed description can be seen at README in ModelC directory.

The demo Android application is uploaded to present our work. You can download and install it. However it is not able to translate faces without server. We only turned on our server during our testing and presentation. Server code is uploaded as well and you can find it in directory ModelC. You may deploy it on your own and change server url to try this demo.

Please refer to model C directory for more detail and instruction.
