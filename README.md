# Gold Nanowire Deformation Project

This project involves molecular dynamics simulations of tensile deformation of a gold (Au) nanowire using LAMMPS. The objective is to study the mechanical response, deformation mechanisms, and the effects of strain rate and temperature on nanowire deformation.

## Objectives
1. **Decipher Strain Rate:**  
   Understanding the strain rate used in the simulations based on the units provided.
   
2. **Tensile Deformation Simulation:**  
   - **Stress-Strain Response:** Analyze the stress-strain curve to evaluate the yield strength and Young's modulus of the nanowire.
   - **Deformation Mechanisms:** Visualize and study the deformation mechanisms using Ovito, focusing on identifying dislocations, twinning, and other structural changes that occur during deformation.

3. **Effect of Strain Rate and Temperature:**  
   Investigate how varying strain rates and temperatures affect the deformation characteristics, focusing on mechanical properties such as yield strength, stress, and deformation mechanisms.

## Simulation Details
- **Material:** Gold (Au) Nanowire
- **Simulation Software:** LAMMPS for molecular dynamics, Ovito for visualization
- **Temperatures Simulated:** 300K, 250K, 200K, 150K
- **Strain Rates Simulated:**  
  - 2.5 × 10⁻⁹ s⁻¹  
  - 5 × 10⁻⁹ s⁻¹  
  - 1 × 10⁻⁸ s⁻¹  
  - 5 × 10⁻⁸ s⁻¹

## Key Findings
1. **Stress-Strain Response:**  
   The stress-strain curve provides insights into the mechanical response of the nanowire under tensile deformation. Key points like the yield strength and the Young’s modulus are extracted for each strain rate and temperature combination.

2. **Deformation Mechanisms:**  
   Using Ovito, we visualized the deformation mechanisms that include dislocation motion and potential twinning. The visualizations reveal the onset of plastic deformation and how the nanowire responds at different strain rates and temperatures.

3. **Effect of Strain Rate and Temperature:**  
   - At lower strain rates, the nanowire exhibits more pronounced plastic deformation and lower yield strength.
   - Higher temperatures generally result in increased ductility, while lower temperatures show more brittle behavior.

## Usage

### Requirements
- **LAMMPS:** To run the molecular dynamics simulations.
- **Ovito:** For visualizing the deformation and identifying key mechanisms like dislocations and twinning.

### Running the Simulations
To run the tensile deformation simulation of the Au nanowire:

1. Download and install LAMMPS.
2. Set up the input files with the desired strain rate and temperature.
3. Execute the LAMMPS script:
   ```bash
   lmp -in in.deform
