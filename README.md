# HPML-Project

We want to analyze various state-of-the-art object detection models for the best performance on a given dataset. We want to find out which one has the lowest inference time and the lowest time taken for fine-tuning each model while mainting a high accuracy. Further, we want to plot a graph which would be a plot between performance with the corresponding model where performance is a weighted metric between the time taken and accuracy.


# Code Structure
There are 2 colab notebooks. One has inferences and fine-tuning for Fast-RCNN and RetinaNet using detectron2 librrary. The other has inferences and fine-tuning for DETR and YOLO using huggingface.

# Results

| MODEL          | Inference Time (ns) | Fine-tuning time(s / it) | Parameter Count |
| -------------- | ------------------- | ------------------------ | --------------- |
| yolo-small     | 9.45                | 2.41                     | 30,684,768      |
| RetinaNet      | 5.145837088         | 1.5744                   | 37,915,572      |
| detr-resnet-50 | 10.77673547         | 3.971                    | 41,309,536      |
| faster-rcnn    | 8.278814845         | 2.5273                   | 104,784,480     |
| yolo-base      | 27.61568451         | 4.5                      | 127,798,368     |
