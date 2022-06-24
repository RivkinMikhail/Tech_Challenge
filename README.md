# Test_Challenge

This solution is based on usage of three models [DeepForest](https://github.com/weecology/DeepForest) and [EfficientDet Pytorch](https://github.com/zylo117/Yet-Another-EfficientDet-Pytorch)

## Install ##
Create new venv and then launch :

`pip install -r requirements.txt`

## Usage ##

Download weights form this link: [link](https://github.com/zylo117/Yet-Another-Efficient-Pytorch/releases/download/1.2/efficientdet-d8.pth)

Create folder `EfficientDet/weights` and place downloaded weights there.

Then just simply launch test file.

`python3 efficientdet_test.py`

The results will be in folder `EfficientDet/test`.

![Orig](https://github.com/RivkinMikhail/Tech_Challenge/blob/main/image.jpg)

![Detections](https://github.com/RivkinMikhail/Tech_Challenge/blob/main/EfficientDet/test/img_inferred_d8_this_repo_0.jpg)
