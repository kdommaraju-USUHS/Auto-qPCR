# Auto-qPCR
A python program to process spreadsheet output directly from qPCR thermocycler.

This repository contains the python and flask scripts that are used to create the web app. 

See the web app version https://auto-q-pcr.com/

This work is described in the publication:
https://www.nature.com/articles/s41598-021-99727-6#Abs1

Please site our publication if you use Auto-qPCR in our research
Maussion, G.$, Thomas, R.A.$, Demirova, I. et al. Auto-qPCR; a python-based web app for automated and reproducible analysis of qPCR data. Sci Rep 11, 21293 (2021). https://doi.org/10.1038/s41598-021-99727-6

$Equal contribution

# To run locally in development mode
Clone this github repository

1. navigate to the folder 'website/Auto-q-pcr-frontend'. You must be within the local-GUI folder or the program won't run.
$ cd website/Auto-q-pcr-frontend/

2. create a virtual environment and install requirements, and run the program.


3. run the program 
$ python main.py
 * Serving Flask app "application" (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: off
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)


either a local browers will open or you will have the link in your terminal click open link and the GUI will open in your webbrowser (firefox, chrome).

All the source scripts are available. Python scripts using flask to create a local server which works to process qPCR data and perform statistics.

The file requirments.txt list packages needed to run the local server.

4. In your local web browser follow the instructions and enter all the user input boxes. 

# Run a local version not for development
A zip folder containing a local version with instruction on how to run is currently under the help tab on the auto-q-pcr website.
The same folder can be located when you pull this github repo and navigate to
$ Auto-qPCR/website/Files_to_link_website/sample data/Local_Download

 
# Command Line version is archived 
We are not updating these scripts.

# Contributions
We invite your contributions.  Please fork this repository and make a pull request if you are interested in contributing to the web app or command line version. 

# Authorship

Program conception: Rhalena Thomas and Gilles Maussion

Program and web app design and management: Rhalena Thomas

Command line data input and absolute model: Iveta Demirova

Relative models and genomic instability: Eddie Cai

Web app and interface development, statistic and plotting: Gracia Gu

This repository is managed by Rhalena Thomas.  The auto-qPCR webapp is maintained by Rhalena Thomas. 

# Licencing

Auto-q-PCR is a program for analysis of qPCR data for absolute and relative quantification
Copyright (C) 2021 Rhalena Thomas, Eddie Cai, Gracia Gu and Iva Demirova at the NeuroEDDU
This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation version 3 of the License,

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  

For further information see: http://www.gnu.org/licenses/gpl.html

