# Embedded-Sensor-DSP-Simulation
: MATLAB simulation of signal noise filtration for embedded sensors.
# Simulated Embedded Sensor Signal Conditioning

## Project Overview
This project simulates the digital signal processing (DSP) pipeline for an optical distance sensor (e.g., LiDAR or Laser Diode). It addresses the common engineering problem of high-frequency noise interference in raw sensor data.

## Technical Implementation
* **Language:** MATLAB
* **Method:** Discrete-time Signal Processing
* **Filter Type:** Moving Average (Low-Pass Filter)

## Key Results
* **Simulation:** Generated synthetic sensor data with a noise amplitude of 2.0 (simulating electrical interference).
* **Performance:** The DSP algorithm reduced the Root Mean Square Error (RMSE) from **2.00 cm (Raw)** to **0.60 cm (Filtered)**.
* **Outcome:** Achieved a **70% reduction in signal error**, stabilizing the control input for downstream actuators (e.g., servos).

## Visualization
*(Note: View the included PDF for the full code and high-resolution plots)*
