# SynConNet
Related code for "High-resolution human contact networks in thirteen countries for infectious disease transmission"

## 1. Install SynthPops  
We recommend installing [SynthPops](https://github.com/synthpops/synthpops) before running the code to support the generation of contact networks. Please follow the instructions in the repository for installation.

## 2. Replace Files  
After installing SynthPops, copy the JSON files from the `location` directory into the `synthpops/data` directory. Then, replace the existing `defaults.py` in the `synthpops/` root directory with the provided version.

## 3. Contact Network Generation  
The `ConNetGen.ipynb` notebook includes contact network generation code for 13 countries. The generated contact networks and individual attributes are saved in the `net` and `pop` directories, respectively. We provide 30 sample contact networks for the US as a demo.

## 4. Validation & Visualization  
A detailed set of contact network results, intermediate data, and the validation process are provided in the `validation.zip` archive.
