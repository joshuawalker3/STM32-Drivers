# Peripheral Drivers for STM32 Microcontrollers

## Introduction
This repository holds frivers for various peripherals to be used with STM32 microcontrollers. The drivers use the vendor HAL so the drivers should be able to be used for all STM32 microcontrollers. The drivers are also wriiten to be used both with and without RTOS. 

## Standard Used
The standard for the drivers is to use POSIX standard function names as much as possible.  

## Example Code
Each driver directory includes an example program that can be flashed to a STM32F767ZI microcontroller to display the drivers functionality.

## Driver Installation
To use the drivers, install the drivers header and source code files in the appropriate directories and add the include preprocessor directive in main for the driver.

## Details on Individual Drivers
Each driver directory will have its own individual README that contains further details about the driver such as header defines, macros, and functions.