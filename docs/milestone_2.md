# Milestone 2: Implement and Test DTW Algorithm

## Overview

This milestone focused on implementing the core Dynamic Time Warping (DTW) algorithm and validating it using synthetic time series data. The goal was to produce a working DTW function, generate test inputs, and observe how DTW behaves across different scenarios.

---

## What I Built

### 1. `dtw_distance()` Function
- Implemented a basic DTW algorithm in Python.
- Computes the minimum alignment cost between two time series.
- Handles cost matrix initialization and dynamic programming logic.

### 2. Synthetic Input Generator
- Created `generate_sine_wave()` to produce smooth, periodic test data.
- Supports variations in frequency and noise level.
- Used NumPy for time steps and Gaussian noise.

### 3. Test Notebook
- Ran DTW on multiple input pairs:
  - Base sine wave vs faster/slower oscillations
  - Base sine wave vs noisy variant
- Printed DTW distances to observe similarity scores.

Notebook saved in:  
 `DTW-App/notebooks/03_dtw_core.ipynb`

---

## Sample Results

| Series Pair | DTW Distance |
|-------------|--------------|
| 1 vs 2 (faster) | *e.g., 2.0* |
| 1 vs 3 (slower) | *e.g., 1.8* |
| 1 vs 4 (noisy)  | *e.g., 3.2* |

*Note: Actual values may vary due to random noise.*

---

## Reflections

- DTW successfully handles time series with phase shifts and noise.
- Sine waves are useful for controlled testing, but future inputs should include more diverse patterns (e.g., linear trends, random walks).
- Code comments and docstrings were added to clarify logic and improve readability.

---

## Next Steps (Milestone 3 Preview)

- Visualize alignment paths and cost matrices.
- Compare DTW results across different input types.
- Begin modularizing code for app integration.

---
