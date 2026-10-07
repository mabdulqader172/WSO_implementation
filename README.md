# WSO Implementation

The following respository is a minimal implementation of Weighted Sequence Order as defined by Abdulqader and Muñoz in our publication ***Physics-based prediction of protein folding and unfolding rates: Examining the roles of fold topology and core packing***.

## File Structure
The repository has the following file structure:
```
WSO_implementation/
├─ data/
│  ├─ PDB/
│  ├─ fold_kinetics_dataset.csv
├─ notebooks/
│  ├─ implementation.ipynb
├─ .gitignore
├─ environment.yml
├─ README.md
```
All PDB data is located in `PDB` along with the dataset used for this study `fold_kinetics_dataset.csv`. 

## Installation

Ensure Git and Conda are installed. Clone the repository, navigate to its directory, and create and activate the environment using the provided YAML file:
```bash
git clone https://github.com/mabdulqader172/WSO_implementation.git
cd WSO_implementation
conda env create -f environment.yml
conda activate wso
```

## Citing
Please Cite the following publication if this impelmentation or WSO is used in your work:
>Abdulqader M, Muñoz V. Physics-based prediction of protein folding and unfolding rates: Examining the roles of fold topology and core packing. Protein Science. 2026; 35(8):e70705.https://doi.org/10.1002/pro.70705