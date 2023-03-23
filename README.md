# ID Card Detection using YOLO v5

This repository contains code for training and using a YOLO v5 model to detect ID cards in images.

## Dataset

The dataset consists of images of various types of ID cards, along with corresponding bounding box annotations. The dataset can be downloaded from [insert dataset source].

## Model

The YOLO v5 model is a state-of-the-art object detection model that is both fast and accurate. The model is trained on the ID card dataset to detect ID cards in images. The implementation of the YOLO v5 model is in the `yolo.py` file.

## Training

To train the YOLO v5 model, first, download the ID card dataset and extract it to the `data/` directory. Then, run the following command:

python train.py --data data/id_card.yaml --cfg models/yolov5s.yaml --weights '' --batch-size 16
