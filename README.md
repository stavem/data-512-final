# GENDER AND STOCK MARKET PARTICIPATION
_Karl Stavem_

### ABSTRACT



### PROJECT STRUCTURE

    ├── raw_data/                          # Raw data taken directly from the US Financial Capability Website
    ├── dataset_documentation/             # PDF documentation provided by FINRA, outlining all data elements
    ├── cleaned_data/                      # Cleaned csv file only containing data used in this analysis
    ├── figures/                           # All charts and figures created during analysis
    ├── Final_Report.ipynb                 # Complete analysis and report
    ├── LICENSE                            # MIT License
    └── README.md

### DATA SOURCES
#### Descrption
The primary dataset used in this research is the 2018 National Financial Capability Study (NFCS), funded by the FINRA Investor Education Foundation.  The 2018 NFCS contains responses from roughly 27,000 households across all 50 states. Each respondent provided answers to 127 different questions. All responses have been numericall encoded into a single .csv file.

#### Usage/Access
The 2018 NFCS dataset is freely available online and is subject to FINRA's [terms of use](https://www.usfinancialcapability.org/terms.php).  Full details and descrptions can be found on the on the [Data and Downloads](https://www.usfinancialcapability.org/downloads.php) page of the US Financial Capability website.  The primrary dataset used in this exploration is titled, _2018 State-by-State Survey — Respondent-Level Data, Comma delimited Excel file (.csv)_ and it may be downloaded in a .zip file directly from FINRA's website using [this link](https://www.usfinancialcapability.org/downloads/NFCS_2018_State_by_State_Data_Excel.zip).  This project already contains the full 2018 NFCS dataset, which can be viewed directly here: [\"NFCS 2018 State Data 190603.csv\"](raw_data/NFCS%202018%20State%20Data%20190603.csv). 


### PYTHON LIBRARIES USED
The analysis in this repository requires the following python packages:

* Pandas
|  https://pandas.pydata.org/

* Seaborn
| https://seaborn.pydata.org/  

* requests, zipfile, io


### PROJECT LICENSE
Please view the [MIT License](/LICENSE) for details.

