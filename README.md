# Road-lane-detetion

A lane recognition system for smart cars under difficult road conditions and different situations are presented in this work. The suggested lane detection technique demonstrated apparent advantages about accuracy and execution time consumption. The CNN model is built using the LeNet-5 CNN architecture. The model was created using batch normalization and has a total of 30 layers. Instead of using normal Convolution layers with forward pass, here the model is created with deconvolutional layers in combination of convolution layers, upsampling and maxpooling layers to achieve the back propagation technique in CNN. The dataset used for this research is a public dataset from Kaggle that contains images extracted from various road videos. Hyper parameter optimization is done to improve the model’s accuracy in road lane prediction.  According to the trial outcomes, the average road lane prediction accuracy achieved based on the road video is 95.96%. Thus, the model is capable to detect the lane areas from different videos under the different circumstances.

#Convolutional Neural network! Model Architecture

![image](https://github.com/PranavMS007/Road-lane-detetion/assets/16048267/51bb9b51-bdbb-440f-93f7-9cfc36132858)


#Fig. 3 CNN model layer specification.

![image](https://github.com/PranavMS007/Road-lane-detetion/assets/16048267/fa376757-aedc-433c-ba3a-d41b9affa21d)


#CNN Model validation in real time

![image](https://github.com/PranavMS007/Road-lane-detetion/assets/16048267/a401c4f9-af61-4b56-9339-ef7e1e841046)

#Fully Convolutional Neural Network Model

![image](https://github.com/PranavMS007/Road-lane-detetion/assets/16048267/6c6ebc92-e262-4371-abf0-819df24ca20d)

#Model response for real time video.

![image](https://github.com/PranavMS007/Road-lane-detetion/assets/16048267/3c04af37-e40b-470f-8101-91d5edba774d)



