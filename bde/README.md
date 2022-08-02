
## bde.csv
Contains the BDE results (eV) of the molecules in the BDE dataset at the ωB97X/def2-TZVP level 
of theory in the gas phase. 
The column names correspond to the following:
1. **bond**: bond number 
2. **inchi**: inchi representation of the principle molecule
3. **smiles**: smiles representation of the principle molecule
4. **frag1**: smiles representation of the first fragment
5. **frag2**: smiles representation of the second fragment 
6. **comp**: the computed BDE (eV)
7. **exp**: the experimental BDE (eV) from the iBond database 
8. **exp_err**: the experimental BDE uncertainty (eV) from the iBond database
9. **error**: the absolute error between the computed and experimental BDE (eV)

## structures
Contains the optimized structure of the principle molecules used in the BDE dataset

## data
Contains the raw json files that the BDE workflow in mispr produces after a BDE calculation is completed

