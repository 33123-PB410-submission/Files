# PB410 Files for submission

Hello! This is a short introduction to the files available via this GitHub repository. The following files are available: 

## Corpora study 1&2
An Excel file containing the meta data and URLs for the articles selected for study number 1 and 2 (ch. 4.1 and 4.2 in the paper). The 'Study 1' sheets contain the themes that each article was assigned. The 'Study 2' sheets contain the number of comments that was downloaded from each article. 

## Corpora study 3
An Excel file containing the 'best rated' comments selected for study 3, in conjunction with the same meta data listed in 'Corpora study 1&2', as well as the themes that each article was assigned. 

## Guardian full comment data
This CSV file contains the comments which were scraped from The Guardian's articles specified in 'Corpora study 1&2'. 

## DM full comment data
This CSV file contains the comments which were scraped from The Daily Mails's articles specified in 'Corpora study 1&2'. 

## DDR-master
This is a repository containing the code to execute DDR from [Garten et al. (2018)](https://link.springer.com/article/10.3758/s13428-017-0875-9). Since the available code was written to be compatible with Python 2.0, some code was adapted to be compatible with the current latest version of Python (3.9.7). 

## DDR Execution file (Python)
In order to run the DDR code, this file contains the necessary code to do so. All file paths have been anonimysed, and will need to be defined by any subsequent user themselves in order to run the code. The output will be a tab-separated values file (tsv). 

* The Word2Vec file is not provided, as it was ca. 3GB and therefore too large to upload. Please use the following link instead to download the Word2Vec model: https://code.google.com/archive/p/word2vec. The downloaded model should be stored in the same master file (i.e., DDR-master) to make the code work. 

## Document dictionary loadings Guardian
The outputs from DDR (i.e., the document dictionary loadings) provided too big of a file to upload to GitHub, therefore only the subsets of the (Guardian) data which were quantitatively analysed as well as the descriptive statistics results which were run on these subsets are laid out in the worksheets of this Excel file. 

## Document dictionary loadings DM
The outputs from DDR (i.e., the document dictionary loadings) provided too big of a file to upload to GitHub, therefore only the subsets of the (Daily Mail) data which were quantitatively analysed as well as the descriptive statistics results which were run on these subsets are laid out in the worksheets of this Excel file. 

## Within Guardian t-test
This Excel file contains the results of the Wilcoxon's t-tests which were run on The Guardian's document dictionary loadings. The results pertain to the full data sets (i.e., document dictionary loadings). No t-tests were run on any subsets of the data. 

## Within DM t-test
This Excel file contains the results of the Wilcoxon's t-tests which were run on The Daily Mail's document dictionary loadings. The results pertain to the full data sets (i.e., document dictionary loadings). No t-tests were run on any subsets of the data. 

## Guardian vs. DM t-test
This Excel file contains the results of the Welch's t-tests which were run to compare the document dictionary loadings of The Guardian with those of The Daily Mail. The results pertain to the full data sets. 
