# Deeplearning Vehicle Detection Model
 APS360 deeplearning final project for roadside vehicle detection. This model takes pictures and videos as inputs and creates both a bounding box around the objects, and creates a segmentation for them.

The model utilizes transfer learning by starting with pretrained weights from YOLOv8, and coco128 image dataset for part of the training data.

Hyperparameters for the model were fine tuned through a grid search by iterating through different hyperparameters to find the best dimensionality that minimizes training, validation, and testing loss.

Training weights were not uploaded to the repo due to the size of them

Google Drive link to video demonstration: https://drive.google.com/file/d/1gqKJ8fcDn-cDWdwzzkSHdGKBZGwVA0h1/view?usp=sharing

Google Drive link to trained weights: https://drive.google.com/drive/folders/1hqkA7Aw6o8EPqcmbCTAelbXXnOOuYYh6?usp=sharing
