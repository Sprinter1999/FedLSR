# FedLSR

This repository is the official **Pytorch** implementation DEMO of FedLSR framework in the [paper](https://arxiv.org/abs/2208.12807):

Towards **Fed**erated Learning against Noisy Labels via **L**ocal **S**elf-**R**egularization (CIKM 2022 full paper track)



----------------------------
## Main Baselines:
- FedAvg [[paper](http://proceedings.mlr.press/v54/mcmahan17a?ref=https://githubhelp.com)]
- Symmetric Cross Entropy [[paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Wang_Symmetric_Cross_Entropy_for_Robust_Learning_With_Noisy_Labels_ICCV_2019_paper.html)] [[code](https://github.com/YisenWang/symmetric_cross_entropy_for_noisy_labels)]
- Co-teaching [[paper](https://proceedings.neurips.cc/paper/2018/hash/a19744e268754fb0148b017647355b7b-Abstract.html)] [[code](https://github.com/bhanML/Co-teaching)]
- Robust Federated Learning [[paper](https://ieeexplore.ieee.org/abstract/document/9713942)] [[code](https://github.com/jangsoohyuk/Robust-Federated-Learning-with-Noisy-Labels)]

--------------------------
## Requirements:
- Python:  3.8
- Pytorch:  1.7.1
- torchvision:  0.8.2
- Other dependencies

-------
## Special Thanks
 - Girum gives some valuable comments in the Github Issue part, and I just clarify some missed points of this paper. Please visit there for more information.
-------

## Citing this work:
```bibtex
@inproceedings{Jiang22,
    title = "Towards Federated Learning against Noisy Labels via Local Self-Regularization",
    author = "Xuefeng Jiang, Sheng Sun, Yuwei Wang, Min Liu",
    booktitle = "Proceedings of the 31st ACM International Conference on Information and Knowledge Management (CIKM ’22), October 17–21, 2022, Atlanta, GA, USA",
    month = oct,
    year = "2022",
    publisher = "Association for Computing Machinery (ACM)",
    pages = "12 pages",
    doi = "10.1145/3511808.3557110"
}
```
