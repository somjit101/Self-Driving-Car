# Self Driving Car
An implementation of a simple self-driving car control using the image feed from a single dashcam. 

## Overview

Here, we use images which are frame-by-frame captures from the dashcam of a car and the ideal steering angle (the angle by which the steering is rotated by an experienced driver, in degrees) at the corresponding moments of the captures to train a Deep Neural Network to predict the momentary steering angle in a self-driving car. The output steering angles have actually been smoothened using a fine-tuned exponential smoothing operation to avoid any sudden movements or 'jerks' in the real-world actuation of the output. 

Here, we have highly simplied the self-driving use case. There is no speed control, braking, proximity sensors or multi-camera setup. We have simply implemented the steering output from the autopilot system. 
