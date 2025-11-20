# M5StackLCD_Simulink
Simulink block example to allow displaying table data and X-Y graph onto M5Stack devices (Tested against M5Stack Fire.  Report to also work on M5Stack Basic)
The block is a MATLAB System block calling C++ libraries underneith.  The skelton was generated Arduino IO Device Builder, which is part of Simulink Arduino Support Package (see "Software Requirement" section below)
https://www.mathworks.com/help/simulink/arduino-io-device-builder.html

Majority of C++ code (M5FireLCD.cpp and M5FireLCD.h) was created using AI Coding tools.  

# MATLAB Version Supported
The block runs on MATLAB version R2023a or newer.
(As of Nov.20.2025, tested against R2025b)

# Software Requirement
MATLAB, Simulink, and Simulink Arduino Support Package from MATLAB File Exchange
https://jp.mathworks.com/matlabcentral/fileexchange/40312-simulink-support-package-for-arduino-hardware
After the support package installation, make sure to setup and enable ESP32 hardware support.

# Install
To be written

# Disclaimer
This is a personal project of the Author.
Code is shared under BSD License

