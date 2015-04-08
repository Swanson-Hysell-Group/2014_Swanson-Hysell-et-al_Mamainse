Overview
===============================
This repository contains code and data associated with a paper published in the Geological Society of America journal GEOLOGY in 2014. The manuscript is entitled "Magmatic activity and plate motion during the latent stage of Midcontinent Rift development" authored by: Nicholas L. Swanson-Hysell, Seth D. Burgess, Adam C. Maloof, and Samuel A. Bowring. The article is available in the UC eScholarship repository: http://escholarship.org/uc/item/989179cs

This work can be cited as:
`
Swanson-Hysell, Nicholas L. and Burgess, Seth D. and Maloof, Adam C. and Bowring, Samuel A., Magmatic activity and plate motion during the latent stage of Midcontinent Rift development: Geology, 2014, v. 42, p. 475-478, 10.1130/G35271.1.

Contents of this repository
===============================

Code
-------------------------------
This folder contains an IPython notebook that contains statistical data analysis and plotting associated with paleomagnetic data in the the manuscript. In addition to the IPython notebook, the folder contains the pmag.py, pmagplotlib.py, and pmagpyrc.py libraries of PmagPy version 2.206 as well as a library IPmag.py that modifies some of the interactive programs of PmagPy for use in the IPython environment in addition to providing some new functions. This folder also contains a PDF version of notebook to be viewed outside of the IPython generated using nbconvert. Note that the IPython notebook can also be viewed online without an IPython installation at this link where it is rendered better than in the PDF output:

http://nbviewer.ipython.org/github/Swanson-Hysell/2014_Swanson-Hysell-et-al_Mamainse/blob/master/Code/Mamainse_Data_Analysis.ipynb

Data
-------------------------------
This folder contains three files:
### MP_Pmag_Summary.xlsx ###
This excel spreadsheet has all of the site mean data used in the study. There are four sheets within the spreadsheet (1) the latex formatted text that was used to generated the table in the GSA data repository; (2) an interactive worksheet where Fisher means can be calculated from the flow means; (3) a sheet with preliminary formatting for the MagIC database and (4) data in the format that was exported for the Mamainse_Point_data.csv file.
### Mamainse_Point_data.csv ###
This csv file contains the flow (i.e. site) mean paleomagnetic data as well as the locations of the flows stratigraphically and geographically (lat, long is in WGS84). These data are imported and analyzed in the IPython notebook.
### NSVGsubset_VGP.txt, SCV_VGP.txt, SI_upperthird_VGP.txt ###
Text files used for comparitive analysis in the IPython notebook. See paper text for more details.
