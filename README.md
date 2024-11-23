# Sensor Data Analysis

This repository contains a dataset collected from environmental sensors, including parameters like humidity, temperature, signal strength, and more. The data can be used for research, analysis, and modeling.

## Dataset Description

The dataset includes the following fields:
- **Timestamp**: Date and time of the measurement.
- **Sensor ID**: Unique identifier for each sensor.
- **H (Humidity)**: Relative humidity percentage.
- **T (Temperature)**: Temperature in degrees Celsius.
- **Hs (Soil Humidity)**: Soil humidity in percentage.
- **SP (Speed)**: Speed parameter (e.g., wind or data packet speed).
- **SF (Spreading Factor)**: LoRa spreading factor.
- **RSSI**: Received Signal Strength Indicator.
- **SNR**: Signal-to-Noise Ratio.
- **Tx/Rx Details**: Transmission power, trials, and air time.

## File Structure

The data is stored in a text file (`dataset_recv.txt`), with each row representing a measurement. Columns are separated by semicolons (`;`).

Example:
