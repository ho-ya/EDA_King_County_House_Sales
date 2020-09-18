# First Project - EDA of the King Conty House Sales Data Set

This project is centered around exploratory data 
analysis (EDA) techniques and statistical analysis, 
as well as modeling data using linear regression.

It is the first project during the 'neuefische' Data Science Bootcamp in Cologne.

The files in this repository are as follows:

**Assignment.pdf**    - Contains the task for this project and should be read before browsing the jupyter notebooks

**Presentation_Slides.pdf** - The presentation of EDA findings, which were adapted for the specific business case of an asset management firm.

**column_names.md** - Contains (partially incorrect) information about the variables in this data set. Was given at the start of this project.

**1_Cleaning.ipynb** - This part of the EDA contains the Data Cleaning process. We also take a first look at the variables to get an  understanding of their range and general meaning 

**2_Exploration.ipynb** - This is were the main part of the EDA takes place. We go through the variables and primarily look at their contribution to the house price

**3_Regression_Model.ipynb** - Contains the whole modeling process. Part of the task was to formulate a linear regression model which was optimized for the Mean Absolute Percentage Error (MAPE)

**4_Figures.ipynb** - Contains the code used to create the plots for the presentation slides. They only differ in design from the plots in '2_Exploration.ipynb'

**King_County_House_prices_dataset.csv** - The originally provided dataset

**King_County_House_prices_dataset_CLEANED.pkl** - The data set after cleaning. Written at the end of '1_Cleaning.ipynb' and read at the beginning of '2_Exploration.ipynb'

**King_County_House_prices_dataset_EXPLORED.pkl** - The data set after the core part of the EDA. Written at the end of '2_Exploration.ipynb' and read at the beginning of '3_Regression_Model.ipynb'. This ensures that all possible changes from the first two steps are present for model generation.


