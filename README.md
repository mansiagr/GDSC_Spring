# GDSC_ML_Project

## Goal of our Project

We chose this project because we wanted to help blind people engage with video calls in a better way. We hope that through our project, blind people will be able to receive helpful information about people's facial expressions during video calls. 

## Introduction

We used various machine-learning tools and libraries to detect facial emotions. We used a convolution neural network to train our model so that it can understand what certain emotions look like. We also implemented our model to work with the webcam as well. Since our project is supposed to help blind people, we also implemented a feature that reads aloud the emotion detected from the webcam. 

## Methods

To start this project, we first researched different data sets that might be useful for this project to train our machine learning model. We also looked for different libraries and tools that might be useful in this project. 

Using this information, we started detecting facial expressions in static images using the FER library. We were able to see results, but we quickly saw that the accuracy was not great and we realized that we would have to train our model more.

We then started implementing our CNN model, and we saw that we had more accuracy in detecting facial expressions in static images. We then tried detecting facial expressions using the webcam too, and we were able to see the results.  

We also used the gTTs library and the playsounds library to convert our text to speech. This allowed us to get verbal feedback and we could hear the emotions predicted instead of it just being displayed on the screen.

## Future Applications

In the future, we hope to create a product that users can directly interact with and actually use this model. We hope to create a web application for the functionality. We also hope to further increase the accuracy of our model by having it detect the start and end point of the user's lips and using that data to predict emotions. If the lips moved up, it would predict the emotion as being happy. 
