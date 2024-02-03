# Maritime Obtacle Detection and Classification Dataset (MAROCD)

## Overview
This repository contains the MAROCD dataset for obstacle detection and classification in maritime environments. The dataset is designed to provide the necessary data to achieve a robust CNN-based obstacle detector for maritime environments. The labels in this dataset are in the YOLO annotation format.

![Dataset Overview](https://github.com/phsilvarepo/MAROCD/blob/main/dataset.png)

## Data
To assemble this dataset, other publicly available datasets were used, specifically the SMD and MID datasets, along with the development of the novel TEJO dataset. In result, this dataset is comprised with 8636 annotated images. The distribution of the images in the dataset per source is available in the following images. As for the classes, this dataset segregates maritime obstacles into 8 classes: Boat, Vessel, Ferry, Kayak, Buoy, Sailboat, and Other. In total, there are 57995 class instances, and the class distribution is shown in the following images.

![Dataset Distribution](https://github.com/phsilvarepo/MAROCD/blob/main/Dataset%20Distribution.jpg)
![Number of Instances per Class](https://github.com/phsilvarepo/MAROCD/blob/main/Number%20of%20Instances%20per%20Class.jpg)

This dataset is available in the following link: https://drive.google.com/file/d/1FqlDkOoW81htLfDT9u1kaeAcUTqwXt5J/view?usp=drive_link

## Citation
If you use this dataset in your research or project, please cite it as follows:

```
@misc{Silva_MAROCD_2024,
  author = {P. Silva},
  doi = {10.5281/zenodo.10612077},
  month = {2},
  title = {{Maritime Obstacle Classification and Detection}},
  url = {[https://github.com/phsilvarepo/MAROCD]},
  version = {1.0},
  year = {2024}
}

@misc{prasad2016video,
  title={Video Processing from Electro-optical Sensors for Object Detection and Tracking in Maritime Environment: A Survey}, 
  author={D. K. Prasad and D. Rajan and L. Rachmawati and E. Rajabaly and C. Quek},
  year={2016},
  eprint={1611.05842},
  archivePrefix={arXiv},
  primaryClass={cs.CV}
}

@article{liu2021efficient,
  title={Efficient obstacle detection based on prior estimation network and spatially constrained mixture model for unmanned surface vehicles},
  author={Liu, Jingyi and Li, Hengyu and Luo, Jun and Xie, Shaorong and Sun, Yu},
  journal={Journal of Field Robotics},
  volume={38},
  number={2},
  pages={212--228},
  year={2021},
  publisher={Wiley Online Library}
}
```

## License
This dataset is available for research purposes but not for comercial use.
