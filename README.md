
The zip file contains Five folders (please download from here https://doi.org/10.1039/D1SM01825F)

.mol2 files of epoxy and crosslinker are provided. 



Each folder has two data files. 

data.300 and data.visualize.

c.txt contains the reacted carbons 
n.txt contains the reacted nitrogens
LAMMPS output for the temperature ramp
The density data. 


To vsiualize crosslink bonds:
Use topotools to load the data file data.300

Type 18 is the nitrogen 
Type 20 is the carbon

To visualize the heterogeneities:
epoxy rich systems (R=0.4, 0.6)
Type 21 E2
Type 22 E1
Type 23 E0
Type 24 A4

amine rich systems (R=2, R=3)
Type 21 E2
Type 22 A4 
Type 23 A3
Type 24 A2
Type 25 A2p
Type 26 A1
Type 27 A0

Stoichiometric  (R=1)
Type 21 E2
Type 22 A4

