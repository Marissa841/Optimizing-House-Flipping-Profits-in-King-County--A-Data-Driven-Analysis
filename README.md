## Overview

This project analyzes the King County data set to answer the business case question of what types of housing features to pay attention to when buying and flipping homes in King county. Using the OSEMN data science process the housing features that would be the most lucrative for the Zillow-type company would be bathrooms, sqft.living, and grade. 

## Business Case
 
The budding Zillow-type company, J.Hughes Inc., is buying and flipping houses in the Seattle area. They would like to know the types of housing features to prioritize to make the most profit. Knowing which features have the biggest impact on housing prices, J. Hughes Inc. could then make data-driven decisions on which houses to purchase to optimize making a profit on.

![map of kc](/images/kc_folium_map.png)
 
## Data

The data used in this project is the King County housing dataset. The dataset provides data from houses sold between the years 2014 to 2015 with 21,597 entries which includes 21 features.
 
## Methods

This project used the OSEMN data science process. OSEMN stands for obtain, scrub, explore, model, and interpret. 
 
## Results

After running four linear regression models, the second model proved to have the best and most relevant results for the stakeholders. Specific housing features to pay attention to when purchasing and flipping homes were most notably bathrooms, sqft.living, and grade. 

![model table](/images/model_table.png)
 
 
## Conclusions + Future Work

Some key insights include adding a bathroom to increase the home value by $20,940. By keeping the renovation costs below $20,940 it'd be a clear way to make a profit when flipping.
My second recommendation would be to add sqft.living to a house. For each unit of additional sq. footage $ 137 would be  added to the value. My third recommendation would be to increase the grade of the house. This will add $112,200 to the value.
For additional future work, I'd like to make additional models with the KC data for houses above 1.5 million. Also, I'd like to look at not just houses, but apartments and other types of housing as well.

 
## For More Information

​​See the full analysis in the [Jupyter Notebook](https://nbviewer.org/github/Marissa841/dsc-phase-2-project/blob/main/phase_2_project.ipynb) or review this [presentation](https://github.com/Marissa841/dsc-phase-2-project/blob/main/project_2_presentation.pdf).
For additional info, contact Marissa Bush at Marissabush.02@gmail.com
 
## Repository Structure

```bash 
├── data
├── images
├── README.md
├── phase_2_presentation.pdf
└── phase_2_project.ipynb
```
 
 

