# SIFANet
> [A Semantic Information Feature Aggregation Network Based On Remote Sensing Images]

## Abstract

Object detection is a crucial but challenging task in remote sensing images. Thanks to the emergence of convolution neural networks (CNNs ), object detection has made significant progress. However, there are still two significant issues that must be addressed: 1) Since small targets are distributed at any angle, the features extracted by traditional convolution are incomplete and 2) the objects in remote sensing images are small and dense, resulting in missed detections and false detections during the detection process. In this letter, we innovatively propose to obtain more semantic information to help remote sensing detection tasks solve these two problems. To achieve this goal, we design two novel modules: an adaptive feature extraction module (AFEM) and a tridirectional feature fusion module (TRFFM) to improve detection capabilities in small target-dense scenarios. More specifically, AFEM is suitable for feature extraction of rotating targets and can adaptively fit the receptive field of rotating targets. TRFFM establishes multiple paths between different layers of the feature pyramid to aggregate shallow detail information and deep semantic information. Extensive experiments on two challenging remote datasets, optical remote sensing images (DIOR) and VisDrone2019, experimental results in terms of accuracy and adaptivity validate the superiority of our method.

## dataset

DIOR & VisDrone2019

## Results and Models
We provide the config files and models for SIFANet: [A Semantic Information Feature Aggregation Network Based On Remote Sensing Images].


| Backbone |  Model   | Lr schd | Mem (GB) | Inf time (fps) | box AP |                  Config                   |                                                                                                                                                Download                                                                                                                                                |
| :------: | :------: | :-----: | :------: | :------------: | :----: | :---------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|   R-50   | SIFANet|   12e   |          |                |  75.4  | [config]() | [model]()  |

