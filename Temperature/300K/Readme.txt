The directory has the following files:

1. in.deform - sample input script for tensile deformation of Au nanowire
2. Au_u3.eam - EAM (Embedded Atom Method) potential file for describing Au-Au atomic interaction.

Tasks - 
1. Decipher the strain rate used from the units
2. Perform tensile deformation of Au nanowire, and study the
	Stress-strain response, yield strength, modulus
	Deformation mechanisms (visualize in Ovito) including dislocations (if possible), twinning etc. 
3. Effect of strain rate and temperature on deformation characteristics

Note:
1. We are creating an FCC Au nanowire that has periodic structure only along Z axis (visualize in OVITO to convice yourself). 
2. We also create a rhombic cross-section for the nanowire (first several lines in the 'in.deform' script that involve 'prism', 'del' and 'group' commands. 
4. Output files:
  'deform.dump' contains positions, as well as several per-atom properties such as Potential and Kinetic energy and individual stress components. 
  'stress_strain.txt' contains the stress-strain data. Data is in 3 columns: column 1 - time step; 2 - strain and 3 - stress (in GPa). 

Refer to the 2 PDFs for comparison with literature