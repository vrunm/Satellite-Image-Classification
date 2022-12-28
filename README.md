# Satellite-Image-Classification
## Data
This dataset has 4 different classes mixed from Sensors and google map snapshot.
The objective is to predict the images into 4 classes: cloudy , desert , green_area , desert.


The mobilenet v2 cnn architecture was fit for this data which gave an accuracy of 0.99.
Also a CNN with :
</br>
2 Convolutional Layers
</br>
1 Batch Normalization Layer
</br>
1 Max Pooling Layer
</br>
1 Flatten Layer
</br>
1 Dropout Layer
</br>
3 Dense Layer was implemented which gave an accuracy of 0.88.
| Model       | Accuracy    | 
| :---        |    :----:   |  
| Baseline CNN    | 90%      |
| Mobilenetv2     | 99%      | 
