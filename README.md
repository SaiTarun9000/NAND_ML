# Threshold Voltage Prediction Models for Advanced Flash Memory Devices

This repository contains machine learning models designed to predict initial and program threshold voltages in various advanced non-volatile memory technologies. The models utilize either synthetic data or TCAD-extracted simulation data, offering insight into device behavior across different architectures.

---

## Overview

### 3D_NAND

Models to predict:
- **Initial Threshold Voltage**
- **Program Threshold Voltage**

**Data Source**: Synthetic data generated within the notebooks, mimicking realistic distributions observed in 3D NAND flash memory.

---

### SONOS

Models to predict:
- **Initial Threshold Voltage**
- **Program Threshold Voltage**

**Data Source**: Realistic data extracted from **Sentaurus TCAD** simulations. Input files (Excel) contain device-level parameters and threshold voltage values.

---

### NAND_Polygrain

Model to predict:
- **Program Threshold Voltage** considering **grain boundary effects** in polycrystalline silicon.

**Data Source**: TCAD simulations exploring grain structure influence on threshold voltage. Input data available as Excel files.

---

## Technologies Used

- Python (NumPy, pandas, scikit-learn, TensorFlow)
- Jupyter Notebooks
- Sentaurus TCAD (for simulation data in SONOS and NAND_Polygrain)

---

## Goals

- Understand and predict device threshold voltage variation using ML.
- Explore physical effects (like polygrain variation) on memory performance.

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/threshold-voltage-prediction.git
