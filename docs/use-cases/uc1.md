# UC1 — Improved Brain-Inspired Perception in Autonomous Robots (SAR)

**Objective.** Determine, in real time, safe stepping positions for quadrupedal robots operating on uneven disaster terrain.

## Context & Setup
- **Robots & Arena:** Unitree A1/Aliengo; CAR Robotics Arena with Optitrack motion capture.  
- **Sensing:** RGB-D (Intel RealSense D435), fisheye T265, IMU; optional thermal (Optris PI 640), multispectral (MicaSense), 2D LiDAR (RPLIDAR), BNO055 IMU.  
- **Compute:** Replace Jetson Nano/Xavier with modular brain-like FPGA and custom VLSI designs.

## BLNN approach
- Fast, local learning and sparse representations for event-driven control; online adaptation to terrain changes; low-precision viability.

## Data & Privacy (pipeline)
- DOS for feature selection, augmentation/synthetic data and automatic labelling. Privacy via anonymisation/HE-ready paths.

## Evaluation targets (examples)
- **+10%** effective speed; **+20%** failure-rate reduction (falls/steps); **+15%** dataset reduction; **+10%** energy reduction.  
- Technical and non-technical criteria include latency, energy, robustness, scalability, XAI clarity, usability, mission management and compliance.
