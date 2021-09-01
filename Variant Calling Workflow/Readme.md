# Variant Calling Workflow 

The variant calling workflow step was utilize to get Single Nucleotide Polymorphisms (SNPs) in the genomic sequences.

This is done by aligning and comparing the dataset sequences to Reference Wuhan Sequence (NC_045512.2).

## The tool used for this workflow is: **[Mummer 4.0](https://github.com/mummer4/mummer)**

To reproduce `nucmer.snp` we needed to align the sequences with Nucmer (a part of the Mummer toolkit):
```
nucmer -g 500 -c 400 -l 20 -p nucmer <reference sequence> <query sequence>
```
Get the SNPs using Nucmer's show-snps command:
```
show-snps -Tr nucmer.delta <output of the nucmer alignment> > nucmer.snp
```
### Analysis and Processing is done on `Nucmer Preprocessing.ipynb`  to get `filteredvariantcalling.csv` for concatenation and processing.  