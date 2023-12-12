# DSC180AQuarter1Project

The notebook "DSC180AQ1Project.ipynb" contains code to prepare gene expression for analysis, perform cis-eQTL, create LocusZoom plots, and a pipeline for PRS generation.

Run the following wget commands, then unzip the data. These are necessary to run the notebook.

```
wget -O GD462.GeneQuantRPKM.50FN.samplename.resk10.txt.zip https://drive.google.com/file/d/1ugiWccCtoF7Ccx5-8Fn4nfvL1NJ-PuSr/view

wget -O eqtl_results.csv.zip https://drive.google.com/file/d/1qIw_hQ1WqClbOeb_xoB2kv0KWyW_Ht9n/view

wget -O 1000G.EUR.22.vcf.zip https://drive.google.com/file/d/1W8rcC6_pEVbVuFHZb0iWqwss0Ud509u5/view

unzip GD462.GeneQuantRPKM.50FN.samplename.resk10.txt.zip

unzip eqtl_results.csv.zip

unzip 1000G.EUR.22.vcf.zip
```

Command line calls within the notebook use `Plink2.0`, a free, open-source whole-genome association analysis toolset. Download the executable at this link: https://www.cog-genomics.org/plink/2.0/ and place the file in the working directory. In the notebook, to run the Plink2.0 calls, replace the "<PATH TO PLINK EXEC>" tags with the path to the Plink executable on your device.

Notebook dependencies include `numpy`, `statsmodels`, `matplotlib`, `seaborn`, `pandas`, and `PyPlink`. If required, install the dependencies using `pip install <packagename>` commands.

Following the retrieval of the data, open the jupyter notebook and run the cells in order. Explanations for what each cell does are provided in the comments within the code.
