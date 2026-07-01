# PA-GFP Cavity Engineering

**Computational modeling of steric cavities in Photoactivatable GFP using PyMOL**

## Overview
This repository contains the PyMOL scripts and structural analysis data for a computational study on Photoactivatable Green Fluorescent Protein (PA-GFP). The project investigates the structural limits of photoactivation by engineering internal steric cavities around the chromophore. 

## The Importance
PA-GFP is a critical tool for super-resolution microscopy, allowing researchers to illuminate specific proteins with precise spatiotemporal control. However, the efficiency of this light-induced activation depends heavily on the physical space (steric environment) surrounding the chromophore. 

By applying classic cavity-creation methodologies from T4 Lysozyme to PA-GFP, this project maps exactly how much internal cavity volume can be engineered while maintaining chromophore accessibility. Ultimately, this provides a structural framework for designing next-generation fluorescent probes that require lower UV exposure, reducing cellular damage during live-cell imaging.

## Key Findings (TBD)
- **Baseline Control:** The well-characterized T203H mutation maintains a tight spatial distance of **3.3 Å** to the chromophore.
- **Novel Mutation:** Engineering the **F153A** mutation removes a bulky phenylalanine residue, creating a substantial internal cavity.
- **Structural Shift:** This mutation significantly expands the distance to the chromophore to **13.3 Å**.
- **Result:** Large internal cavities can be successfully engineered in PA-GFP without disrupting the core architecture required for photoactivation.

## How to Run the Analysis
The structural analysis was performed using [PyMOL](https://pymol.org/). To replicate the cavity engineering and distance measurements:

1. Download the `PA_GFP_Mutagenesis.pml` script from this repository.
2. Ensure you have the initial PA-GFP PDB file in the same directory.
3. Open PyMOL and run the script via the command line:
   ```pymol
   run PA_GFP_Mutagenesis.pml
