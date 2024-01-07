## Random Fuse Model Theory

The Random Fuse Model (RFM) serves as a representation of the behavior of materials under stress, particularly in fracture mechanics. In this context, the implemented RFM in the `ProgrammingProject.ipynb` utilizes a square lattice to simulate the behavior of an elastic/brittle material subjected to a uniaxial load.

### Model Configuration
- **Boundary Conditions:** 
  - Constant voltages V=1 and V=0 are applied at the top and bottom boundaries respectively, representing the applied uniaxial load in the vertical direction.
  - Periodic boundary conditions in the horizontal direction mimic the material's geometry.

### Simulation Details
- **Crack Simulation:**
  - Four contiguous vertical links are removed to simulate a horizontal crack within the lattice structure.
  - The resulting system demonstrates the redistribution of load and stress around the crack profile.

### Observations
- **Network Structure Visualization:** 
  - Figure i in the notebook displays the actual configuration of the fuse network, representing the lattice structure with the removed vertical links simulating the crack.
- **Current Flow Visualization:** 
  - Figure ii demonstrates the currents within the system resulting from the applied load and the presence of the crack.
  - Thicker lines indicate higher currents, illustrating load redistribution due to the crack, akin to stress redistribution in fracture mechanics.

### Significance
- **Analogous Stress Redistribution:** 
  - The flow of currents in the horizontal direction mirrors the load redistribution around the crack, providing insights akin to stress patterns in fracture mechanics.
- **Model Application:** 
  - This model serves as a tool to study the behavior of materials under stress, aiding in understanding stress distribution and potential failure mechanisms in brittle materials.

### Conclusion
The Random Fuse Model implementation in this notebook offers a visualization of load redistribution and current flow around a simulated crack in a square lattice. Through this representation, it provides a simplified yet insightful analogy to stress redistribution in fracture mechanics, aiding in the comprehension of material behavior under tension and the implications of crack formation.

This README provides an overview of the RFM's implementation and its relevance in simulating stress redistribution around cracks in materials under tension. Adjust and expand upon these points to best describe the project's context, implementation, and significance.
