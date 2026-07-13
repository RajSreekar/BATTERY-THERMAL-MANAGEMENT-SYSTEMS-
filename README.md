# BATTERY THERMAL MANAGEMENT SYSTEMS
A capstone project on hybrid thermal management for Li-ion battery packs used in EVs and drones

# Problem Statement
Lithium-ion batteries generate excessive heat during operation, making conventional air cooling insufficient. This project develops a hybrid thermal management system to improve cooling efficiency and battery safety. Excessive temperatures can result in:
- Reduced battery lifespan & Capacity degradation
- Lower efficiency
- Thermal runaway & Safety hazards

# Project Summary
A hybrid Battery Thermal Management System (BTMS) integrating Phase Change Material (PCM), heat pipes, and cooling fins is proposed to efficiently dissipate heat from lithium-ion battery packs. PCM absorbs excess heat, heat pipes rapidly transfer it away from the cells, and cooling fins enhance heat dissipation through increased airflow, resulting in improved thermal performance, temperature uniformity, and battery safety.

# Technologies & Materials Used:
| Category           | Tools                                                                   |
| ------------------ | ----------------------------------------------------------------------- |
| CAD Design         | Fusion 360                                                              |
| CFD Simulation     | ANSYS Fluent                                                            |
| Battery Modeling   | LiFePO₄, NMC, Molicel Cells                                             |
| Thermal Materials  | Paraffin Wax PCM, Silicon Carbide (SiC), Expanded Graphite, Epoxy Resin |
| Cooling Components | Heat Pipes, Pulsating Heat Pipes, Aluminum Fins                         |

- Battery Configurations Studied:
  - LiFePO₄ Battery Pack: An 8-cell (4S2P) LiFePO₄ battery module was analyzed to evaluate the proposed BTMS, with operating temperatures reaching 42°C during charging and 52°C during discharging.

  - Molicel Battery Pack: A 30-cell (6S5P) Molicel battery pack was designed for high-discharge applications, reaching temperatures of up to 60°C to assess the cooling system under demanding operating conditions.

 - PCM Composition: A composite Phase Change Material comprising 50% paraffin wax, 30% epoxy resin, 17% silicon carbide (SiC), and 3% expanded graphite (EG) was developed through hit & trial to enhance thermal conductivity while maintaining efficient latent heat storage for improved battery cooling.

 - Simulation Studies: Thermal performance was evaluated using ANSYS Fluent through simulations of single-cell, multi-cell, and full battery pack configurations with PCM and heat pipes. The analyses examined temperature distribution, pressure, airflow velocity, and overall heat transfer to validate the effectiveness of the proposed BTMS.
