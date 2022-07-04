# swin-mpii
Repo with code used in the exam of Deep Learning. Fine-Tuning Faster R-CNN with Swin as a Backbone. Based on mmdetection.

References:
  - [MPII Dataset](http://human-pose.mpi-inf.mpg.de/)
  - [SWIN](https://github.com/SwinTransformer/Swin-Transformer-Object-Detection)
  - [MMDetection](https://github.com/open-mmlab/mmdetection)
  - [Installation](https://mmdetection.readthedocs.io/en/v2.11.0/get_started.html#a-from-scratch-setup-script)
  - [MPII to COCO](https://github.com/mks0601/TF-SimpleHumanPose/blob/master/tool/mpii2coco.py)
  - [COCO Dataset Splitting](https://github.com/akarazniewicz/cocosplit)
  
 Usage:
 
 Run for training
 >python ./tools/train.py ./configs/swin/mask_rcnn_swin-t-p4-w7_fpn_1x_coco.py
 
 Run for testing
 > Testing command
 
