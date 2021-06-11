# lammpstrj_motion_correction
Subtract the translational and rotational movement of the polymer chain to study subdiffusion. It works quite bad for systems with less than 50 beads.
Example:

> python lmp_motion_correction.py /path/to/lammpstrj /path/to/topology/file

Topology file should contain information on connectivity and bead types. More information can be found here https://www.mdtraj.org/1.9.5/index.html
