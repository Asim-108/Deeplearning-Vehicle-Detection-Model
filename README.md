# Deeplearning Vehicle Detection Model
 APS360 deeplearning final project for roadside vehicle detection. This model takes pictures and videos as inputs and creates both a bounding box around the objects, and creates a segmentation for them.

The model utilizes transfer learning by starting with pretrained weights from YOLOv8, and part of the coco128 image dataset for training.

Hyperparameters for the model were fine tuned through a grid search by iterating through different hyperparameters to find the best dimensionality that minimizes trainging, validation, and testing loss.

Training weights were not included in repo due to the size of them
