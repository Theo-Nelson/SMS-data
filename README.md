# Single-Molecule Sequencing Course Data

This repository provides access to datasets for the analysis and evaluation of DNA and RNA base modification detection using Oxford Nanopore Technologies' single-molecule direct RNA sequencing. 

Course Webpage: https://physiology.med.cornell.edu/faculty/mason/lab/clinicalgenomics/index.html <br>
YouTube Channel: https://www.youtube.com/@makethebrainhappy-scientificex 

## 📁 Available Datasets

### Basecalled Reads – Chr22 Subset (Dorado v1.0.0, All 8 Modifications)

This dataset includes reads aligned to **chromosome 22**, basecalled with **Dorado v1.0.0** using multi-modification models supporting the following modified bases:

- **m5C, 2′-O-methylcytidine (2OMeC)**
- **Inosine, m6A, 2′-O-methyladenosine (2OMeA)**
- **Pseudouridine (pseU), 2′-O-methyluridine (2OMeU)**
- **2′-O-methylguanosine (2OMeG)**

This data includes both **HEK293T Total RNA** and **in vitro transcribed (IVT) RNA** controls, processed and filtered for reads mapped to chromosome 22.

📦 **Download link (Box folder):**  
[HEK293T chr22 Dorado v1.0.0 basecalled reads with 8 modifications](https://wcm.app.box.com/folder/324146793020?s=01knrh5f4xon37wh2f21d3ddu6v6hgda)

📄 **Associated preprint:**  
Singh et al. (2025). _"Direct detection of multiple RNA base modifications in native RNA with nanopore sequencing."_  
[bioRxiv: 10.1101/2025.02.03.636352v1](https://www.biorxiv.org/content/10.1101/2025.02.03.636352v1)

---

### 🧬 Genome in a Bottle (GIAB) RNA002 Dataset – Direct RNA Sequencing

This dataset contains **Oxford Nanopore direct RNA sequencing** data generated by the Genome in a Bottle consortium (NIST) with the RNA002 direct-RNA protocol. The data supports benchmarking and development of tools for **transcriptome analysis**.

Data includes **pass reads (FAST5)** hosted on the ENA and **fail reads with metadata** hosted on Zenodo. Samples represent multiple biological replicates and cell types, processed across different years.

#### 🔗 Project Accession
- **European Nucleotide Archive (ENA):**  
  [PRJEB90085 – Genome in a Bottle RNA002](https://www.ebi.ac.uk/ena/browser/view/PRJEB90085)  
  (Includes raw pass FAST5 files)

#### 📊 Sample Links (Zenodo)

**2023 Samples:**
- [Sample 1 – HEK293T (2023)](https://doi.org/10.5281/zenodo.15619903)
- [Sample 2 – HEK293T (2023)](https://doi.org/10.5281/zenodo.15619978)
- [Sample 3 – HEK293T (2023)](https://doi.org/10.5281/zenodo.15635264)
- [Sample 4 – HEK293T (2023)](https://doi.org/10.5281/zenodo.15635353)
- [Sample 5 – HEK293T (2023)](https://doi.org/10.5281/zenodo.15635165)

**2022 Samples:**
- [NA24143 (2022)](https://doi.org/10.5281/zenodo.15644497)
- [NA27730 (2022)](https://doi.org/10.5281/zenodo.15644545)
- [Reference Control Sample (RCS, 2022)](https://doi.org/10.5281/zenodo.15644519)

Each Zenodo link contains:
- `fast5_fail/` – Raw reads that failed default quality filters
