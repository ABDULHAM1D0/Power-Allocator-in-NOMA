# Power Allocation in NOMA (Non-Orthogonal Multiple Access)
## Overview
This project focuses on power allocation in NOMA systems to address one of their key challenges: interference between users. NOMA improves spectral efficiency by allowing multiple users to share the same frequency resources, but this comes at the cost of increased interference.
The goal of this research-based project is to reduce interference rates by learning optimal power allocation strategies using machine learning.

## Problem Statement

In NOMA systems, improper power allocation leads to high interference, degrading overall system performance. Metrics such as BER (Bit Error Rate), SINR (Signal-to-Interference-plus-Noise Ratio), ISR (Interference-to-Signal Ratio), and throughput are directly affected.
This project investigates how data-driven methods can be used to allocate power more efficiently and improve system reliability.

## Project Type
- Research prototype
- Machine learning–based optimization for wireless communication systems

## Key Features
- Data preprocessing tailored for NOMA communication parameters
- Feature engineering using communication metrics:
  - **BER** (Bit Error Rate)
  - **SINR** (Signal-to-Interference-plus-Noise Ratio)
  - **ISR** (Interference-to-Signal Ratio)
  - **Throughput**


Exploratory data analysis and visualization

Machine learning–based classification for power allocation decisions

Model evaluation and performance comparison

Technologies Used

Python

PyTorch

NumPy, Pandas, Matplotlib (for analysis and visualization)

Input & Output

Input: Communication system parameters and extracted features

Output: An optimal power allocation decision that minimizes interference while improving overall performance

How to Run

The project is implemented as a Google Colab notebook:

Open the notebook in Google Colab

Run the cells sequentially

Follow the analysis, training, and evaluation steps inside the notebook

No additional setup is required beyond standard Python ML libraries.

Future Improvements

Extend the model to handle more users and dynamic channel conditions

Compare ML-based allocation with traditional optimization methods

Explore deep reinforcement learning for adaptive power allocation

Evaluate performance under real-world noise and mobility scenarios

Notes

This project is intended as a research and learning-oriented study, demonstrating how machine learning can be applied to communication systems to solve interference-related challenges in NOMA.
