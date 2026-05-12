A labeled sample IoT time-series dataset collected from a container-mounted endpoint in a container yard. Includes accelerometer, gyroscope, magnetometer, barometer, and piezoelectric signals across container handling phases such as reach stacker movement, trailer transport, and yard placement for ML/DL research.

# Container Yard IoT Motion Dataset

A labeled sample IoT time-series dataset collected from an endpoint installed on a shipping container in a container yard environment. The dataset captures multimodal sensor readings during multiple container handling and transport phases and is intended for machine learning and deep learning research, including classification, sequence modeling, and model fine-tuning.

## Overview

This repository contains a sample of sensor data gathered from an IoT endpoint mounted on a container. During data acquisition, the container underwent several operational phases in a logistics environment. These phases were labeled to support supervised learning tasks.

The recorded scenario includes:
- movement of the container using a reach stacker
- placement of the container on a trailer
- trailer transportation
- placement of the container in another yard location

The dataset includes synchronized or near-synchronized measurements from multiple onboard sensors and can be used to study movement recognition, activity classification, event detection, and multimodal sensor fusion.

## Sensors Included

The dataset includes readings from the following sensors:

- Accelerometer
- Gyroscope
- Magnetometer
- Barometer
- Piezoelectric sensor

These signals provide complementary information about vibration, motion, orientation changes, environmental pressure variation, and mechanical events.

## Labels / Classes

This sample dataset includes labeled segments for selected container handling phases. Example classes may include:

- container lifted / moved by reach stacker
- container placed on trailer
- trailer transport / trailer movement
- container placed in yard / repositioned in yard

> Note: Some labels collected in the broader project are intentionally excluded from this public repository. These excluded classes may include ship loading, unloading, and container movement aboard a vessel.

## Intended Use

This dataset is intended for:

- supervised learning
- deep learning model training
- transfer learning / fine-tuning
- time-series classification
- multimodal sensor fusion research
- logistics and smart port/container yard analytics
- event segmentation and operational state recognition

Possible model families include:

- CNN / 1D CNN
- LSTM / GRU
- CNN-LSTM hybrids
- Transformers for time series
- classical ML models with handcrafted features

## Repository Contents

Structure:
```text
.
├── data/
│   └── sample_container_yard_dataset.csv
├── docs/
│   └── label_description.md
├── LICENSE
└── README.md

