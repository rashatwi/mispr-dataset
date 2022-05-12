
## redox.csv
Contains the ionization potential, electron affinity, and electrochemical windows for the first electron transfer at the B3LYP/def2-TZVP level 
of theory in an acetone solvent using the SMD solvation model. Calculations were performed using the thermodynamic cycle.

The column names correspond to the following:
,mol,chemsys,ip_gas,ip_sol,ea_gas,ea_sol,EW_gas,EW_sol

1. **mol**: structure number 
2. **chemsys**: molecule chemical system
3. **ip_gas**: ionization potential in the gas phase (eV)
4. **ip_sol**: ionization potential in solution (eV)
5. **ea_gas**: electron affinity in the gas phase (eV)
6. **ea_sol**: electron affinity in solution (eV)
7. **EW_gas**: electrochemical window in the gas phase (eV)
8. **EW_sol**: electrochemical window in solution (eV)

## structures
Contains the optimized structure of the molecules used in the IP/EA dataset

## data
Contains the raw json files that the redox potential workflow in mispr produces after a redox calculation is completed