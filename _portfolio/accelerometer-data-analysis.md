---
title: "Smartphone Accelerometer Data Analysis"
excerpt: "Python-based processing and analysis of smartphone accelerometer data collected with Phyphox."
collection: portfolio
---

## Overview

This course project explored the collection, processing, and analysis of smartphone accelerometer data using Python. Linear acceleration data were collected with the Phyphox mobile application and analyzed both at the individual-subject and group levels.

The project was completed as part of BME 598 – Applied Programming at Arizona State University.

## Data Collection

Thirty seconds of linear acceleration data were collected using the Phyphox "Acceleration (without g)" experiment. The smartphone was held in a standardized orientation with the arm extended to reduce variability in data collection.

Acceleration measurements included the x, y, and z components as well as the absolute acceleration magnitude.

## Data Processing

Python functions were used to:

- Read device metadata and raw acceleration CSV files
- Extract accelerometer specifications from device metadata
- Parse x-, y-, and z-axis acceleration measurements
- Calculate absolute acceleration magnitude when not provided in the exported data
- Compute descriptive statistics for acceleration measurements
- Combine data from multiple subjects into a pandas MultiIndex DataFrame

## Analysis

For individual accelerometer recordings, mean and standard deviation were calculated for the x, y, z, and absolute acceleration measurements. Histograms were used to visualize their distributions.

For the group analysis, acceleration data from multiple subjects were processed using pandas. Standard deviation was calculated for each acceleration component for each subject, and the subject with the lowest variability was identified for each component.

## Tools

**Python · pandas · Matplotlib · Jupyter Notebook · Phyphox**

## Skills Demonstrated

- Biomedical sensor data processing
- Time-series data handling
- Descriptive statistical analysis
- Multi-subject data organization with pandas
- Data visualization
- Modular Python programming

## Course Context

This project was completed within the framework of BME 598 – Applied Programming. Starter materials and the project framework were provided by Bradley Greger, Neural Engineering Lab, Arizona State University. The provided materials are distributed under the GNU General Public License v3.
