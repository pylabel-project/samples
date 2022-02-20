Notebooks and code samples to help you use the PyLabel Python package and the PyLabeler Jupyter-based labeling tool. 

## Annotation Format Conversion
Use PyLabel to translate bounding box annotations between different formats-for example, from coco to yolo.
- [coco2voc.ipynb](https://github.com/pylabel-project/samples/blob/main/coco2voc.ipynb) <a href="https://colab.research.google.com/github/pylabel-project/samples/blob/main/coco2voc.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
- [coco2yolov5.ipynb](https://github.com/pylabel-project/samples/blob/main/coco2yolov5.ipynb) <a href="https://colab.research.google.com/github/pylabel-project/samples/blob/main/coco2yolov5.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
- [voc2coco.ipynb](https://github.com/pylabel-project/samples/blob/main/voc2coco.ipynb) <a href="https://colab.research.google.com/github/pylabel-project/samples/blob/main/voc2coco.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
- [yolo2coco.ipynb](https://github.com/pylabel-project/samples/blob/main/yolo2coco.ipynb) <a href="https://colab.research.google.com/github/pylabel-project/samples/blob/main/yolo2coco.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
- [yolo2voc.ipynb](https://github.com/pylabel-project/samples/blob/main/yolo2voc.ipynb) <a href="https://colab.research.google.com/github/pylabel-project/samples/blob/main/yolo2voc.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
- [yolo_with_yaml_importer.ipynb](https://github.com/pylabel-project/samples/blob/main/yolo_with_yaml_importer.ipynb) <a href="https://colab.research.google.com/github/pylabel-project/samples/blob/main/yolo_with_yaml_importer.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

## PyLabeler 
PyLabeler is a Jupyter-based labeling tool that you can use to annotate images and edit bounding box annotations within a Jupyter notebook. 
- [**label_new_dataset.ipynb**](https://github.com/pylabel-project/samples/blob/main/label_new_dataset.ipynb) <a href="https://colab.research.google.com/github/pylabel-project/samples/blob/main/label_new_dataset.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a><br>This notebook is a labeling tool that can be used to annotate image datasets with bounding boxes, automatically suggest bounding boxes using an object detection model, and save the annotations in YOCO, COCO, or VOC format.
- [**yolo2pylabeler.ipynb**](https://github.com/pylabel-project/samples/blob/main/yolo2pylabeler.ipynb) <a href="https://colab.research.google.com/github/pylabel-project/samples/blob/main/yolo2pylabeler.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a><br>This notebook uses PyLabeler to edit an existing dataset of Yolo annotations and save the new annotations back to Yolo format.

## Integrations with Other Tools
PyLabel can help you use other tools that take bounding box annotations as an input or output. PyLabel stores annotations as a Pandas dataframe, which you can access directly to support your particular use case. 

- [**albumentations.ipynb**](https://github.com/pylabel-project/samples/blob/main/albumentations.ipynb) <a href="https://github.com/pylabel-project/samples/blob/main/albumentations.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a><br>If you don't have enough images to train a model well, you can use image augmenation to create more samples for training and validation. 
[Albumentations](https://albumentations.ai/) is a popular open-source library for creating additional, augmented images as well as the annotations for those images.

- [**azure_custom_vision.ipynb**](https://github.com/pylabel-project/samples/blob/main/pylabel2azure_custom_vision.ipynb) <a href="https://github.com/pylabel-project/samples/blob/main/pylabel2azure_custom_vision.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a><br>Using PyLabel you can import existing labels in COCO, YOLOv5, or VOC format and then upload the dataset to Azure Custom Vision.
