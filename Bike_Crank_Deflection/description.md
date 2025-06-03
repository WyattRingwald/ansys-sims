# Bike Crank Deflection Simulation

A static structural analysis of a bicycle crank arm under a 100 lbf vertical load using ANSYS 2024 R2. This simulation evaluates the stress and deformation response under typical loading.

## 🔧 Setup

- **Force**: 100 lbf
- **Support**: Fixed at crank mounting point
- **Solver**: Static Structural
- **Units**: Imperial (in, lbf, psi)

## 🖼️ Visuals

### Geometry and Mesh

- Geometry setup with load and constraint annotations  
  ![Geometry](visuals/Annotated_Geometry_View.png)

- Hex-dominant mesh with refinement around fillets and stress points  
  ![Mesh](visuals/Mesh.png)

### Results

- **Total Deformation**: Max = ~0.052 in  
  ![Deformation](visuals/Total_Deformation.png)  
  🎥 [Animation](visuals/Deformation_Animation.mp4)

- **Normal Stress (X-Axis)**: Peak ~13,303 psi  
  ![Stress](visuals/Stress_Model.png)  
  🎥 [Animation](visuals/Stress_Animation.mp4)

## 📌 Key Observations

- Stress is highest near the root of the crank arm due to bending.
- Deformation occurs mainly at the free end.
- The component shows acceptable stress levels for static loading, indicating good structural integrity.

