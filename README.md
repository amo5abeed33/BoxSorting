# BoxSorting
This repository contains a PLCsim (TIA Portal) implementation of a box sorting algorithm. The algorithm is designed to control a simulated conveyor belt system to sort boxes based on a predefined criteria (e.g., size, color, destination).

Key Features:

Clear and Modular Design: The PLC code is structured logically with well-defined function blocks (FBs) for each stage of the sorting process (e.g., sensor input, decision logic, actuator control).
Configurable Sorting Criteria: The sorting logic can be easily adapted to different box characteristics by modifying the relevant parameters within the PLC program.
Realistic Simulation: The algorithm is intended for use with PLCsim (TIA Portal), allowing for realistic simulation and testing of the sorting process before deployment on physical hardware.
Well-Commented Code: The PLC code is thoroughly commented to explain the functionality of each section, making it easy to understand and modify.
Scalable Architecture: The modular design allows for potential expansion to handle more complex sorting systems with additional sensors and actuators.
How it Works:

Box Detection: Sensors (simulated in PLCsim) detect the presence of a box on the conveyor belt.
Criteria Acquisition: Based on sensor readings or other input mechanisms (e.g., barcode scanner simulation), the algorithm determines the sorting criteria for the current box.
Decision Logic: The core of the algorithm compares the acquired criteria against predefined sorting rules.
Actuator Control: Based on the decision, the algorithm activates simulated actuators (e.g., diverters, pushers) at appropriate locations along the conveyor belt to guide the box to its designated output.
Tracking and Management (Optional): The algorithm may include logic to track the number of sorted boxes for each category.
Contents:

PLC_Project/: Contains the TIA Portal project files (.ap1x or similar) with the PLC program implementing the sorting algorithm.
Documentation/: (Optional) May include diagrams, flowcharts, or further explanations of the algorithm and its implementation.
README.md: This file (describing the project).
Getting Started:

Prerequisites:
Siemens TIA Portal software installed.
PLCsim (integrated within TIA Portal).
Import Project: Open TIA Portal and import the PLC project file from the PLC_Project/ directory.
Simulate: Activate PLCsim within TIA Portal.
Monitor and Test: Use the TIA Portal watch table or online monitoring features to observe the algorithm's behavior and simulate box arrivals and sensor inputs.
Modify (Optional): Adapt the sorting criteria and logic within the PLC program to suit your specific requirements.
Potential Enhancements:

Integration with a simulated HMI for visualization and control.
Implementation of error handling and fault detection.
Support for more complex sorting criteria and multiple sorting destinations.
Inclusion of a simulated database or data logging for tracking sorted items.
