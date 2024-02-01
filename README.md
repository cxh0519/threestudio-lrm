# threestudio-lrm
The threestudio-lrm is an extension for threestudio, integrating the Large Reconstruction Model (LRM) for advanced 3D reconstruction tasks. This model is based on the framework detailed at [https://yiconghong.me/LRM/](https://yiconghong.me/LRM/). We have adapted the open-source implementation from [OpenLRM](https://github.com/3DTopia/OpenLRM). Currently, it is only used for initialization of [threestudio-gaussiandreamer](https://github.com/cxh0519/threestudio-gaussiandreamer.git).

## Installation
```
cd custom
git clone https://github.com/cxh0519/threestudio-lrm
cd threestudio-lrm
pip install -r requirements.txt
```

## 🚀Quick Start
See [threestudio-gaussiandreamer](https://github.com/cxh0519/threestudio-gaussiandreamer.git).

## 📢Discussion
**Difference with original** [threestudio-lrm](https://github.com/Adamdad/threestudio-lrm)

* Using lrm+MVDream initailzation instead of lrm+SDXL. Compared to SDXL, MVDream generates more appropriate front/side view images for given text prompt.

## 📌Citation
If you use threestudio-lrm in your research, please cite the following paper:
```
@article{hong2023lrm,
  title={Lrm: Large reconstruction model for single image to 3d},
  author={Hong, Yicong and Zhang, Kai and Gu, Jiuxiang and Bi, Sai and Zhou, Yang and Liu, Difan and Liu, Feng and Sunkavalli, Kalyan and Bui, Trung and Tan, Hao},
  journal={arXiv preprint arXiv:2311.04400},
  year={2023}
}
```
