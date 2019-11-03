## SIFA
[**Synergistic Image and Feature Adaptation: Towards Cross-Modality Domain Adaptation for Medical Image Segmentation**](https://arxiv.org/abs/1901.08211) AAAI, 2019 (oral)
<br/>
<br/>
![](figure/framework.png)

## Installation
* Install TensorFlow 1.4 and CUDA 8.0
* Clone this repo
```
git clone https://github.com/cchen-cc/SIFA
cd SIFA
```

## Data Preparation
* Raw data needs to be written into `tfrecord` format to be decoded by `./data_loader.py`.
* Put `tfrecord` data of two domains into corresponding folders under `./data` accordingly.
* Run `./create_datalist.py` to generate the datalists containing the path of each data.

## Train
* Modify paramter values in `./config_param.json`
* Run `./main.py` to start the training process


If you make use of the code, please cite the paper in resulting publications.
```
@article{chen2019synergistic,
  title={Synergistic image and feature adaptation: Towards cross-modality domain adaptation for medical image segmentation},
  author={Chen, Cheng and Dou, Qi and Chen, Hao and Qin, Jing and Heng, Pheng-Ann},
  journal={arXiv preprint arXiv:1901.08211},
  year={2019}
}
```
