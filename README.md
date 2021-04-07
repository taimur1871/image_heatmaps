# Using Activations of Pretrained Network to Create Image Heat Maps

This workbook explores the idea of generting heat maps from a pretrained model to create heat maps that allow for rough detection of object in an image.
An example of dog detection using this is given below.

![Original](https://github.com/taimur1871/image_heatmaps/blob/main/dog_images/original.png)

![heatmap](https://github.com/taimur1871/image_heatmaps/blob/main/dog_images/heatmap1.png)

## Enironment
* python 3.6
* tensorflow 2.3
* matplotlib 3.3.3
* PIL 8.0.1
* numpy 1.19
* cv2 4.4.0.46

## Extension of Application

The idea can be taken much further and used to generate bounding boxes. This was done by making a threshold map from heatmaps and then finding coordinates of the object of interest. Please refer to notebook 3 for some examples.
![Threshold_heat_map](https://github.com/taimur1871/image_heatmaps/blob/main/dog_images/dog_threshold.png)

This resulted in the following bounding box
![dog_bbox](https://github.com/taimur1871/image_heatmaps/blob/main/dog_images/dog_pred.png)

The examples below are some of the tests carried out on other animals.

![Ferret](https://github.com/taimur1871/image_heatmaps/blob/main/animal_images/ferret.png)
![Ferret_pred](https://github.com/taimur1871/image_heatmaps/blob/main/animal_images/ferret_pred.png)

![Raccoon](https://github.com/taimur1871/image_heatmaps/blob/main/animal_images/raccoon.png)
![Raccoon_pred](https://github.com/taimur1871/image_heatmaps/blob/main/animal_images/raccoon_pred.png)

![Rabbit](https://github.com/taimur1871/image_heatmaps/blob/main/animal_images/rabbit.png)
![Rabbit_pred](https://github.com/taimur1871/image_heatmaps/blob/main/animal_images/rabbit_pred.png)

![Mouse](https://github.com/taimur1871/image_heatmaps/blob/main/animal_images/mouse.png)
![Mouse_pred](https://github.com/taimur1871/image_heatmaps/blob/main/animal_images/mouse_pred.png)
