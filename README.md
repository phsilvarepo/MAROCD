# Maritime Obtacle Detection and Classification Dataset (MAROCD)

## Overview
This repository contains the MAROCD dataset for obstacle detection and classification in maritime environments. The dataset is designed to provide the necessary data to achieve a robust CNN-based obstacle detector for maritime environments. The labels in this dataset are in the YOLO annotation format.

![Dataset Overview](https://github.com/phsilvarepo/MAROCD/blob/main/Dataset%20Distribution.jpg)

## Data
To assemble this dataset, other publicly available datasets were used, specifically the SMD and MID datasets, along with the development of the novel TEJO dataset. In result, this dataset is comprised with 8636 annotated images. The distribution of the images in the dataset per source is available in the following images. As for the classes, this dataset segregates maritime obstacles into 8 classes: Boat, Vessel, Ferry, Kayak, Buoy, Sailboat, and Other. In total, there are 57995 class instances, and the class distribution is shown in the following images.

![Dataset Distribution](https://github.com/phsilvarepo/MAROCD/blob/main/Dataset%20Distribution.jpg)
![Number of Instances per Class](https://github.com/phsilvarepo/MAROCD/blob/main/Number%20of%20Instances%20per%20Class.jpg)

This dataset is available in the following link: https://drive.google.com/file/d/1FqlDkOoW81htLfDT9u1kaeAcUTqwXt5J/view?usp=drive_link

## Citation
If you use this dataset in your research or project, please cite it as follows:

@misc{your-project-dataset,
  title={Your Project Name - Sample Dataset},
  author={Your Name},
  year={2024},
  howpublished={\url{https://github.com/your-username/your-dataset-repo}},
}

@misc{your-project-dataset,
  title={Your Project Name - Sample Dataset},
  author={Your Name},
  year={2024},
  howpublished={\url{https://github.com/your-username/your-dataset-repo}},
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

## License
This dataset is released under the [license type, e.g., MIT License].
