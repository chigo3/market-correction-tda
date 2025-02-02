# market-correction-tda

# Stocks Correction Detection with TDA

This project was created during a hackathon to detect “bubble corrections” in stocks (specifically Apple & Nvidia) using:
- **Financial Metrics** (PE, PB, volatility, etc.)
- **Topological Data Analysis (TDA)**, features (Betti curves)
- **ML Classifier models**, compares the predictive skill of tda and traditional financial forecasting

## Overview

We define a correction as:
- A local peak with at least a 10% drop but less than 20% (otherwise it's considered a crash).
- We label each day as part of a correction/crash based on rolling local maxima.
