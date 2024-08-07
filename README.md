# VASP (Vienna Ab initio Simulation Package) Scripts
More about VASP [here](https://www.vasp.at/)

## Features
- Initial structure gen for **POSCAR** and KPOINTS (POTCAR, INCAR, KPOINTS, and job file (.slurm) will need to be provided in the templates folder) 
- OSZICAR plotter (Y v.s. steps)
- Adsorption energy calculator
- Bond length calculations between atom pairs
- HTML webpage generation with data and important previews
- More to come

### Functions
- Freezing bottom two layers of atoms (can be modified to freeze bottom *n* layers)
- Simulation folder generation from the template folder
- Slabs, molecules, and atom manipulation (Adsorbates on a slab, Atom/Molecule in a vacuum, Vacancy on a slab)
- More to come

## HTML output example
![image](https://github.com/EDED2314/VASP-scripts/blob/main/HTML%20Output%20Example%207.16.24.jpg)

## Graph output example

### Coming soon (feature already done... don't know if I can upload the actual graph though)

## Local Workspace Reference Tree
```
.
├── H
│   ├── 1stLayer
│   │   ├── O0
│   │   ├── O1
│   │   ├── O2
│   │   └── P0.0
│   └── 2ndLayer
│       ├── O0
│       ├── O1
│       ├── O2
│       ├── O3
│       ├── O4
│       └── O5
├── H2O
│   ├── V-O0-OD
│   ├── V-O1-OD
│   ├── V-O2-OD
│   └── V-P0.0-OD
├── N2
│   ├── V-O0-UPR
│   ├── V-O1-UPR
│   └── V-O2-UPR
├── POSTOUTPUT
├── adsorbates
│   ├── H
│   ├── H2
│   ├── H2O
│   └── N2
├── data
├── images
│   ├── H_CONTCAR
│   │   ├── Avg-O014
│   │   ├── Avg-O235
│   │   ├── O0
│   │   ├── O1
│   │   ├── O2
│   │   ├── O3
│   │   ├── O4
│   │   ├── O5
│   │   ├── W0
│   │   ├── W1
│   │   └── W2
│   └── H_POSCAR
│       ├── Avg-O014
│       ├── O0
│       ├── W0
│       └── W1
├── notebooks
├── surface
├── surface_v
│   ├── O0
│   ├── O1
│   └── O2
├── surface_x2y2
├── templates_W001
├── templates_W001_x2y2
└── templates_adsorbate
```
## Super Computer Workspace Reference Tree
```
.
├── ads
│   ├── H
│   │   ├── 1stLayer
│   │   │   ├── O0
│   │   │   ├── O1
│   │   │   ├── O2
│   │   │   └── P0.0
│   │   └── 2ndLayer
│   │       ├── O0
│   │       ├── O1
│   │       ├── O2
│   │       ├── O3
│   │       ├── O4
│   │       └── O5
│   ├── H2O
│   │   ├── V-O0-OD
│   │   ├── V-O1-OD
│   │   ├── V-O2-OD
│   │   └── V-P0.0-OD
│   └── N2
│       ├── V-O0-UPR
│       ├── V-O1-UPR
│       └── V-O2-UPR
├── surface_v
│   ├── O0
│   ├── O1
│   └── O2
└── vac
```
