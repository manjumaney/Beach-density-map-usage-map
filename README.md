# Beach Density Map (Smart Beach Project - Stage 4)

## Overview

This project is part of the Bruce County Smart Beach initiative, focused on monitoring and estimating crowd density at Station Beach, Kincardine.

This repository represents **Stage 4: System Implementation**, where object detection models were applied to detect and count people and generate crowd density insights.

## Project Stage

This work corresponds to:

**Stage 4 – System Implementation**

At this stage:
- Object detection models were implemented and tested
- Real-world beach data was processed
- Crowd density estimation logic was developed
- Model outputs were validated and compared

## Problem

Manual monitoring of beach crowds is:
- Inaccurate
- Time-consuming
- Not scalable

This project provides an automated approach using computer vision to estimate crowd density.

## Features

- People detection using:
  - YOLOv8
  - Faster R-CNN
  - Detectron2
- Image preprocessing (cropping, filtering)
- Bounding box detection and counting
- CSV-based data analysis
- Crowd density estimation

## Tech Stack

- Python
- OpenCV
- PyTorch
- Detectron2
- NumPy / Pandas

## How it Works

1. Input beach images are collected
2. Images are preprocessed (cropping relevant regions)
3. Detection models identify people
4. Bounding boxes are generated
5. Counts are extracted and stored
6. Data is analyzed for density insights


## Key Implementation Details

- Faster R-CNN used for higher detection accuracy
- Detectron2 used for advanced detection and refinement
- Cropping strategy improved detection of distant individuals
- Noise reduction and filtering applied to improve results

## Project Structure

```

project/
│
├── data/              # Input images
├── processed/         # Cropped images
├── outputs/           # Detection results
├── scripts/           # Model and processing scripts
├── results/           # CSV outputs
└── README.md

````


## Usage

### Install dependencies

```bash
pip install -r requirements.txt
````

### Run detection

```bash
python main.py
```


## Applications

* Beach safety monitoring
* Crowd management
* Smart city systems
* Public event monitoring


## Note

This repository focuses on the **implementation phase** of the Smart Beach project. Other stages include planning, analysis, and system design.


## Author

- Manjumaney C M
- Vaibhavkumar Bhupendrabhai Vaghela
- Jaganlal Manilal
- Minnu Varghese

