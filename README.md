# Using OpenCV DNN combined with YoloV3 and YoloV3-tiny for simple object detections tasks.

## Instructions.

You'll find all the instructions in the three different notebooks which are basically the same, the only changes occur on the detection device or type of input frames. There are three different object detections tasks I would like to highlight there, for objects detections in images, videos and webcam (cameras). This code was inspired by some coders on github and Kaggle, they allow me to start my first project of Computer Vision using OpenCV DNN and YoloV3. All the functions are stored in these notebooks and ready to work.

### YoloV3 cfg and weights.

I based this repository on the YOLOv3 algorithm : https://pjreddie.com/darknet/yolo/ . The weights and cfg files were downloaded on the official website, I used YOLOv3-320 (320x320) and YOLOv3-tiny. The weights and cfg files can be checked in the **cfg** and **models** folders.

### Dataset.

The YOLOv3-320 and YOLOv3-tiny were trained on the MSCOCO Dataset, you'll find the dataset listing names and bouding boxes with COCO format in **data** folder.

### Images and videos.

You'll be able to find images and videos for test in the folders **images** and **videos**, the code is already setup to execute directly in those directories.

## About

This code is not the most complicated and is certainly not the most detailed one but, it was the easiest one for me to start to learn about using OpenCV DNN and YOLOv3 for object detections and I think it might be useful for beginners to start there.
In the near future, I'll try to upgrade the code for custom detections and combined my findings in this : https://github.com/fredotran/traffic-sign-recognition with OpenCV DNN and YOLOv3 for traffic signs detections.

## Source 

***YOLOv3: An Incremental Improvement***, Redmon, Joseph and Farhadi, Ali, **arXiv**, 2018 : http://arxiv.org/abs/1804.02767


https://www.murtazahassan.com/
