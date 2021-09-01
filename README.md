<center><img src="Assets/DNA.gif" alt="drawing" width=50% height=50%/>
<br>
<h1> SARS-CoV-2-Clade-Identifier</h1></center>
This is the code repository for SARS-CoV-2 clade identifier with Single Nucleotide Polymorphisms (SNPs) data using machine learning.

A project of the Philippine Genome Center's 2021 Internship Program. 

## Setup 💻
To get started:
- Clone the repository
```
git clone https://github.com/tkmanabat/SARS-CoV-2-Clade-Identifier.git
```
- In order that to run the notebooks, all dependencies must be installed. We provided a list of dependencies in `requirements.txt`
``` 
pip install -r requirements.txt
```
- To open with Jupyter Notebook 
```
jupyter notebook
```


## Code Organization 🤹‍♂️
This repository is divided into five parts:
- **Dataset Gathering/**: contains steps on how SARS-CoV-2 sequences was collected/downloaded.
- **Variant Calling Workflow/**: contains information on was processing done to get the SNPs from the sequences. 
- **Clade Assignment/**: contains steps on how clade assignment and processing was done.
- **Concatenation and Data Preprocessing/**: contains the notebook for concatenating the SNPs from the variant calling workflow and the clade from the clade assignment workflow.
- **Machine Learning/**:  contains the machine learning models trained for this projects.

