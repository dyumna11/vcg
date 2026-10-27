# Recovery of Compressed VCG Signals via SVT-Based Matrix Completion

## Overview
This research project explores the compression and reconstruction of Vectorcardiogram (VCG) signals using low-rank matrix completion techniques. It aims to reduce signal storage requirements while preserving important cardiac signal characteristics during reconstruction.

## Methodology
- **Signal Preprocessing:** R-peak detection, heartbeat segmentation, and temporal normalization using cubic spline interpolation.
- **Low-Rank Representation:** Singular Value Decomposition (SVD) to estimate the low-rank structure of the signal.
- **Signal Reconstruction:** Iterative Singular Value Thresholding (SVT) to recover missing signal information through matrix completion.
- **Evaluation:** Quantitative assessment of compression and reconstruction quality using standard signal-quality metrics.

## Dataset
Evaluated on 10 VCG records from the **PTB Diagnostic Database**.

## Results
- **Average Compression Ratio:** 40.09
- **Average Percentage Root-mean-square Difference (PRD):** 3.22%
- **Average Signal-to-Noise Ratio (SNR):** 30.29 dB
- **Average Mean Squared Error (MSE):** 0.00007
- **Average Peak Signal-to-Noise Ratio (PSNR):** 44.42 dB
- **Average Similarity:** 0.9985

## Technologies
Python · NumPy · SciPy · Pandas · Matplotlib · WFDB

## Key Contributions
- Applied low-rank matrix recovery techniques to biomedical signal compression.

