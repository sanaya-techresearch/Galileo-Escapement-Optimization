# Galileo-Escapement-Optimization
Novel Sensor-Based Energy Optimization for Electro-Mechanical Devices

Researcher: Sanaya Telang 

Technical Mentors: PhD Noah Graff, James Geraci, and Professor Michael Littman (Princeton University) 

Project Overview

This research addresses the energy inefficiencies in classical Galileo clock mechanisms5. While original designs rely on falling weights that require frequent resetting, modern electro-mechanical versions often use continuous-run motors that consume excessive power7. I engineered a hardware-assisted power gating technique and custom control software to selectively actuate the motor only when torque is required.

Engineering Highlights

•	Energy Savings: Achieved a verified 44.2% reduction in energy consumption.
•	Power Gating Logic: Implemented IR sensors and Arduino-based control to drop current draw to zero during the pendulum’s non-contact phase.
•	Precision Machining: Designed and 3D-printed a custom motor housing using SolidWorks to integrate the electronic drive with the mechanical gear train.
•	High-Frequency Data Logging: Replaced standard multimeters with an INA219 circuit to achieve 7.5ms sampling granularity (40-60 samples per cycle) for statistical analysis.

Mathematical Framework

My optimization strategy is grounded in the relationship between power, current, and time:
•	Power ($P$): Defined as $P = V \times I$13. Since $V = I \times R$, power is proportional to the square of the current ($P \propto I^2 \times R$).
•	Energy ($E$): Calculated as the integral of power over time ($E = \int P \, dt$).
•	The Result: By dropping the current ($I$) to zero for 42.2% of the oscillation period, the energy consumption follows a linear downward trend compared to continuous-run systems.

Portability & Scalability

This method is portable and applies to various high-torque mechanical systems17:
•	Electric Mowers: Estimated to extend the runtime of a 40V RYOBI mower from 80 to 128 minutes, increasing coverage from 3,000 to 6,400 sq ft.
•	Air Compressors: Calculated to extend the runtime of a VIAIR compressor from 30 to 42 minutes by assisting only during the compression stroke.

Repository Contents

1. Final Research Paper Uploaded
2. Arduino Code and Measurement Graphs embedded in the paper
3. Contributors and Mentors mentioned in the Acknowlegment section of the paper.
   
