# DNA Sequence Analyzer

Analyzes DNA sequences from FASTA files.

- Loads DNA sequences from FASTA format
- Counts nucleotide frequencies (A, T, C, G)
- Calculates GC content
- Finds sequence motifs (like ATG start codons)
- Visualizes nucleotide distribution

## Results from sample data

Using an E. coli gene (3,075 nucleotides):
- **GC Content:** 56.26%
- **ATG occurrences:** 58
- **Nucleotide counts:** A=678, T=667, C=842, G=888

### K-mer Analysis
- Implements k-mer counter for any k value
- Visualizes k-mer frequency distribution
- Compares k-mer statistics across different k sizes
- All 64 possible 3-mers found, ranging from 6-103 occurrences

## Tools used

- Python 3
- Biopython
- Matplotlib


## Sample output

Nucleotide Frequency Chart
<img width="888" height="587" alt="image" src="https://github.com/user-attachments/assets/c0c38eb9-cb58-4309-91f8-d28ee6f244da" />
