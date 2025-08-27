---
tags:
  - protocol
  - dna
category: dna
---
# Site Directed Mutagenesis

**Last Updated**: 2023-07-21 (not done yet)
**Authors**: Max

## Introduction
How to design a primer for introducing a mutation in a gene via PCR. Followed by [[2004Zheng]]. 

## Material and Equipment

## Procedure

#### Primer Design
1. get gen[[2004Zheng]]
2. identify aa you want to change and how you want to change it
3. identify common codons in the gene for the aa you want to introduce! and use this one if possible. (Some codons are more frequent in a gene, and since we usually use codon optimised plasmids, if we take from the plasmid we are sure not to pick a rare one by accident.)
**FORWARD**:
4. start from mutation and elongate for10 to 15 bases to the 3'end and ca. 6 bases in 5'end
5. Check Tm, chew away both ends until Tm around 68 to 72. Keep at least 8 to 7 at the 3' and at least 4 to 5 at the 5'
6. try to end sequence on C or G

**BACKWARD**:
(keep in mind that you need to use now corresponding bases and revers direction (always write sequences from 5' to 3'))
6. start from mutation and elongate for 6 bases to the 3'end (5' end in original sequence) and ca. 15 bases in 5'end (3' end in original sequence)

7. [check annealing temperatures](https://tmcalculator.neb.com/#!/main) (best in a range from 68 to 72 °C) (if to high try to shorten sequence, if to low, try to elongate sequence, we usually use Phusion Polymerase)
8. check for hairpin and other problems, [here](https://en.vectorbuilder.com/tool/dna-secondary-structure.html)
9. Order primers!

ideal GC content 40 to 60 %
$\Delta G$ for hairpin okay if absolute value smaller -5 kcal/mol
(dimerization can be ignored for this technique)

While waiting for primers check for/make: LB-Agarose plates, LB medium, competent cells, Plasmid Mini Prep Kit, DpN1, Phusion Polymerase

#### Lab work
1. Dissolve primer accordingly. (You should get a sheet of paper where its says how much water etc.)
2. Start with a standard PCR mixture like so... (if it doesn't work, play around with DMSO content, cycling protocol etc.)


3. Shortly before starting the program, add the polymerase. Place PCR tubes in the cycler. Run program.
4. Afterwards, incubate with DpN1 (1µL each PCR tube is enough), for 1 to 2 h at 37 C, heat inactivate.
5. Run agarose gel to evaluate if you have PCR product in the appropriate size.
6. Transform competent E. coli of choice. For not yet closed plasmids I would recommend to go the extra mile and use DH5aplha.
7. After successful transformation, collect purify plasmid, with Mini Prep kit.
8. Send plasmid for sequencing.
**Done!** Good job!

## Notes