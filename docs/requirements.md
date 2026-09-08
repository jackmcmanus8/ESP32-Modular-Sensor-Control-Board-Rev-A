# Rev A Requirements

## Primary Function
Generate a 2D environmental map using LiDAR distance measurements
and IMU orientation/motion data.

## Processor
- ESP32-S3-WROOM-1

## Sensors
- ICM-42688-P IMU
- External LiDAR module

## Communications
- SPI: IMU
- UART1: LiDAR
- UART2: expansion / future flight controller
- I2C: expansion
- Wi-Fi: laptop telemetry / mapping
- USB: programming and debugging

## Power
- USB-C 5 V input
- 5 V rail available to LiDAR
- 3.3 V regulated rail for ESP32 and IMU

## Expansion
- UART header
- I2C header
- GPIO header

## Rev A Success Criteria
1. Power the board safely
2. Program the ESP32
3. Read IMU data over SPI
4. Read LiDAR data over UART
5. Determine scan direction using inertial measurements
6. Send measurements to a laptop over Wi-Fi
7. Display the measurements as a live 2D map