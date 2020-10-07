# Food9K: Detecting and Localizing Food in Social Media Images Using YOLOv3
An in-the-wild dataset of ~9K food images labeled for food detection is collected in this work. A YOLOv3 model is trained on this dataset with 63.3% F1-score that is available for download. Please refer to the dissertation paper and presentation slides for more information about the Food9K dataset and the trained model.

## Food9K Dataset
There are total 9287 images over 35 food categories in the Food9K dataset. The number of images per category is depicted in Figure 1.

<img style="display:block; margin:auto;" alt="Food9K categories" src="https://imgur.com/1kcaTwN.png" width="400" height="300"></img>

Figure 1. Food categories in Food9K dataset.

## YOLOv3 Model
You can download the pre-trained YOLOv3 model in .pt format [here](https://drive.google.com/file/d/1rBUsXy-sAm3tV8OKpV1c8h0mZ3muiQc-/view?usp=sharing). Figure 2 shows an example of a bounding box drawn by this model on unseen data.

<img style="display:block; margin:auto;" alt="Output example" src="https://imgur.com/ABbUc1D.png =250x250" width="400" height="300"></img>

Figure 2. Output example of the YOLOv3 model trained on Food9K dataset.
