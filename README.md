# STIB GTFS Service Pattern Analysis

Analysis of STIB public transport service patterns using GTFS data, headway computation, time-group detection, clustering, and service regularity assessment.

## Project Overview

This project analyzes public transport service patterns in the STIB-MIVB network using GTFS schedule data.

The objective is to understand service regularity, headway distribution, and temporal operating patterns across bus, tram, and metro lines.

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

## Repository Structure

```text
notebooks/
images/
data/
