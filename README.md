# Sensor Data Analysis

This repository contains a dataset collected from environmental sensors, including parameters like humidity, temperature, signal strength, and more. The data can be used for research, analysis, and modeling.

## Dataset Description

The dataset includes the following fields:
- **Timestamp**: Date and time of the measurement.
- **Packet ID**: Unique identifier for each sensor.
- **H (Humidity)**: Relative humidity percentage.
- **T (Temperature)**: Temperature in degrees Celsius.
- **Hs (Soil Humidity)**: Soil humidity in percentage.
- **SP (Power)**: Transmission Power (varies from 2 to 14).
- **SF (Spreading Factor)**: LoRa spreading factor.
- **RSSI**: Received Signal Strength Indicator.
- **SNR**: Signal-to-Noise Ratio.

## File Structure

The data is stored in a CSV file (`dataset_recv.csv`), with each row representing a measurement. Columns are separated by semicolons (`;`).
