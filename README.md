# Supplementary material to the manuscript: "RecA is a reliable marker for bacterial taxonomy, even in the Candidate Phyla Radiation"
In this repository, we have included custom scripts and data produced in the manuscript. Codes and data are organised in separate folders coherently with the flow of the manuscript. 

## Material stored in the repository
### Code:
- *1_RecA_CPR_core_gene_identification*: this section contains a bash pipeline to perform the sequence clustering analysis used to search for a core, single-copy protein marker in the CPR
- *2_Model_training_and_testing*: this section contains the scripts used to: 1) create a panbacterial RecA database; 2) count the kmers in the sequences; 3) the code used to train 
  and test the preliminary assignment models; 4) the code used to train and test the refined assignment models
- *3_Tool_evaluation*: this section contains the code used to compute the metrics of the forestax output
### Data:
- *1_RecA_CPR_core_gene_identification*: this section contains the metadata of the genomic dataset, the RecA global phylogenetic tree a folder with fasta sequences, alignments and 
  tree for each selected cluster in the refined CPR dataset
- *2_Model_training_and_testing*: this section contains the list of genomes used to train and test the random forest models, the metadata of the genomes (with info on number of RecA found),
  and the output files for the preliminary and refined taxa assignment models discussed in the manuscript.
- *3_Tool_evaluation*: this section contains the forestax output (at genus and species level), the expected output of the mock communities and the metrics comparison with other pipelines.
  
## Download the material
To download the material, run in the terminal:
```
git clone https://github.com/LodovicoSterzi/RecA_taxonomy_code_data
unzip "*.zip"
```
