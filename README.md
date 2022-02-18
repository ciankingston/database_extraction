**database_pubchem.ipynb**

PubChem is a database that contains information on 111 million chemical molecules and their activities in biological assays. The aim of this script is to calculate descriptors for sets of compounds within PubChem, which can be obtained through a filtered search or by focusing on a particular data source (https://pubchem.ncbi.nlm.nih.gov/source/). For example, his script was developed using the 13575 compounds submitted to PubCHem by DrugBank (PubChem_drugbank.csv). This notebook will clean the data, calculate Mordred QSAR descriptors, and perform UMAP dimensionality reduction. The resulting dataset can be used for a variety of applications and further manipulated e.g. see drugbank_umap.ipynb


**database_chembl.ipynb**

The primary aim of this script is to identify biologically active compounds for a target protein/organism of interest. The script extracts information from the ChEMBL database, which is a manually curated collection of ~2 million bioactive molecules. The second section of the script contains code to extract information from ChEMBL for a particular molecule.
