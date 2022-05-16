# HPML-Project

We want to analyze various state-of-the-art object detection models for the best performance on a given dataset. We want to find out which one has the lowest inference time and the lowest time taken for fine-tuning each model while mainting a high accuracy. Further, we want to plot a graph which would be a plot between performance with the corresponding model where performance is a weighted metric between the time taken and accuracy.


# Code Structure
There are 2 colab notebooks. One has inferences and fine-tuning for Fast-RCNN and RetinaNet using detectron2 librrary. The other has inferences and fine-tuning for DETR and YOLO using huggingface.

# Results

| MODEL          | Inference Time (ns) | Fine-tuning time(s / it) | Parameter Count | mAP  |
| -------------- | ------------------- | ------------------------ | --------------- | ---- |
| yolo-small     | 9.45                | 2.41                     | 30684768        | 36.1 |
| RetinaNet      | 5.145837088         | 1.5744                   | 37915572        | 52.1 |
| detr-resnet-50 | 10.77673547         | 3.971                    | 41309536        | 52.3 |
| faster-rcnn    | 8.278814845         | 2.5273                   | 104,784,480     | 43.9 |
| yolo-base      | 27.61568451         | 4.5                      | 127798368       | 45.5 |
