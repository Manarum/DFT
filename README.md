# DFT
## XDATCAR
The XDATCAR files from VASP DFT output provides the `x,y,z` coordinates of atoms in all the ionic steps including initial non-relaxed, intermediate, and the final relaxed. The following code will extract all the ionic steps from XDATCAR and save as `.vasp` file (Atomic Structure). This VASP file has been used to convert into ACSF descriptors or any other descriptors. Each ionic steps in XDATCAR can also be saved as `.vasp` from OVITO but it will be time consuming.
