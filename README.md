# Coaxial Magnetic Gear with Variable Air Gap

## Overview
This project explores the design and analysis of a coaxial magnetic gear system with a variable air gap for non-contact torque transmission.

## Objective
To analyze how torque varies with air gap and understand magnetic coupling behavior in the system.

## Key Idea
- Magnetic gears transmit torque without physical contact
- Air gap directly affects magnetic interaction
- Adjusting air gap enables potential control of torque output

## Methodology
- Defined air gap range: 1 mm to 5 mm
- Collected torque data based on magnetic behavior
- Used Python (NumPy, Matplotlib) for analysis and visualization

## Results

| Air Gap (mm) | Torque (Nm) |
|-------------|------------|
| 1 | 11.2 |
| 2 | 7.8 |
| 3 | 5.1 |
| 4 | 3.4 |
| 5 | 2.3 |


## Observations
- Torque decreases with increasing air gap
- Relationship is non-linear
- Small gap changes significantly impact torque

## Conclusion
Magnetic coupling weakens with distance, reducing torque transmission. This enables the possibility of controlling torque through air gap variation.

## Tools Used
- Python (NumPy, Matplotlib)
- CAD (Fusion 360)

## Future Work
- Validate using ANSYS Maxwell simulation
- Implement dynamic air gap control
- Develop closed-loop torque control system
