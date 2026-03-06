# STM32 MPU6050 Driver

This project demonstrates how to interface the MPU6050 IMU sensor with STM32 using the HAL library.

## Features
- I2C communication with MPU6050
- Accelerometer and gyroscope data reading
- Configurable sensor ranges
- Timer interrupt based sampling
- Low pass filter implementation

## Hardware
- STM32
- MPU6050 IMU sensor

## Architecture

Timer Interrupt
↓
MPU6050 I2C Read
↓
Raw Data
↓
Low Pass Filter
↓
Filtered Data
