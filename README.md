# real-time-objective-detection-
A report of the project done as part of the Yonsei-Roboin project for the 2nd semester, 2022
(https://arxiv.org/abs/2303.02735)

An official implementation of “Scalable Object Detection on Embedded Devices Using Weight Pruning and Singular Value Decomposition”



This paper presents a method for optimizing object detection models by combining weight pruning and singular value decomposition (SVD). The proposed method was evaluated on a custom dataset of street work images obtained from this https URL (https://universe.roboflow.com/roboflow-100/street-work). The dataset consists of 611 training images, 175 validation images, and 87 test images with 7 classes. We compared the performance of the optimized models with the original unoptimized model in terms of frame rate, mean average precision (mAP@50), and weight size. The results show that the weight pruning + SVD model achieved a 0.724 mAP@50 with a frame rate of 1.48 FPS and a weight size of 12.1 MB, outperforming the original model (0.717 mAP@50, 1.50 FPS, and 12.3 MB). Precision-recall curves were also plotted for all models. Our work demonstrates that the proposed method can effectively optimize object detection models while balancing accuracy, speed, and model size.
