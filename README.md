# Instance-Segmentation-Of-Teeth-using-Detecton-2
Instance Segmentation Of Teeth using Detecton 2

Detectron 2


Detectron2 is a ground-up rewrite of Detectron that started with maskrcnn-benchmark. The platform is now implemented in PyTorch. With a new, more modular design, Detectron2 is flexible and extensible, and able to provide fast training on single or multiple GPU servers. Detectron2 includes high-quality implementations of state-of-the-art object detection algorithms, including DensePose, panoptic feature pyramid networks, and numerous variants of the pioneering Mask R-CNNmodel family also developed by FAIR. Its extensible design makes it easy to implement cutting-edge research projects without having to fork the entire codebase.


1)Used custom dataset of laptops and labelled them and drew mask on them using labelling software

2)converted them to json and split them in train and test dataset

3)Converted them to COCO dataset format using script to convert them

4)Using google colab registered them with COCO dataset

5)Using Detectron 2(open source library )performed transfer learning to train model on custom dataset for mask of teeth

6)Using test dataset we tested our model to draw mask and it performed very well for mask on teeth


![image](https://github.com/vibhavjoshi123/Instance-Segmentation-Of-Teeth-using-Detecton-2/assets/37294597/2f23a7a4-e758-4295-8642-0c5e0d6e1ecc)

![image](https://github.com/vibhavjoshi123/Instance-Segmentation-Of-Teeth-using-Detecton-2/assets/37294597/6180caf9-25f2-428e-ab40-f664c247900d)

![image](https://github.com/vibhavjoshi123/Instance-Segmentation-Of-Teeth-using-Detecton-2/assets/37294597/dda440a9-fd9b-4149-9ce6-0ad6bc85d6bc)


