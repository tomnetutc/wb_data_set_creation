This GitHub repository provides information about the three wellbeing indicators that are used in the TOMNET wellbeing platform and the process for creating the final data set. The dataset_creation.ipynb Jupyter file contains instructions and code for generating the data set and using it. This version of the wellbeing platform uses data from the ATUS dataset from 2003 to 2021, but the code can be applied to any data set after 2021. Please note that the ATUS data files are not included in this repository due to file size limitations. To run the dataset_creation script, you will need the following [ATUS files](https://www.bls.gov/tus/data/datafiles-0321.htm), which should be placed in a folder called ats_03_21:
        - atus_03_21/atuscps_0321.dat
        - atus_03_21/atusresp_0321.dat
        - atus_03_21/atusrost_0321.dat
        - atus_03_21/atuswho_0321.dat
        - dataset_creation.ipynb