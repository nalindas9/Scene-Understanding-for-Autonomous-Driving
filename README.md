# Scene Understanding for Autonomous Driving

## Description and Figures
Scene understanding is a vital aspect of safe and effective autonomous driving. And with the increase of high-quality datasets in recent years, the models have sufficient data to train on. However, the underlying models are important factors in determining the overall performance of the autonomous vehicle. In this paper, we propose a new model pipeline for tackling two main aspects of scene understanding, driveable lane prediction and object detection. We also provide a detailed analysis of our design choices of DeepLabv3+ used for our driveable lane prediction to cater to the problem of driveable area prediction for scene understanding. Our experimental results on BDD100K driveable area dataset show fwIoU 90.3% which is higher than other baseline segmentation models. For object detection, the pre-trained YOLOv4 shows quite stable performance with accurately localized bounding boxes for an input image. The flexibility of our pipeline leaves room for improvement.

#### Link to [Paper](https://www.researchgate.net/publication/372189733_Scene_Understanding_for_Autonomous_Driving)
