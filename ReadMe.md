# Understanding and Predicting Blight Fine

## Overview

For this project we wanted to better predict when someone in Detroit would not only allow their property to fall to blight but also not be compliant with the fines issued afterwards.

We based this project on a data challange from the Michigan Data Science Team (MDST) and the MIchigan Student Symposium for Interdisciplinary Statistical Sciences (MSSISS). They partnered with the City Detroit to better understand this problem.

Blight, allowing your property to fall into and remain in ruin,  has become a serious problem in Detroit. Every year the city issues millions of dollars in fines to violators and every year many of those tickets go unpaid. Following up and enforcing these fines can become extremely costly as well and as such they want to use predictive analytics to increase ticket compliance.


To answer this question we first needed to understand when and why a resident would not comply with a blight violation. This is the task, understanding the factors that play into that, be they categorical or numerical.


## Data

The data we obtained for this project we recieved from the university of Michigan as well as the Detroit Open Data Portal.

source": [
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
    "| **Needs Boardingt** | whether the building is in need of structural repair |\n",
    "| **Fire** | whether the lot has suffered fire damage|\n",
    "| **Dumping** | Whether the lot has been used as a dumping ground |\n",
    "| **Units** | number of units at the site |
    
## Methodology

## Results

## Conclusion

├── README.md                           <- The top-level README for reviewers of this project\n",
    "├── Project_Walkthrough.ipynb           <- Narrative documentation of analysis in Jupyter notebook\n",
    "├── Pneumonia-ID.pdf                    <- PDF version of project presentation\n",
    "├── src                                 <- Contains python modules\n",
    "│   └── modules                         <- .py files\n",
    "├── images                              <- Both sourced externally and generated from \n",
    "│                                          code\n",
    "├── notebooks                           <- Noteboooks used to build Walkthrough\n",
    "├── models                              <- Saved models\n",
    "└── data                                <- Data obtained from the Census Bureau\n",
    "    └── extracted                       <- .py files