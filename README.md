# Project-2
This project is the first Draft of my Prohject 2. 
The Scientific Question was: Is increased ACE2 gene expression in lungs of current smokers correlated with an increased risk of SARS-CoV-2 infection in adult current-smokers? 
The Scientific Hypothesis was: If current smokers have a higher ACE2 gene expression in lungs compared to nonsmokers, then their rate of SARS-CoV-2 infection per 100,000 (p-value<0.05) compared to nonsmokers will also be higher. 
Data: There are two input data files:1) Smoking_Data.xlxs 2) Seq_Data.fastq
The Smoking_Data.xlxs was compiled using various published studies, which are listed in the excel file along with the data extracted from the respective studies. 
The Seq_Data.fastq is a transcriptome dataset obtained from https://www.ncbi.nlm.nih.gov/sra?LinkName=biosample_sra&from_uid=2438364. The fastq file is 2.2 gb and unable to upload on Github, it can be downloaded directly from the following link: http://ftp.sra.ebi.ac.uk/vol1/run/ERR315/ERR315346/5_130103_AD1J0JACXX_P262_148D_index27_1.fastq.gz
A screenshot of the results from the t-test are attached and an analysis of the results is in R-notebook. 
Note: This project has only been partially completed. The first part of the project was to analyze is the smokers display a statistically significant difference in covid infection rates compared to non-smokers. The bio-bank data that was supposed to be used initially was not available publicly. Moreover, as I progressed with data analysis it became apparent that the covid infection rates comparison between smokers and non smokers was not that straightforward because of the types of data that were available publicly.  So to solve this problem, I tried to compare the percentage of smokers in the adult population with the percentage of smokers in the covid-positive patients. The percentage of smokers in the adult population although very variable depending on demographics, was assumed to be a constant and equal to  13.5%. Considerable amount of time was spent to extract the % of smokers in the Covid patients from a variety of studies and the data was extracted and listed in an excel file (Smoking_Data.xlxs). I was unable to complete the second part of the project successfully, which was to perform single cell rna sequencing. More information about these problems is given in the r-notebook file. 
To conclude, the data does show a statistically higher rate of SARA-COV-2 among smokers. The project is still work under progress



