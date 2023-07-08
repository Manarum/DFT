# DFT
## XDATCAR
The XDATCAR files from VASP DFT output provides the `x,y,z` coordinates of atoms in all the ionic steps including initial non-relaxed, intermediate, and the final relaxed. The following code will extract all the ionic steps from XDATCAR and save as `.vasp` file (Atomic Structure). This VASP file has been used to convert into ACSF descriptors or any other descriptors. Each ionic steps in XDATCAR can also be saved as `.vasp` from OVITO but it will be time consuming. The input file of the 'XDATCAR.ipynb' is the XDATCAR file which has been obtained from the output files of the VASP DFT simulations.

## EnergyConv
To plot free energy TOTEN vs Iterations including ionic steps and electronic steps. The input file of the script is the OUTCAR file. This script has been used to plot the energy convergence of the system.
