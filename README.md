# Galileo-Escapement-Optimization
Novel Sensor-Based Power Optimization for Electro-mechanical Escapements

Overview
This project addresses the energy inefficiency inherent in continuous-running motors for Galileo-based electro-mechanical clock designs. By implementing a hardware-assisted power gating technique controlled via software, this design achieves significant energy savings without sacrificing timekeeping accuracy.

Technical Achievements
Energy Efficiency: Achieved a 44.2% reduction in power consumption.
Power Gating Logic: Developed software to disable the battery when the pendulum is not in contact with the gear system, dropping current draw to zero during idle phases.
High-Frequency Data Acquisition: Utilized an INA219 circuit to sample current, voltage, and power every 50 milliseconds.
Statistical Analysis: Verified results through mean-standard deviation hysteresis curves over 400ms oscillation periods.

Repository Contents

