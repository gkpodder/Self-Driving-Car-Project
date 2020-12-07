# Self-Driving-Car-Project

This project is done with behavioural learning by implenting a convolutional neural network(CNN) from Nvidia. The model was trained using a dataset composed of hundreds of images from a driving simulator provided by udacity's self-driving car nanodegree. To increase the size of the dataset and reduce the chances of overfitting a preprocessing step was implemented to augment the images by slight rotations, filters, blur and resize. This was effective in reducing overfitting and helped diversify the dataset. 

The model works by taking a frame from the simulator at an instance and predicting the appropriate steering angle for that instance. For the purposes of this project I chose to keep the car's speed constant and instead focused on making the model work on a different track then the original track.

The image below will link to a video showing the model in action(the model and server communication is included in the repository):

[![Video](http://img.youtube.com/vi/E0NfMECe-SU/0.jpg)](https://www.youtube.com/watch?v=E0NfMECe-SU&t=100s)
