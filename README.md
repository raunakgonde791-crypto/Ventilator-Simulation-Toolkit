# Ventilator Simulation Toolkit

Five Jupyter notebooks for simulating mechanical ventilation and lung mechanics.

## Notebooks

1. `01_lung_mechanics.ipynb` – Single‑compartment lung model. Interactive sliders for resistance, compliance, PEEP, rate. Plots pressure, flow, volume, and PV loop. Shows tidal volume, minute ventilation, dynamic compliance.

2. `02_multi_compartment.ipynb` – Two‑compartment lung (left/right). Each compartment has independent R and C. Detects asynchrony (difference in peak filling times). Plots volumes, flows, and PV loops for both compartments.

3. `03_ventilation_modes.ipynb` – Compare Volume Control, Pressure Support, and SIMV modes. Mode‑specific controls appear dynamically. Calculates work of breathing (area under PV loop).

4. `04_patient_asynchrony.ipynb` – Adds patient muscle effort (sinusoidal). Detects wasted efforts and double triggers. Shows pressure components (machine + muscle) and marks wasted efforts on the volume plot.

5. `05_alarms_safety.ipynb` – Monitors high peak pressure, low tidal volume, apnea, and disconnection. Displays alarm messages on the plot and console. Adjustable thresholds.

## Requirements

Install with pip:
