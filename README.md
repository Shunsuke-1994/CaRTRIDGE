# CaRTRIDGE
Code repository for "Programmable mammalian translational modulators by CRISPR-associated proteins"

# Requirements
- python > 3.3
- viennarna
- numpy
- pandas/openpyxl
- matplotlib/seaborn
- scipy

# Directories
```
CaRTRIDGE
├── LICENSE
├── README.md
├── datasets
│   ├── Crosstalk-ON.xlsx
│   ├── Orthogonal OFF-3.xlsx
│   └── gRNA list for MFE2.xlsx
├── notebooks
│   ├── calcMFE.ipynb
│   └── orthogonality_check.ipynb
└── outputs
    └── gRNA list for MFE2_RNAfold.xlsx
```
- `datasets/Crosstalk-ON.xlsx` : normalized fold change information of on-switches.
- `datasets/Orthogonal OFF-3.xlsx` : normalized fold change information of off-switches.  
- `datasets/gRNA list for MFE2.xlsx` : sequences of switches used for MFE calculation.  

# Reference
Kawasaki, S., Ono, H., Hirosawa, M., Kuwabara, T., & Saito, H. (2021). Programmable mammalian translational modulators by CRISPR-associated proteins. bioRxiv.
