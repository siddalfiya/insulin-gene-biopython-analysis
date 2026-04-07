# insulin-gene-biopython-analysis
Beginner Bioinformatics Project: DNA sequence analysis of human insulin gene using Biopython
# Insulin Gene Analysis using Biopython

**Beginner to Intermediate Bioinformatics Project**  
DNA sequence analysis of the human insulin (INS) gene using Biopython.

### Project Overview
This project demonstrates practical sequence analysis of the human insulin gene — a classic example in bioinformatics due to its medical importance (diabetes, hormone biology). 

The analysis covers:
- Retrieval of the gene sequence from NCBI
- Basic sequence statistics (length, GC content, molecular weight)
- Translation to protein sequence
- Identification of open reading frames (ORFs)
- Codon usage analysis
- Simple motif search (e.g., signal peptide region)
- Comparative analysis with insulin genes from other species (mouse, rat, chimpanzee)

### Technologies Used
- Python 3
- Biopython
- Matplotlib / Seaborn (for visualization)
- Pandas (for tabular results)

### Key Analyses Performed

1. **Sequence Retrieval & Statistics**
   - Fetched human INS gene (NCBI Reference Sequence)
   - Calculated length, GC%, AT%, molecular weight

2. **Protein Translation & Features**
   - Translated DNA → Protein
   - Identified the preproinsulin, proinsulin, and mature insulin regions
   - Calculated protein properties

3. **Open Reading Frame (ORF) Analysis**
   - Found all possible ORFs
   - Highlighted the longest biologically relevant ORF

4. **Comparative Genomics**
   - Compared human insulin gene with orthologs from mouse, rat, and chimpanzee
   - Calculated pairwise sequence identity
   - Basic phylogenetic insight

5. **Visualization**
   - GC content plot
   - Codon usage bar chart
   - Sequence length comparison across species

### Repository Structure


