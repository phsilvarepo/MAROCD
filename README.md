## Maritime Obtacle Detection and Classifiacation Dataset (MAROCD)

# Overview
This repository contains the MAROCD dataset for obstacle detection and classification in maritime environments. The dataset is designed to provide the necessary data for training a CNN. The labels of this dataset are in the YOLO annotation format.

# Data
This dataset comprises 8636 annotated images. To assemble this dataset, other publicly available datasets were used, specifically the SMD and MID datasets, along with the development of a novel TEJO dataset. The distribution of the images in the dataset per source is available in the following images. As for the classes, this dataset segregates maritime obstacles into 8 classes: boat, vessel, ferry, kayak, buoy, sailboat, and other. In total, there are 57995 class instances, and the class distribution is shown in the following images.

![alt text]([http://url/to/img.png](https://github.com/phsilvarepo/MAROCD/blob/main/Number%20of%20Instances%20per%20Class.png))

# Citation
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

# License
This dataset is released under the [license type, e.g., MIT License]. See the LICENSE file for more details.
