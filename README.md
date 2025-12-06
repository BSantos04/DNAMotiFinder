# MotiFinder
This repository contains a python script that searches for a motif in a FASTA file containing nucleotide biological sequences, displaying all the locations of that specific motif in the sequences.
# Requirements
- Python >= v3.6
# Installation
`git clone https://github.com/BSantos04/Finding_DNA_Motifs.git` 
# Tutorial
`python3 {path/to/script.py} {path/to/sequences/file.fasta}`
## Example
`python3 ~/Finding_DNA_Motifs/Finding_DNA_Motifs.py sequences.fasta`

"Enter the motif you want to find:" `{motif} (e.g.: 'ATCGCG')`
## Path to the Script
Example: `~/Finding_DNA_Motifs/Finding_DNA_Motifs.py` or, if you are already in the working directory, just `Finding_DNA_Motifs.py`.
## Motif 
A DNA sequence containing only IUPAC nucleotides (A, T, C, G) with at least 5 bp length.
# License
GNU General Public License V3.0
