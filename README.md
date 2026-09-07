# STIB GTFS Service Pattern Analysis

Analysis of STIB public transport service patterns using GTFS data, headway computation, time-group detection, clustering, and service regularity assessment.

## Overview

This project analyzes STIB (Brussels public transport) GTFS data to understand network structure, service frequency, temporal demand patterns, and stop usage characteristics.

The analysis combines schedule data, route information, and stop-level metrics to identify operational patterns and assess service regularity across the network.

## Notebooks

### 01 - Headway Analysis

This notebook computes vehicle headways from STIB GTFS schedules and analyzes service regularity across the network.

Key tasks:

- Headway calculation
- Average hourly headway estimation
- Time-group detection
- Service pattern visualization
- K-Means clustering
- QoS assessment

### 02 - Delay and Punctuality Analysis

Analysis of service delays, punctuality indicators, and operational performance.

### 03 - Time Group Detection

Automatic identification of service periods using change-point detection.
 
### 04 - Service Pattern Analysis

Clustering and visualization of recurring transit service patterns
## Technologies

- Python
- Pandas
- NumPy
- Plotly
- Seaborn
- Matplotlib
- GTFS-kit
- Ruptures
- Scikit-learn
## Key Findings

- Bus routes represent over 75% of the network.
- Route 7 is the busiest route by trip count.
- Peak service demand occurs around 17:00.
- Weekday service levels significantly exceed weekend levels.
- DE BROUCKERE is one of the most connected transfer hubs.
- Median network headway is approximately 11 minutes.
- Metro services offer the highest frequency.
## Repository Structure

```text
notebooks/
images/
data/
