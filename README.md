## SIFA
[**Synergistic Image and Feature Adaptation:<br/> Towards Cross-Modality Domain Adaptation for Medical Image Segmentation**](https://arxiv.org/abs/1901.08211)
AAAI Conference on Artificial Intelligence, 2019 (oral)
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

## Note
* The repository is being updated
* Contact: Cheng Chen (chencheng236@gmail.com)
