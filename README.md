# GNSSPositionEstimator
A Python-based tool for estimating GNSS receiver position using satellite pseudo-range data and least squares optimization. Implements ECEF to geodetic coordinate conversion adhering to the WGS-84 model.

## Overview
GNSSSPositionEstimator is a Python tool designed to accurately estimate the position of a GNSS receiver. It uses satellite pseudo-range data and applies the method of least squares optimization to determine the receiver's Earth-Centered, Earth-Fixed (ECEF) coordinates. The tool then converts these coordinates to geodetic coordinates (latitude, longitude, and height) based on the WGS-84 ellipsoid model.

## Features
- Calculation of GNSS receiver position from pseudo-range measurements of satellites.
- Implementation of least squares optimization for accurate estimation.
- Conversion of ECEF coordinates to geodetic coordinates.
- Use of the WGS-84 ellipsoid model for accurate representation of the Earth's shape.

## Requirements
- Python 3
- NumPy
- SciPy

## Installation
Clone the repository:
```bash
git clone https://github.com/mrpurplenice/GPSPositionEstimator.git
