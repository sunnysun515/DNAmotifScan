# DNAmotifScan

This script scans through an input sequences and looks for possible TF binding sites based on motifs.
The motifs are provided as Position Weighted Matrix (pwm).
The sequece is provided in fasta format.

Examples are included.

### Create sequences file
`python -m seqFinder -q <path_to_csv_file> [-f path_to_fasta_file]`


### Find motifs
`python -m motifFinder`
