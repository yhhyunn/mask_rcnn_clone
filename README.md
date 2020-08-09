# mask_rcnn_clone

Mask-RCNN

Reference1 :
https://github.com/matterport/Mask_RCNN

Reference2 :
https://github.com/kairess/Mask_RCNN

# Dependancies

- python 3.7.7
- numpy 1.19.1
- keras 2.3.1
- tensorflow 2.1.0
- opencv 4.3.0(python)
- scikit-image(skimage) 0.16.2
- matplotlib 3.2.2

- imgaug

* Install imgaug :
  pip3 install imgaug
  https://github.com/aleju/imgaug

- pycocotools

* Install Python COCO from github :
  https://github.com/waleedka/coco

  1. Pre-requisite(cython) :
     pip3 install Cython

  2. pycocotools :
     pip3 install pycocotools

# tf1 --> tf2 upgrade

- Reference :
  https://www.tensorflow.org/guide/upgrade

- Command :
  tf_upgrade_v2 --infile model.py --outfile model_tf2_upgraded.py
