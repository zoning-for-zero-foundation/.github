# Climate Proxy 2

## Introduction

This document describes Climate Proxy 2 (CX2) and its role in climate analysis.

## Description

CX2 represents a complementary climate indicator that provides additional insights when used with CX1.

### CX2 Characteristics

- **Type**: Secondary climate indicator
- **Time Scale**: Medium to long-term data
- **Geographic Coverage**: Regional to global
- **Resolution**: Variable temporal resolution

## Data Analysis

The integrated analysis combining CX1 and CX2:

$$
C(t) = w_1 \cdot CX_1(t) + w_2 \cdot CX_2(t)
$$

Where:
- $C(t)$ is the combined climate signal
- $w_1$ and $w_2$ are weighting factors
- $w_1 + w_2 = 1$

### Uncertainty Estimation

The uncertainty in measurements is calculated as:

$$
\Delta C = \sqrt{(w_1 \cdot \Delta CX_1)^2 + (w_2 \cdot \Delta CX_2)^2}
$$

## Integration with CX1

CX2 complements CX1 by providing:

1. Cross-validation of climate signals
2. Enhanced spatial coverage
3. Improved temporal resolution
4. Reduced uncertainty in reconstructions

## Future Work

Ongoing research will expand the CX2 dataset and improve calibration methods.
