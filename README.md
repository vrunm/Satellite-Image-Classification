# Satellite-Image-Classification
- Built an image classification model to predict four different types of geographical areas that are present in a satellite image.
- Compared 4 different CNN architectures ie. a custom CNN, InceptionV2,   MobileNetV2 , EfficientNetB3 based on model performance on this dataset.

## Data
This dataset has 4 different classes mixed from sensors and google map snapshot.
The objective is to predict the images into 4 classes: cloudy , desert , green_area , desert.

The dataset can be downloaded from [here]:(https://www.kaggle.com/datasets/mahmoudreda55/satellite-image-classification)

## Experiments
#### MobileNetV2:

- The **MobileNetV2** model was initialized with pre-trained ImageNet weights and all the layers were fine-tuned. Training the model with an **Adam optimizer with learning rate of 0.001** for **8 epochs** yielded an **Accuracy of 99.2%**.

#### Custom CNN:

- A baseline was created using a custom CNN model with 2 convolution layers and 3 dense layers. A **kernel of size 3 x 3** was used for all the convolution layers. A dropout layer was used with dropout rate 0.1 .Training the model with an **Adam optimizer with learning rate of 0.001** for 5 epochs yielded an accuracy of 90%.

#### InceptionV2:

- The **InceptionV2** model was initialized with pre-trained ImageNet weights. Only the Dense layers were fine-tuned. Training the model with an **Adam optimizer with learning rate of 0.001** for **5 epochs** yielded an **Accuracy of 88.92%.**

#### EfficientNetB3:

- The **EfficientNetB3** model was initialized with pre-trained ImageNet weights and all the layers were fine-tuned. Training the model with an **Adam optimizer with learning rate of 0.001** for **5 epochs** yielded an **Accuracy of 86.72%**

| Model       | Accuracy    | 
| :---        |    :----:   |  
| Baseline CNN    | 90%      |
| Mobilenetv2     | 99%      | 
| InceptionV2     | 88%      |
