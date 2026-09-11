# Time Series Analysis & Statistical Diagnostics

This repository contains four technical reports demonstrating applied statistical analysis, anomaly detection, and time-series forecasting across mechanical, synthetic, and real-world datasets.

### 📂 Repository Contents

*   **Bearing Accelerometry Analysis:** Applied Cumulative Sum (CUSUM) anomaly detection to NASA's bearing dataset, successfully predicting catastrophic mechanical failure 3 days in advance[cite: 3]. Evaluated stochastic drift using Augmented Dickey-Fuller (ADF) and KPSS tests, achieving signal stationarity via first-order differencing and logarithmic transformations[cite: 3].
*   **Multivariate Synthetic Data Validation:** Executed dynamic factor decomposition via Principal Component Analysis (PCA) and lag diagnostics (CCF/PACF) to mathematically validate the underlying LMC-Synth generation framework utilized by the TimePFN architecture[cite: 1].
*   **Theme Park Wait Time Decomposition:** Extracted complex daily trends and seasonal attendance cycles from high-frequency observational data utilizing Seasonal and Trend decomposition using Loess (STL) and STAHL[cite: 2].
*   **UFO Sightings Forecasting:** Benchmarked classical SARIMA forecasting models against IBM's FlowState architecture, specifically evaluating the efficacy of orthogonal Legendre polynomials and Fourier series within state space models[cite: 4].

### 🛠️ Key Methodologies

*   **Anomaly Detection:** Cumulative Sum (CUSUM), Statistical Thresholding[cite: 3].
*   **Diagnostics & Stationarity:** Augmented Dickey-Fuller (ADF), KPSS, Cross-Correlation (CCF), PACF, Friedman Test[cite: 1, 3].
*   **Decomposition:** Principal Component Analysis (PCA), STL, STAHL[cite: 1, 2].
*   **Forecasting:** SARIMA, FlowState (SSM)[cite: 4].
