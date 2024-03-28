# FedLSR

This repository is the official **Pytorch** implementation DEMO of FedLSR framework in this [paper](https://dl.acm.org/doi/abs/10.1145/3511808.3557475):

Towards **Fed**erated Learning against Noisy Labels via **L**ocal **S**elf-**R**egularization (CIKM 2022 full paper track)

The slides for the oral presentation link is [here](https://github.com/Sprinter1999/FedLSR/blob/main/paper/%5BCIKM%E2%80%9922%5D%20Towards%20Federated%20Learning%20against%20Noisy%20Labels%20via%20Local%20Self-Regularization.pdf).

**Note**: For researchers who are interested to adopt this as a baseline, please **take care of the difference between FedLSR and FedLSR+** (which is given in the discussion section). The key motivation to append an entropy regularization term (to devise FedLSR+) is to further make the model more robust to extreme noisy labels. For experiments on clothing1M, it is suggested to raise the learning rate to 0.1 for FedLSR's implementation.


----------------------------
## Main Baselines
- FedAvg [[paper](http://proceedings.mlr.press/v54/mcmahan17a?ref=https://githubhelp.com)]
- Symmetric Cross Entropy [[paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Wang_Symmetric_Cross_Entropy_for_Robust_Learning_With_Noisy_Labels_ICCV_2019_paper.html)] [[code](https://github.com/YisenWang/symmetric_cross_entropy_for_noisy_labels)]
- Co-teaching [[paper](https://proceedings.neurips.cc/paper/2018/hash/a19744e268754fb0148b017647355b7b-Abstract.html)] [[code](https://github.com/bhanML/Co-teaching)]
- Robust Federated Learning [[paper](https://ieeexplore.ieee.org/abstract/document/9713942)] [[code](https://github.com/jangsoohyuk/Robust-Federated-Learning-with-Noisy-Labels)]

--------------------------
## Requirements
- Python:  3.8
- Pytorch:  1.7.1
- torchvision:  0.8.2
- Other dependencies

-------
## Special Thanks
 - Girum & IAMjmj give some valuable comments in the Github Issue part, and I just clarify some missed points of this paper. Please visit there for more information.
-------

## Citing this work
```bibtex
 @inproceedings{jiang2022towards,
  title={Towards federated learning against noisy labels via local self-regularization},
  author={Jiang, Xuefeng and Sun, Sheng and Wang, Yuwei and Liu, Min},
  booktitle={Proceedings of the 31st ACM International Conference on Information \& Knowledge Management},
  pages={862--873},
  year={2022}
}
```
