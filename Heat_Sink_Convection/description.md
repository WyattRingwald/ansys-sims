# Heat Sink Convection Simulation

This project simulates convective heat transfer across a finned aluminum heat sink using ANSYS Fluent. Forced airflow drives heat away from the heat sink to evaluate thermal performance under realistic cooling conditions.

## 🛠 Simulation Setup

- **Solver**: ANSYS Fluent
- **Flow Type**: Steady-State, 3D
- **Turbulence Model**: Laminar
- **Energy Equation**: Enabled
- **Material**: Air (flow), Aluminum (sink)

---

## 🖼️ Visuals

### Mesh

- **Air Domain Mesh**  
  ![Air Flow Mesh](visuals/Air_Flow_Mesh.png)

- **Full Domain Mesh**  
  ![Full Mesh](visuals/Full_Mesh.png)

- **Heat Sink Only Mesh**  
  ![Heat Sink Mesh](visuals/Heat_Sink_Mesh.png)

---

### Results

#### 🔥 Thermal Fields

- **Overall Domain Temperature**  
  ![Full Thermal](visuals/Full_Thermal.png)

- **Heat Sink Temperature Distribution**  
  ![Sink Temp](visuals/Temperature_of_heatsink.png)

#### 🌬️ Flow Visualization

- **High-Density Thermal Streamlines**  
  ![High Density](visuals/High_Density_Thermal_Flow.png)

- **Low-Density Thermal Streamlines**  
  ![Low Density](visuals/Low_Density_Thermal_Flow.png)

---

### 📉 Residuals

Convergence was achieved with residuals below `1e-5` for energy and `1e-3` for velocity and continuity.

![Residuals](visuals/Scaled_Residuals.png)

---

## 📌 Key Takeaways

- Thermal boundary layer develops across fins and exits with a temp gradient.
- Flow recirculation is minimal, indicating good air throughput.
- Finned geometry increases heat rejection effectiveness across the domain.
