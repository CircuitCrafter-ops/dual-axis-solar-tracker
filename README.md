# 🔆 Dual-Axis Solar Tracker Controller – MATLAB Simulation

This project simulates a **Dual-Axis Solar Tracker** using MATLAB/Simulink. It aligns a solar panel with the sun throughout the day to maximize energy capture — a practical application in renewable energy systems.

---

## 👨‍🎓 Project Details

- **Author:** Adil Malik  
- **Degree:**  Electrical Engineering (2nd Year)  
- **Coursework:** MATLAB-based simulation project  
- **Tools Used:** MATLAB Simulink, Simscape, Control Systems Toolbox  

---

## 🎯 Project Objectives

- Simulate dual-axis sun tracking using azimuth and elevation angles
- Compare energy output with fixed vs tracked solar panels
- Run the simulation over a full 24-hour solar day

---

## 📁 Folder Structure

| File | Description |
|------|-------------|
| `Solar_Tracker_Model_Dual_axis.slx` | Main dual-axis tracking model |
| `Solar_calculations.mlx` | Calculates solar position based on time & location |
| `Irradiance.mlx` | Calculates received solar irradiance |
| `Comparison_and_analysis.slx` | Compares results: Fixed vs Tracker |
| `MyNotes.txt` | My personal understanding and key takeaways |
| `README.md` | This documentation file |

---

## 🚀 How to Run the Simulation
To get started with the Solar Tracker Controller Project, follow these steps:

Clone the repository:
 ```bash
   git clone https://github.com/your-username/solar-tracker.git
   ```
 Open the project in MATLAB/Simulink and follow the instructions in this README for usage.
  Note that the model relies on the parameters defined in the `WormAndGearConstraintParameters` file. Before running the model, ensure that you load these parameters.
## Usage and Steps to Run the Simulation


1. **Run** `Solar_calculations.mlx` to initialize location and time settings.
2. **Open** `Solar_Tracker_Model_Dual_axis.slx` in Simulink and simulate.
3. **Run** `Irradiance.mlx` to calculate panel exposure.
4. **Open** `Comparison_and_analysis.slx` to view and analyze results.

---

## 🖼## Simulation Results

The following simulation results are based on the geographical location of Roorkee, India, with coordinates at a latitude of 29.8543° N and a longitude of 77.8880° E, on March 23, 2024.

### Variation of Azimuth and Elevation Angles
The graph below illustrates the variation of azimuth and elevation angles throughout the day for the specified location and date.

<div align="center">
  <img src="https://github.com/user-attachments/assets/ff356713-0cfb-4966-be28-5e955d86a421" alt="Graph of angles" width="500">

</div>

### Solar Tracker Operation
- **Daytime Tracking:** The GIF below depicts the solar tracker following the sun during the day in Roorkee, India, on March 23, 2024. The simulation starts at midnight and shows how the tracker adjusts the panel angles to maximize sunlight exposure.

<div align="center">
  <img src="https://github.com/user-attachments/assets/5d96335e-3778-41d2-8dbf-f6ad33ca86b4" alt="Solar tracker during daytime" width="500">
</div>

- **Nighttime Energy Saving:** The following GIF shows the solar tracker conserving energy by slowly returning to its initial position during nighttime for the same location and date.
<div align="center">
  <img src="https://github.com/user-attachments/assets/75a0f1f1-27fd-4eea-b91c-a6aef1590b41" alt="Solar tracker at nighttime" width="500">
</div>

- **Comparative Analysis:** The following graph shows the irradiance generated by Fixed solar panel and the Proposed Dual axis solar tracker. This panel is oriented south with a tilt angle of 15°, optimized for summer by adjusting the tilt to capture maximum sunlight. The graph compares the performance of these two systems for the same location and date.

<div align="center">
  <img src="https://github.com/user-attachments/assets/8e6a92a4-85b5-4cd4-8478-f2a3a4472a7d" alt="Comparison based on irradiance" width="500">



</div>


>
> ### References
- National Renewable Energy Laboratory (NREL) – Solar Position Algorithm (SPA)
- NOAA Solar Position Calculator
- Worm and Gear Constraint Block - Solar Tracker from Simscape™ Multibody™
- S. K. Jha, S. Roy, V. K. Singh and D. P. Mishra, "Sun's Position Tracking by Solar Angles Using MATLAB," 2020 International Conference on Renewable Energy Integration into Smart Grids
  

---

## 📌 Notes

This project is based on open-source concepts but was independently configured and submitted as part of my academic coursework. All simulations and documentation were personally reviewed and tested.

---

## 📃 License

For educational use only. No commercial reuse allowed.
