# commercial-power-system_project
# Electrical Load Distribution & Power Supply System Documentation

## Overview

This repository provides a detailed overview of the electrical load distribution, power supply system, and associated calculations for a building project. It includes the layout, service sizing, panel configurations, and capacitor bank sizing for optimal power factor improvement. The contents also include mechanical schedules, conductor sizing, and power layout diagrams essential for the proper functioning of the electrical network across different building floors and rooms.

## Contents

- **Panel Load Distribution**
  - Detailed descriptions of load distribution across different panels, including Panels E, F, G, and H.
  - Each panel's respective rooms and load connections are specified, such as Room 113 Information, Room 118 Staff, and Room 117 Mechanical.

- **Power Factor Improvement (PFI)**
  - Power factor calculations for improving system efficiency by adding a capacitor bank.
  - Assumed and desired power factor values, and the necessary calculations for the required capacitor bank size.

- **Service Sizing and Conductor Selection**
  - A comprehensive calculation of conductor sizes for continuous and discontinuous loads.
  - Application of the CEC code for conductor sizing based on ambient temperature and insulating temperature.
  - Load current calculations and corresponding conductor sizes, with conduit sizes for each room based on load distribution.

- **Mechanical Schedule and Power Layout**
  - Mechanical schedule detailing various mechanical components such as furnaces, exhaust fans, and hot water tanks with their respective voltage, amperage, and conduit specifications.
  - Power layout diagram for visual representation of the entire system.

- **Lighting Layout**
  - Lighting design layout for the main floor and mezzanine floor, created using DIALux software.

## Power Factor Improvement (PFI) Calculation

- **Active Power (P)** = 250.74 kW
- **Assumed Existing Power Factor (PFold)** = 0.95
- **Desired Power Factor (PFnew)** = 0.98

Formulas for reactive power:
- **Qold** = P * tan(cos⁻¹(PFold)) = 82.41 KVAR
- **Qnew** = P * tan(cos⁻¹(PFnew)) = 50.91 KVAR
- **Required Capacitor Bank Size (Qc)** = Qold - Qnew = 31.5 KVAR

A **32 KVAR** capacitor bank is required to achieve the desired power factor improvement.

## Service Sizing

### Conductor Sizing

- **Conductor Size:** 800 Kcmil for continuous current of 404.02 A.
- **Conduit Size:** Sizing based on conductor requirements in various rooms.

### Room-Specific Electrical Load Distribution

- Detailed room-by-room load distributions, with necessary conductor and conduit sizing.
- Examples:
  - **Room 100 Foyer:** Load: 4.84 kW, Required Ampacity: 24.54 A, Conductor: 8 AWG
  - **Room 110 Cultural Room:** Load: 53.46 kW, Required Ampacity: 271.06 A, Conductor: 600 kcmil
  - **Room 202 Electrical Room:** Load: 29.05 kW, Required Ampacity: 147.30 A, Conductor: 4/0 AWG

## Mechanical Schedule

A detailed list of mechanical equipment in the building, such as:
- **Condensing Units:** For various rooms including Cultural Activity and Mechanical Rooms.
- **Furnaces:** Including mechanical and electrical room heating systems.
- **Exhaust Fans:** For different rooms requiring ventilation.
- **Baseboard Heaters:** For kitchens, cultural rooms, and other common areas.

## Diagrams and Layouts

- **Lighting Layout:** The diagrams are generated using DIALux software for the main floor and mezzanine floor.
- **Power Layout:** A visual representation of the power distribution across the building.
- **Mechanical Schedule Diagram:** The mechanical schedule is also illustrated for easy reference.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit pull requests with any enhancements, bug fixes, or new features. Please ensure your changes are well-documented, and follow the general structure outlined in the repository.

