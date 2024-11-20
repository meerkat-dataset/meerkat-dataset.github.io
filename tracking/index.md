---
title: Impact of Object Detector Accuracy on Tracking-By-Detection Methods: A Case Study with Meerkats
description: An analysis of the impact of object detector performance on tracking-by-detection multi-object tracking algorithms.
---

## Abstract
Multi-object tracking (MOT) is the task of tracking multiple entities across video frames and maintaining identity labels over time. This has many applications, including in animal research and behavioural studies. Animal tracking applications have many unique challenges, such as frequent occlusions, interactions, and homogenous appearance. The most common paradigm for MOT is tracking-by-detection, which relies on powerful object detection models to detect objects and associate the detected objects between frames. These models rely on well-performing detection models; however, the impact of poor detection accuracy has not been quantified. In this study, we trained six variants of YOLOv10 on a dataset of meerkats in a zoo environment and tested four tracking-by-detection methods, BoT-SORT, DeepSORT, ByteTrack, and OC-SORT, to measure the effect of varying detection performances. Our experiments showed that detection accuracy significantly affects tracking metrics, such as identity consistency, HOTA, and MOTA, particularly in challenging scenarios involving occlusions and rapid movement. We also highlight the common detection and tracking challenges with animal datasets and compare the performances of the evaluated tracking methods. Ultimately, this study highlights the importance of optimising detection models to achieve reliable MOT performance in complex environments, contributing to more accurate animal behaviour monitoring and ecological research.

## Extended examples

In this repository, we provide a few short clips of scenarios where the four tracking algorithms did not perform well, to highlight challenges with multi-animal tracking.










## Citation
To cite this dataset please use the following reference.

```BibTeX
@misc{rogers2024recurrencevideoframesrovf,
      title={Recurrence over Video Frames (RoVF) for the Re-identification of Meerkats}, 
      author={Mitchell Rogers and Kobe Knowles and Gaël Gendron and Shahrokh Heidari and David Arturo Soriano Valdez and Mihailo Azhar and Padriac O'Leary and Simon Eyre and Michael Witbrock and Patrice Delmas},
      year={2024},
      eprint={2406.13002},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2406.13002}, 
}
```

## Acknowledgements

This project is supported by the <a href="https://www.auckland.ac.nz/en/science/our-research/research-institutes-and-centres/nao-institute/about-naoinstitute.html">Natural, Artificial, and Organisation Intelligence Institute (NAOInstitute)</a>.

We would like to thank <a href="https://wellingtonzoo.com/">Wellington Zoo</a> for their support and expertise provided throughout the project.