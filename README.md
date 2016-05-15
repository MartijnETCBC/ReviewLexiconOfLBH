## An Alternative Approach to the Lexicon of Late Biblical Hebrew

by Robert Rezetko and Martijn Naaijer (m.naaijer@vu.nl)

Welcome to this repository. Here you can find all the information about our analysis of the items in the Lexicon of Late Biblical Hebrew by Avi Hurvitz. 
You can copy the data and recalculate what we have done, you can do your own analyses using our dataset and if you want, you can change the data or add data to it. 
If you want to publish analyses using our datasets, please refer to this repository and to the article:

Rezetko, R., Naaijer, M., ‘An Alternative Approach to the Lexicon of Late Biblical Hebrew’, Journal of Hebrew Scriptures, Volume 16, Article 1, DOI:10.5508/jhs.2016.v16.1 .
 
We preprocessed the data using Jupyter Notebook, the visualizations were made with R. For a small part of the analyses we used Laf-Fabric. This is a tool for data analysis of the Hebrew Bible, which was developed by Dirk Roorda as part of the SHEBANQ project (shebanq.ancient-data.org).

The repository contains the following files and scripts:

* LexiconHurvitzDataset.csv
* spanish_words.csv
* preprocess_lexicon_lbh.ipynb
* r_scripts_pics.txt

The article is based on the data in LexiconHurvitzDataset.csv, which you can also find at DANS: http://dx.doi.org/10.17026/dans-256-4hcy
The columns in the dataset are explained in the article (pp. 4-5).
In the article two figures (47 and 48) are based on the file spanish_words.csv.

The file preprocess_lexicon_lbh.ipynb consists of a number of Python scripts having LexiconHurvitzDataset.csv as input and some
new files as output. These output files are the input of the R-scripts in r_scripts_pics.txt, with which the figures in the articles were made.

