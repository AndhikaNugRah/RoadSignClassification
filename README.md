Road Sign Recognition

Overview
Road sign recognition is a critical component of advanced driver assistance systems (ADAS) and autonomous vehicles. 
It enables vehicles to understand their surroundings, make informed decisions, and enhance road safety. 
This project aims to develop a robust road sign recognition model using transfer learning with the VGG16 architecture.

Model Architecture
The proposed model is based on the VGG16 architecture, a pre-trained convolutional neural network (CNN) that has achieved excellent performance in various image classification tasks. 
To adapt VGG16 for road sign recognition, employ transfer learning, a technique that leverages the knowledge gained from a pre-trained model on a large dataset to improve performance on a new, related task.

Training and Evaluation:
The model was trained on a dataset of road signs, with 40 samples for each sign. 
It achieved a validation loss of 0.20. 
When tested on 34 images from the validation dataset, it correctly predicted 82% of the signs. 
When tested on the test dataset, it achieved a 97% accuracy rate.
