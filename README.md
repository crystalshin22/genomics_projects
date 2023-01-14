# Genomics Projects

Most of these projects have been completed as a class project under the supervision of Professor Wei-Yi Cheng for his course on Introduction to Genomics and Information Science at Columbia University. All of the code is either completely mine or modified after receiving instructor feedback. <br>

All data files have been provided by the course instructor and can be accessed [here](https://drive.google.com/drive/folders/19Ma2yj605qYQiXjZtNaJkfohv6ZXfJhr?usp=share_link) on request. <br>

The repository is constantly updated as I complete more class/personal projects.<br>

## Outline of Projects

- **Biomarker Identification - Mirdametinib** [[code]](https://github.com/crystalshin22/genomics_projects/blob/main/Biomarker%20Identification%20-%20Mirdametinib.ipynb)
    - Summary: Identified different biomarkers that have led to the discovery of Mirdametinib using approaches illustrated in [Barretina et al.](https://www.nature.com/articles/nature11003) paper. Used machine learning models to shortlist features that are of highest important.
    - Tools: sklearn `RandomForestRegressor`, MAF files, CCLE mutation data

- **NBL Analysis 1 - Identifying Risk-Associated Mutations** [[code]](https://github.com/crystalshin22/genomics_projects/blob/main/NBL%20Analysis%201%20-%20Identifying%20Risk-Associated%20Mutations.ipynb)
    - Summary: Studied the genomic data of neuroblastoma (NBL) samples to identify predictive mutations and gene expression features
    - Tools: Fisher's exact test, MAF files

- **COVID Spark Protein Alignment** [[code]](https://github.com/crystalshin22/genomics_projects/blob/main/COVID_Spark_Protein_Alignment.ipynb)<br>
    - Summary: Performed a multiple sequence alignment of different COVID-19 spark protein sequences, created a phylogenetic tree of the different variants, and assigned variant identities
    - Tools: Biopython, Ipytree, MAFFT, FASTA files
    
- **Prostate Cancer Risk Screening Using Germline Variant Data** [[code]](https://github.com/crystalshin22/genomics_projects/blob/main/Prostate%20Cancer%20Risk%20Screening%20Using%20Germline%20Variant%20Data.ipynb)<br>
    - Summary: Identified pathogenic germline variants from 'Clinvar' clinical variants database that could lead to prostate cancer and screened 1000 genome project dataset to check if the subjects carry those specific variants associated with high risk of prostate cancer
    - Tools: scikit-allel, VCF, Zarr files

- **Calculating Mutation Load Using TCGA Breast Cancer Dataset** [[code]](https://github.com/crystalshin22/genomics_projects/blob/main/Calculating%20Mutation%20Load%20Using%20TCGA%20Breast%20Cancer%20Dataset.ipynb)
    - Summary: Investigated how damages in mismatch repair pathway could affect the number of mutations, also known as mutation load, in breast cancer.
    - Tools: MAF files, Mann-Whitney U test
    
