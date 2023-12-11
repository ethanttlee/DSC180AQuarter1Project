# DSC180AQuarter1Project

Run the following wget commands for all of the data, then unzip the data. These are necessary to run the notebook.

```
wget -O GD462.GeneQuantRPKM.50FN.samplename.resk10.txt.zip https://drive.google.com/file/d/1ugiWccCtoF7Ccx5-8Fn4nfvL1NJ-PuSr/view

wget -O eqtl_results.csv.zip https://drive.google.com/file/d/1qIw_hQ1WqClbOeb_xoB2kv0KWyW_Ht9n/view

wget -O 1000G.EUR.22.vcf.zip https://drive.google.com/file/d/1W8rcC6_pEVbVuFHZb0iWqwss0Ud509u5/view

unzip GD462.GeneQuantRPKM.50FN.samplename.resk10.txt.zip

unzip eqtl_results.csv.zip

unzip 1000G.EUR.22.vcf.zip
```

Notebook dependencies include `numpy`, `statsmodels`, `matplotlib`, `seaborn`, `pandas`, and `PyPlink`. If required, install the dependencies using `pip install <packagename>` commands.

Following the retrieval of the data, open the jupyter notebook and run the cells in order. Explanations for what each cell does are provided in the comments within the code.
