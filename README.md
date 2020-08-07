# mask_rcnn_clone

Mask-RCNN

Reference1
https://github.com/matterport/Mask_RCNN

Reference2
https://github.com/kairess/Mask_RCNN

# Dependancies

- python
- numpy
- keras
- tensorflow
- opencv
- scikit-image(skimage)
- matplotlib

- imgaug

* Install imgaug
  pip3 install imgaug
  https://github.com/aleju/imgaug

- pycocotools

* Install Python COCO from github
  https://github.com/waleedka/coco

  1. Pre-requisite : cython
     pip3 install Cython

  2. pycocotools
     pip3 install pycocotools

# tf1 --> tf2 upgrade

- Reference
  https://www.tensorflow.org/guide/upgrade

- Command
  tf_upgrade_v2 --infile model.py --outfile model_tf2_upgraded.py
