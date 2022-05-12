
## shifts.csv
Contains the <sup>13</sup>C and <sup>1</sup>H NMR chemical shifts (ppm) of the molecules in the NMR dataset at the ωB97X/def2-TZVP leve 
of theory in a chlorofom solvent using the PCM solvation model and referenced to tetramethyl silane (TMS).
The column names correspond to the following:
1. **num**: structure number 
2. **13C_sp**: index of the carbon atom in the molecule 
3. **13C_exp**: the experimental <sup>13</sup>C chemical shift (ppm) from literature or the SDBS database
4. **13C_comp**: the computed <sup>13</sup>C chemical shift (ppm)
5. **1H_sp**: index of the hydrogen atom in the molecule 
6. **1H_exp**: the experimental <sup>1</sup>H chemical shift (ppm) from literature or the SDBS database
7. **1H_comp**: the computed <sup>1</sup>H chemical shift (ppm)

## structures
Contains the optimized structure of the molecules used in the NMR dataset

## data
Contains the raw json files that the NMR workflow in mispr produces after an NMR calculation is completed

