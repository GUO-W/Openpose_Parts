# Openpose_Parts
Thanks to CMU's work, this repository is based on https://github.com/CMU-Perceptual-Computing-Lab/openpose.git.
New caffemodles are added to estimate certian parts of the human body.

To build and start the demo, please look at Openpose doc.

The models already seted in this demo are models with less chanels which are smaller and faster. (Attention: the "iter_" in file names does not mean the real iteration for certain, I was just tired of changing them …)
To use the models with original structure （higher accurancy but slower）, you just need to download the models and the deploy files corresponded in the following BAIDU link, put them in /openpose/models/pose/coco and then run the testing commands with the options bellow. Do not forget to change the file names.


## Options:
--model_pose COCO_legs  only legs with 7 kp (31M)
--model_pose COCO_headshoulder head&shoulder with 8 kp (31M)
--model_pose COCO pose model with 18 kp  (2.6M)


## Download caffemodels from BAIDU:
https://pan.baidu.com/s/1sWfHk8XqhPX8a_EHJEi_pA  password:joc4


## Results
### COCO_headshoulder
<p align="center">
    <img src="openpose/examples/media-results/headshoulder.gif", width="360">
</p>

### COCO_legs
<p align="center">
    <img src="openpose/examples/media-results/legs.gif", width="360">
</p>

