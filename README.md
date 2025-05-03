# Medlytics

Welcome to **Medlytics** — a comprehensive, hands-on course and project suite for learning and applying data science, machine learning, and signal/image processing techniques, with a focus on medical and health-related data.

## Table of Contents

- [Overview](#overview)
- [Directory Structure](#directory-structure)
- [Weeks & Topics](#weeks--topics)
- [Data](#data)
- [Getting Started](#getting-started)
- [Requirements](#requirements)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

This repository contains a multi-week curriculum designed to teach core concepts in data science and machine learning through practical, notebook-based exercises. Each week focuses on a different set of topics, building from foundational skills to advanced deep learning and signal processing.

---

## Directory Structure

```
medlytics/
├── Data/                # Datasets for all weeks
├── Week1/               # Intro to Python, Pandas, ML basics
├── Week2/               # Time series, signal processing, neural networks
├── Week3/               # Image features, clustering, deep learning
├── .git/                # Git version control
├── .idea/               # IDE settings (ignore)
```

Each `WeekX` folder contains subfolders for each topic with Jupyter notebooks for tutorials and exercises.

---

## Weeks & Topics

### Week 1: Data Science Foundations
- **01_GitHub_Deepnote_Intro**: Intro to GitHub and notebook platforms
- **02_Pandas**: Data manipulation with Pandas
- **03_Matplotlib**: Data visualization
- **04_Regression**: Linear regression fundamentals
- **05_Classification_Metrics**: Evaluating classification models
- **06_Nearest_Neighbors**: KNN algorithms
- **07_SVM**: Support Vector Machines
- **08_Decision_Tree**: Decision tree classifiers
- **Challenge_Project**: Capstone project for Week 1

### Week 2: Signal Processing & Neural Networks
- **01_TimeSeries**: Time series analysis
- **02_SignalProcessing**: Signal processing basics
- **03_FourierTransforms**: Fourier analysis
- **04_SignalsML**: ML with signals
- **05_NeuralNetworks**: Neural network foundations
- **06_Convolution**: Convolution operations
- **07_1DConvNets**: 1D Convolutional Neural Networks
- **Challenge_Project**: Sleep analysis challenge

### Week 3: Image Processing & Deep Learning
- **01_ImageFeaturesAndKMeansClustering**: Image features, clustering
- **02_2DConvNets**: 2D convolutional networks
- **03_TransferLearning**: Transfer learning with deep nets

---

## Data

- All datasets are stored in the `Data/` directory, with subfolders for each week and topic.
- Some datasets may be large; ensure you have sufficient disk space.

---

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd medlytics
   ```

2. **Install dependencies:**
   - Recommended: Use [Anaconda](https://www.anaconda.com/products/distribution) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html).
   - Create and activate a new environment:
     ```bash
     conda create -n medlytics python=3.9
     conda activate medlytics
     ```
   - Install Jupyter and common packages:
     ```bash
     pip install jupyter pandas numpy matplotlib scikit-learn scipy seaborn tensorflow keras
     ```

3. **Launch Jupyter:**
   ```bash
   jupyter notebook
   ```
   - Navigate to the desired week and topic notebook.

---

## How to Use

- Each topic folder contains:
  - `*_Tutorial.ipynb`: Guided, step-by-step tutorial.
  - `*_Exercises.ipynb`: Practice problems.
- Challenge projects are located at the end of each week.
- Read the `README.md` files in each week for more details.

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements, bug fixes, or new content.

---

## License

Distributed for educational purposes. See `LICENSE` file if present.

---

*Last updated: 2025-05-03*
