# Comprehensive Phase Stability Database for Al-Li-Cu System

## Dataset file
[AlLiCu.phases.formation.energy.xlsx](AlLiCu.phases.formation.energy.xlsx)

## Description
This dataset provides a comprehensive collection of structural, energetic, and stability data for phases in the Al-Li-Cu ternary system. 
The database combines information from multiple established materials databases including the Open Quantum Materials Database (OQMD), 
Materials Project, ALLOY DATABASE, and the Inorganic Crystal Structure Database (ICSD). 
It contains data for 318 unique configurations, including special attention to seven distinct $T_1$ phase structures.

## Dataset Overview
- No.: Configuration index number
- SimpleSpecies: Simplified chemical composition
- Species: Detailed chemical composition
- SpaceGroup: Crystallographic space group
- AtomNumer: Number of atoms in the unit cell
- Etot(eV): Total energy in electron volts
- Ecoh(eV/atom): Cohesive energy per atom in electron volts
- Eform(eV/atom): Formation energy per atom in electron volts
- Ehull(eV/atom): Energy above the convex hull (decomposition energy) in electron volts per atom
- IsStable: Boolean indicator of phase stability
- StablePhases: Decomposition products for unstable phases
- Source: Origin database of the structure data

## Use Guidance
- Format Provided: The data is provided in `XLSX` format, compatible with common analysis tools including:
  - Microsoft Excel
  - Python (with libraries like pandas and openpyxl)
  - MATLAB
  - R
- Stability Analysis: The dataset enables comprehensive phase stability analysis through:
  - Formation energy calculations
  - Convex hull construction
  - Decomposition energy (hull distance)
  - Phase diagram generation

## Data Sources
This dataset integrates information from four major materials databases:
- Open Quantum Materials Database (OQMD) [https://oqmd.org]
- Materials Project [https://next-gen.materialsproject.org]
- ALLOY DATABASE [https://alloy.phys.cmu.edu]
- Inorganic Crystal Structure Database (ICSD) [https://icsd.fiz-karlsruhe.de]

## License
This dataset is provided for non-commercial academic use only.

## Contributors
- Lin Zhang
- Feng Liu

## Current Version Note
This README serves as a preliminary document and all elements are subject to change until the manuscript reaches peer-reviewed status. 
For precise details on data interpretation, please consult the final paper when published. Until official publication, 
any results or conclusions drawn from this dataset should be regarded with consideration for potential updates or corrections.

## Note
When using this dataset in your research:
1. Properly acknowledge all original data sources (OQMD, Materials Project, ALLOY DATABASE, and ICSD)
2. Cite the associated publication (details to be provided upon publication)
3. Use the data in accordance with the licenses of the original databases