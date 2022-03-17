**database_pubchem.ipynb**

This script calculates descriptors for a subset of PubChem molecules. PubChem is a database that contains information on 111 million chemical molecules and their activities in biological assays. Subsets of compounds  can be obtained using a filtered search or a specific data source (https://pubchem.ncbi.nlm.nih.gov/source/). The 13575 compounds submitted to PubCHem by DrugBank (PubChem_drugbank.csv) are used as an example. This notebook cleans the data, calculates Mordred (QSAR) descriptors, and performs UMAP dimensionality reduction. The resulting dataset can be used for a variety of applications, for example see drugbank_umap.ipynb


**database_chembl.ipynb**

The aim of this script is to identify biologically active compounds for a target protein/organism of interest. The script extracts information from the ChEMBL database, which is a manually curated collection of ~2 million bioactive molecules. The last section contains code to extract information from ChEMBL for a particular molecule.
