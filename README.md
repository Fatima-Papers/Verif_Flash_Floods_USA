[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

# Name or brief description of the repository

### Background

### Description of the repository's content

### Description on how to run the code
_Note._ If the objective is to replicate the same verification analysis, the code does not need modifications, and it can be run as it is. It the objective is to reproduce the code with your own forecasts and observations, you will need to modify the following sripts to adapt the to your data:
      - "Scripts/Raw/Retrieve_FC_ENS.sh" : to download the benchmark forecasts
      - "Scripts/Raw/Retrieve_FC_ecPoint.sh" : to download the forecasts to assess
      - "Scripts/Raw/Retrieve_OBS_NOAA_Reports_README.txt" : to download the flood reports to use in the verification analisys and in the definition of the climatologies of rainfall events associated with flash floods.
      - "Scripts/Raw/Create_USA_Mask_ENS.mv" : to create the mask of the domain of interest.
      - "Scripts/Processed/01_Compute_Clean_NOAA_Reports.py" : to clean the flood reports to use in the verification analisys and in the definition of the climatologies of rainfall events associated with flash floods. If your reports do not need any cleaning, this script can be skipped or deleted.

### Licensing
The code and the report are freely available under the CC BY-NC-SA 4.0 license (Creative Commons, Attribution-NonCommercial-ShareAlike).  
The data (i.e. rainfall forecasts and observations) is available upon request to the main author of the repository and prior authorization from ECMWF management.

#### Main author
Fatima Pillosu
PhD student at University of Reading & Visiting scientist at ECMWF
fatima.pillosu@ecmwf.int
