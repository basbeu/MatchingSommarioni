# MatchingSommarioni

This repository contains the code of the step 4 of a pipelining project done in context of course Foundation of Digital Humanities (DH-405) at EPFL.

Refer to the main [repository](https://github.com/Jmion/VeniceTimeMachineSommarioniHTR) of the project to access to the whole pipeline.

The goal of this step is to establish a matching between an excel file and some extracted data from Sommarioni. 
The full documentation and explanation of the project can be found on the [project wiki page](http://fdh.epfl.ch/index.php/Deciphering_Venetian_handwriting).

The code of the matching is provided in two jupyter notebooks. The main notebook is Matching.ipynb. Given the input computed in step 2 and 3 of the pipeline and the main excel file, it outputs the results.csv file.

The second notebook called Patch_statistics.ipynb is a short exploratory data analysis to show the reasons behind the design choices of the data wrangling step implemented in the main notebook.
