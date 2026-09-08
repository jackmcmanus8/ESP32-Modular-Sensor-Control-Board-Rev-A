# ESP32 LiDAR + IMU Mapping Board

Custom ESP32-S3 based embedded mapping platform designed in
Altium Designer.

## Project Goal

Develop a compact embedded system that combines LiDAR distance
measurements with inertial data to generate a live 2D map of the
surrounding environment.

The board is intended to operate as a standalone mapping platform
and can later integrate with a drone flight controller through UART.

## Core Hardware

- ESP32-S3-WROOM-1
- ICM-42688-P 6-axis IMU
- UART LiDAR interface
- USB-C power/programming
- 3.3 V onboard regulation
- UART expansion
- I2C expansion
- GPIO expansion
- Wi-Fi telemetry

## Current Status

Rev A schematic design.