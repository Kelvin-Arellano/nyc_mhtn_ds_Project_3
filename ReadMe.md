# Understanding and Predicting Blight Fine

## Overview

For this project we wanted to better predict when someone in Detroit would not only allow their property to fall to blight but also not be compliant with the fines issued afterwards.

We based this project on a data challange from the Michigan Data Science Team (MDST) and the MIchigan Student Symposium for Interdisciplinary Statistical Sciences (MSSISS). They partnered with the City Detroit to better understand this problem.

Blight, allowing your property to fall into and remain in ruin,  has become a serious problem in Detroit. Every year the city issues millions of dollars in fines to violators and every year many of those tickets go unpaid. Following up and enforcing these fines can become extremely costly as well and as such they want to use predictive analytics to increase ticket compliance.


To answer this question we first needed to understand when and why a resident would not comply with a blight violation. This is the task, understanding the factors that play into that, be they categorical or numerical.


## Data

The data we obtained for this project we recieved from the university of Michigan as well as the Detroit Open Data Portal.
    "    We synergized the data to the following collumns \n",
    "| column name | description |\n",
    "|-|-|\n",
    "| **ticket_id** | unique ID for each ticket |\n",
    "| **agency_name** | Agency issuing the ticket |\n",
    "| **disposition** | Describing the at fault party |\n",
    "| **discount_amount** | penalty reduction |\n",
    "| **judgement amount** | Penalty amount |\n",
    "| **compliance** | known compliance result for ticket |\n",
    "| **lon** | longitude |\n",
    "| **lat** | lattitude |\n",
    "| **parcel_id** | unique ID for each lot |\n",
    "| **AddCombo** | Street number and street name for lot |\n",
    "| **structure* | whether there is a structure at the lot |\n",
    "| **condition** | general condition of the lot and structure |\n",
    "| **occupancy** | number of occupancy |\n",
    "| **Needs Boarding** | whether the building is in need of structural repair |\n",
    "| **Fire** | whether the lot has suffered fire damage|\n",
    "| **Dumping** | Whether the lot has been used as a dumping ground |\n",
    "| **Units** | number of units at the site |
    "| **Improved** | Whether a site has been improved upon or not |
    "| **Maintained** | Whether a site has been maintained or not |
    "| **coordinates** | combination of lat and lon |
    "| **crime_count** | number crimes commited near a lot |


    
## Methodology
For this project we started with very large data sets, so the first step was stripping down what we thought would be usefull and combining it all into one dataset. This is primarilly what the ingeniring notebook was used for. We also used this notebook to do some feature engineering with the crime_count. 

After this was done we moved on to trying out different models with

## Results

## Conclusion

    "├── README.md                           <- The top-level README for reviewers of this project\n",
    "├── moduling.ipynb                      <- Notebook that gpes pver out modling process\n",
    "├── ingeniring_utils.py                 <- Contains python feature functions\n",
    "├── modeling_utils.py                   <- Contains python module functions\n",
    "├── images                              <- Both sourced externally and generated from Code\n",       
    "│                                          n",
    "├── ingeniring.ipynb                          <- Notebook Used for feature engineering before Modeling\n",
    "├── modules                              <- Saved models\n",
    "└── data                                <- Synergized Data obtained from University of Michigan and Detroit Open Data Portal\n",