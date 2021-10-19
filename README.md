# Cepheid_rrlyrae
Purpose:
---------
The aim of this investigation is to specify the best machine learning method for distinguishing different kinds of stars. 

Data:
------
I generated my data using TOPCAT software and from GAIA data source (the full guidance on procedure is in the TOPCAT repository).

Codes:
---------
All codes and plots are in the "code" file. I fixed the number of random_state so you can achieve the same results.  
Notice that there are 2 files:
1) general_data: in this case, I take all data into account (3344 for cepheids and 60317 for rrlyraes)
2) confined_data: in this case, I removed all data which can be considered as outliers

Result:
---------
Considering Cepheids and rrlyrae stars, the best method was decision tree with test accuracy of about 99% for the general data and 65% for limited ones. 
