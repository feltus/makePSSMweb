# Computational Practice: Building a PSSM from a MSA

##  Lab Overview
Multiple Sequence Alignment (MSA) is an extension of pairwise alignments where one aligns multiple related sequences to achieve optimal matching of the sequences.
A Position Specific Scoring Matrix (PSSM) is a log-odds matrix that contains the probability information of residues at each position in an ungapped multiple sequence alignment.  It’s like a substitution matrix with positional constraint.   New sequences can be scored for a possible match to a PSSM.

##  Lab Objectives:
In this lab, you will go from raw sequences to a position specific scoring matrix (PSSM).

•	Perform a T-COFFEE multiple sequence alignment (MSA)
•	Convert the MSA into a PSSM
•	Score a sequence using your PSSM

Follow these lab instructions:

###  Task A: 
Make a multiple sequence alignment.
Here are 5 DNA sequences: ATATTAGC, ATAGTAGC, ATACTACC, ATATTAGC, AGATTAGC
#### Step 1. 
Convert these sequences into single FASTA format text file.

#### Step 2.
Perform a T-Coffee multiple sequence alignment (MSA) on the 5 sequences below using the European Bioinformatics Institute MSA server https://www.ebi.ac.uk/jdispatcher/msa ).

#### Step 3. 
Paste the MSA into a text file.

#### Step 4. Make an Excel spreadsheet.   
Build a position specific scoring matrix (PSSM) from the above MSA in the spreadsheet.  Use the add-one rule. 

#### Step 5. 
What is the score of this sequence (AGATGACC) using the above PSSM as the scoring system?  Place in your spreadsheet.
