# BATTERY THERMAL MANAGEMENT SYSTEMS
A capstone project on hybrid thermal management for Li-ion battery packs used in EVs and drones

# Problem Statement
Lithium-ion batteries generate excessive heat during operation, making conventional air cooling insufficient. This project develops a hybrid thermal management system to improve cooling efficiency and battery safety. Excessive temperatures can result in:
- Reduced battery lifespan & Capacity degradation
- Lower efficiency
- Thermal runaway & Safety hazards

# Project Summary
A hybrid Battery Thermal Management System (BTMS) integrating Phase Change Material (PCM), heat pipes, and cooling fins is proposed to efficiently dissipate heat from lithium-ion battery packs. PCM absorbs excess heat, heat pipes rapidly transfer it away from the cells, and cooling fins enhance heat dissipation through increased airflow, resulting in improved thermal performance, temperature uniformity, and battery safety.

<img width="380" height="205" alt="Heat Transfer" src="https://github.com/user-attachments/assets/e20f7f42-88be-4d5e-870e-e4ec16e81694" />

- This image depicts the working principle of the project

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

# Simulated Results:

https://github.com/user-attachments/assets/94f355bb-0325-44fa-9ecc-0e547c49b59c

- This video shows the ANSYS simulation of the heat being transfer with only PCM & PHP, which proved insufficient to transfer the heat in the required time

https://github.com/user-attachments/assets/565f1cb4-fd7f-4f07-b5f9-fbdcd2d7b0cc

- This video depicts the ANSYS simulation of the final working model. ANSYS Fluent simulations were conducted to evaluate the thermal performance of battery cells and modules, analyzing temperature, pressure, airflow, and heat transfer to validate the effectiveness of the proposed hybrid BTMS.

<img width="718" height="422" alt="image_2026-07-14_020557465" src="https://github.com/user-attachments/assets/5cb7cd04-e722-4541-a9b6-7597bcf3f725" />

- This is the CAD designed transparent schematic that shows the final working model of the product.
