# AEWD: Aerial Endangered Wildlife Dataset
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
> **Paper Title: [AEWD: A Weakly Observable Object Detection Benchmark for UAV-Based Endangered Wildlife Monitoring**]

# Overview
The Aerial Endangered Wildlife Dataset (AEWD) is a specialized UAV-based dataset designed to tackle the technical challenges of monitoring endangered species in complex, cluttered forest canopies. Unlike traditional benchmarks that mainly focus on charismatic mammals in open savannas, AEWD includes 7,483 high-resolution images with 27,194 annotated instances of four flagship species: the Amur Tiger, Giant Panda, Golden Snub-nosed Monkey, and Sichuan Takin. The dataset carefully assesses detection difficulty across five key attributes, including bounding box size, instance scale, target density, vegetation coverage, and occlusion degree, reflecting the inherent complexities of real-world ecological environments.
# Note on Video Resources
To support motion-cue research and pose estimation, we provide the original aerial video sequences. Due to the large file size exceeding GitHub quotas, the video sequences are hosted on a high-capacity storage platform. Download Link for Full Video Sequences：https://pan.quark.cn/s/bb1922245602?pwd=UiyY
# Dataset Structure
The dataset is organized as follows:
```text
AEWD/
├── images/             # Single-frame extracted images
│   ├── Amur Tiger/                           # Amur Tiger Images
│   ├── Giant Panda/                          # Giant Panda Images
│   ├── Golden Snub-nosed Monkey_Section1/    # Golden Snub-nosed Monkey Images
│   ├── Golden Snub-nosed Monkey_Section2/
│   ├── Golden Snub-nosed Monkey_Section3/
│   ├── Golden Snub-nosed Monkey_Section4/
│   ├── Sichuan Takin_Section1/                # Sichuan Takin Images
│   ├── Sichuan Takin_Section2/
│   ├── Sichuan Takin_Section3/
│   ├── Sichuan Takin_Section4/
├── annotations/                               # Annotation files
├── scripts/                                   # dataset informations
└── LICENSE                                    # Creative Commons Attribution 4.0 International
