# Edge Harmony Attention Network for Semi-supervised Medical Image Segmentation

by Manti Lu, Yang Liu, Yunzhu Chen and Feng Yang.

## Requirements

Our experiments were conducted using PyTorch 2.1.0, CUDA 12.1, and Python 3.8.18 on NVIDIA GeForce GTX 1080 GPUs.

## Usage
We provide `code`, other modules follow [BCP](https://github.com/DeepMed-Lab-ECNU/BCP).

Data could be got at [LA](https://github.com/yulequan/UA-MT/tree/master/data) and [ACDC](https://github.com/HiLab-git/SSL4MIS/tree/master/data/ACDC).

To train a model：
```
python ./code/LA_BCP_train.py        #for LA training
python ./code/ACDC_BCP_train.py      #for ACDC training
```
To test a model：
```
python ./code/test_LA.py       #for LA testing
python ./code/test_ACDC.py     #for ACDC testing
```
## Acknowledgements
Our code is largely based on [BCP](https://github.com/DeepMed-Lab-ECNU/BCP). Thanks for these authors for their valuable work, hope our work can also contribute to related research.
