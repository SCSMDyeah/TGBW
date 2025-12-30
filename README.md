# TGBW

TGBEDriver should be run under the environment of python >=3.7.



Operation steps:



1.Run python data\_process.py BRCA(cancer data folder)



The output of data\_process.py is 4 files after preprocessing: exp.txt, mut.txt, CPDB.txt(the corresponding processed PPI file), mut\_driver.txt.

2.Run TGBW-train.py BRCA



The output of TGBW-train.py is a matrix of gene score of samples



3.Run python EPV.py BRCA



The output of EPV.py is gene ranking.

