[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![Python 3.6](https://img.shields.io/badge/python-3.6-green.svg)](https://www.python.org/downloads/release/python-360/) 

# Behavioural_Cloning

  This is a Self Driving Car AI based project in which the car learns to drive on its own without the intervention of the user. This project makes use Udacity Self Driving Car simulator which reduces the burden of finding the dataset as we can generate our own dataset by manually driving the car for around 3 laps by selecting the training mode and then use the dataset for your project. 

You can download the simulator from this link:
https://s3-us-west-1.amazonaws.com/udacity-selfdrivingcar/Term1-Sim/term1-simulator-windows.zip

Autonomous Drive

![](SDCar.gif)

I have also included the weights file incase you want to run the project directly.
This project contains two part, the first part is the training part where we generate the model and the second part is running the simulator for which a flask app is to be created to link the simulator and the model we created. Once we link the simulator and the flask app we get the images from the simulator and make prediction based on which the streeing values are generated and sent back to the simulator and a constant speed is set and now the car drives on its own.

## Dependencies
```bash
numpy
pandas
matplotlib
cv2
keras
ntpath
os
imgaug
sklearn
tensorflow==1.13
random
flask
socketio
eventlet
base64
io
pillow
```

## Instructions
Make sure you have all the dependencies before you run the code.

Step 1: Open terminal and type

```bash
> git clone https://github.com/Shobhit2000/Behavioural_Cloning.git
```

Step 2: Go to the directory and run the simulator in autonomous mode

Step 3: Change the directory to cloned repository and run the drive.py file

Now see the car drive on its own.

## Author
[![LinkedIn-profile](https://img.shields.io/badge/LinkedIn-Profile-teal.svg)](https://www.linkedin.com/in/shobhit-tulshain-a7562916b/)

* [**Shobhit Tulshain**](https://github.com/Shobhit2000)
