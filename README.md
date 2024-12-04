# whatsmissing
 A python program to find missing residues and missing atoms in the PDB files. 

### Background
Knowledge of missing regions, residues, or atoms in PDB structure is very important. In molecular dynamics simulations, information about missing atoms or residues is crucial for successful execution. Missing residues and atoms might lead to erroneous outcomes or hinder the execution of simulations. Therefore, it is reasonable to check the PDB structure for missing information. The header section in the PDB structure contains all the necessary information about the structure. However, reading the headers is a bit of a tiresome task. This Python program helps you find information about missing residues and atoms in your PDB files. This is easy to run, and results are provided in a simple format. 
 

### Installation
```
git clone https://github.com/abuturabnaqvi/whatsmissing.git
cd whatsmissing
```

### Usage 
To run the application with your structure files, you will need to download the file from [RCSB PDB](https://www.rcsb.org/) databank. Make sure to download the PDB file in mmCIF format. Keep the PDB file in the same directory as the application. 
```

python whatsmissing.pyc example (To run the example file)

python whatsmissing.pyc [YOUR PDB ID] 

```
> [!NOTE]
> Provide the PDB ID (4-letter code) without extension (i.e., .cif).

### Output
The program generates a text file with the information of the number of missing residues/atoms and details of missing residues/atoms in tabular format. 

![Output Format](https://github.com/abuturabnaqvi/whatsmissing/blob/main/output.png)


