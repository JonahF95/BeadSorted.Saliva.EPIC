# BeadSorted.Saliva.EPIC

The **BeadSorted.Saliva.EPIC** data package contains publically available Illumina human methylation data from EPIC saliva samples assayed by Middleton and colleagues (manuscript submitted). It includes an RGChannelSet, a comparison table with degree of association between cell type and samples, and cell proportion estimates within our samples as calculated by the ewastools implementation of the Houseman algorithm. This dataset is novel for cell proportion estimations in saliva and may be useful to end users for estimating and controlling for cell-type heterogeneity in their study samples.

For the purposes of consistency and convenience to the end user, this package is designed to be structurally similar to similar packages, including the **FlowSorted.Blood.EPIC** package after which it is generally modeled.

This package can be implemented through Bioconductor with the FlowSorted.Saliva.EPIC package: https://bioconductor.org/packages/release/data/experiment/html/BeadSorted.Saliva.EPIC.html

## Citation Information
Middleton LYM, Dou JF, Fisher J, Heiss JA, Nguyen V, Just AC, Faul JD, Ware EB, Mitchell C, Colacino JA, Bakulski KM. 2021. Saliva cell type DNA methylation reference panel for epidemiology studies in children. Epigenetics. PMID: 33588693, PMCID: PMC8865319. 

Data can be accessed through the Genome Expression Omnibus: GSE147318
