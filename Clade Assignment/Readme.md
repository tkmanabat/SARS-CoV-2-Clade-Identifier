# Clade Assignment
The clade assignment workflow step was utilize to assign SARS-CoV-2 clades to the genomic seqeunces by viral genome alignment, mutation calling, quality checks and phylogenetic placement. 

## The tool used for this workflow is: **[Nextclade CLI v 1.2.3](https://github.com/nextstrain/nextclade)**

To reproduce `nextclade.tsv` we needed to run the Nextclade CLI to the dataset sequences:
```
nextclade --input-fasta=<query sequence> --input-root-seq=<reference sequence> --input-tree=<nextclade tree file> --input-qc-config=<nextclade qc file> --output-tsv=nextclade.tsv
```
*  The Tree and QC config file can be found on [Nextclade's Github repository](https://github.com/nextstrain/nextclade/tree/master/data/sars-cov-2).
 
### Analysis and Processing is done on `Nextclade Preprocessing.ipynb`  to get `filteredcladecalling.csv` for concatenation and processing.  