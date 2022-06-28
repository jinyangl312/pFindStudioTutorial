# Search

## Lecture
For the search by pLink 2, you can refer to the last part (starts from 29:10) of the fifth lecture of [CNCP系列公开课：《计算蛋白质组学》](https://www.bilibili.com/video/BV15A411c7jh?p=5) (in Chinese), where the main devoloper of pLink 2 Zhenlin Chen teaches you how to use the software.

### Additional information for parameters

**MS Data**

Place of Decimals: the precision of MS data.

Precursor Score: parameters for pParse 2.

By clicking "Mixture Spectra" we allow the detection of multiple results from one spectrum.

**Identification**

Flow Type: supports conventional crosslinking (HCD mode) and Disulfide Bond (HCD mode). Choose the former one for the search of conventional crosslinker and the latter one for the search of disulfide bond.

Process Number: the allowed number of CPU process for the task. Do not recommend the number to be greater than the total number of logical CPU process of the computer.

Add a database: by clicking "Customize Database", pConfig will be called for adding a new database. Click "Add" in pConfig, browse and select a fasta database, rename the database, and click "Save" before close pConfig. By clicking "Add contaminant" we add common contaminant that sometimes occur during the preparation of the sample.

Fixed modifications: fix the modification to all of certain kind of amino acid.

Variable modifications: consider at most three sites in each sequence to have a modification listed in the variable modifications.

By clicking "Compute E-value", pLink will calculate the expetation value for every result. As it is time-consuming, by default it is unchecked.

### FAQ

If you meet any problem, visit [http://forum.pfind.org/forum](http://forum.pfind.org/forum) to read frequently asked questions or ask us directly.

## Homework

Download the dataset (XLpeplib_Beveridge_QEx-HFX_DSS_R1-3) attached to the article [A synthetic peptide library for benchmarking crosslinking-mass spectrometry search engines for proteins and protein complexes](https://www.nature.com/articles/s41467-020-14608-2/) as well as fasta file from [uniprot](https://www.uniprot.org/downloads) and try to use pLink 2. The link of the dataset occurs in **Data availability** section. Note that you should download with FTP, otherwise [the raw file may be corrupted](http://forum.pfind.org/forum/issue73).

After watching it, you may try to answer the following questions:

How to employ a database search with pLink 2?

How to check the identified cross-linked spectra in the .csv file? What about cross-linked peptides and sites?

How to read the peptide-spectrum match details with pLabel?
