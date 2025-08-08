# How to get the data

This example uses the WASP-39b data reduced by [Carter et al. (2025)](https://www.nature.com/articles/s41550-024-02292-x), 
which needs to be downloaded from [Zenodo](https://zenodo.org/records/10161743). First, download the data at 

https://zenodo.org/records/10161743/files/ERS_DataSynthesis_Zenodo.zip?download=1

and then unzip the file under the `data` directory. This can be done with the following commands:

    wget https://zenodo.org/records/10161743/files/ERS_DataSynthesis_Zenodo.zip?download=1 -O w39.zip
    unzip w39.zip

Note that the file is quite large (1.7 GB), so the download may take a while. If disk space is an issue, you can delete 
the `data/ZENODO/2_WHITE_LIGHT_CURVES/priors-and-posteriors/_dynesty_DNS_posteriors.pkl` file that takes 1.3 GB and is 
not needed for this example.

