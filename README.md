# Shot Noise Measurement and Data Analysis

This repository contains Python scripts to perform shot noise measurements using an oscilloscope and a Toptica laser setup, along with data processing and visualization. The script leverages instruments like a LeCroy oscilloscope and Sigilent RSA spectrum analyzer, alongside a Toptica laser controller, to acquire and analyze noise data in real-time.


## Overview

This project is focused on acquiring and analyzing shot noise data from a Toptica laser system using a LeCroy oscilloscope and a Sigilent RSA spectrum analyzer. The script performs the following tasks:

1. Connects to the oscilloscope and spectrum analyzer via VISA.
2. Configures and controls the Toptica laser using its SDK.
3. Acquires time traces from the oscilloscope in binary format.
4. Processes the shot noise data.
5. Plots the mean, standard deviation, and shot noise over time using Plotly.

## Requirements

Ensure you have the following Python packages installed:

- `pyvisa`: To communicate with the instruments via GPIB/USB.
- `lecroy`: For handling LeCroy oscilloscope files.
- `numpy`: For numerical operations.
- `scipy`: For signal processing.
- `toptica.lasersdk`: To control the Toptica laser.
- `plotly`: For creating interactive plots.

You will also need the Toptica laser controller's SDK installed and accessible from your Python environment.


