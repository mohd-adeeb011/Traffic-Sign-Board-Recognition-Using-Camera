# Traffic-Sign-Recognition-Using-YOLO

This repository contains a model and training notebook for traffic sign recognition. For inference, you’ll need to clone the YOLOv5 repository by Ultralytics, and replace the detect.py file with the one in this repository.

## How to run
Open your IDE or shell in the directory then write python detect.py --weights best_93.pt --source 0
Source 0 is to take input from the webcam.

## Dataset
The dataset used for training is [German Traffic Sign Recognition Benchmark (GTSRB)](https://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset) containing 43 classes of traffic signs. The training set contains 39209 labeled images and the test set contains 12630 unlabelled images.

![image](https://user-images.githubusercontent.com/35000278/116809754-50276780-ab5d-11eb-87fa-1f513be1f876.png)

## Model

Using and YOLOv5 for training and achieved >93% mAP on the dataset.

Download the [model](https://mega.nz/file/rV4HDQ5b#UfgDAMlVHvfzSr7PquE8HWx_6jhRmDUGBS-qyfIn_oE)
