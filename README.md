![Illustration of different cancer treatment drugs](https://www.drugtargetreview.com/wp-content/uploads/pill-750x450.gif)
# data_visualisation
## Description
In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens. I'm tasked with generating all of the tables and figures needed for the technical report of the clinical study and producing a top-level summary of the study results.
## Usage 
Please navigate to the Starter_Code folder to find the code for the data analysis process

## Installations
The following dependencies have been installed for this project. Please copy the code as is to your code editor:
`import matplotlib.pyplot as plt`\
`import pandas as pd`\
`import scipy.stats as st`\
`import numpy as np`

Please make sure you have the following libraries pre-installed:
`pip install matplotlib`\
`pip install pandas`\
`pip install scipy`\
`pip install numpy`

## Analysis results
Our original dataset contains information about most recent animal study at Pymaceuticals - pharmaceutical company specialising in cancer treatments. Specifically, the dataset contains the following columns:
1. `Mouse ID`
2. `Timepoint`
3. `Tumor Volume (mm3)`
4. `Metastatic Sites`
5. `Drug Regimen`
6. `Sex`
7. `Age_months`
8. `Weight (g)`

### Summary statistics
In this section, I create a DataFrame that holds the following summary statistics:
1. mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen

![Alt text](<Screenshot 2023-12-26 at 9.45.42 pm.png>)

### Visualisations
In this section, I generated bar and pie charts to further investigate our datataset. Specfically, I generated:
1. A bar plot showing the total number of rows (Mouse ID/Timepoints) for each drug regimen 
![Alt text](<Screenshot 2023-12-26 at 9.51.24 pm.png>)
3. A pie plot showing the distribution of female versus male mice
![Alt text](<Screenshot 2023-12-26 at 9.50.58 pm.png>)
4. A line plot of tumor volume vs. time point for a single mouse treated with Capomulin
![Alt text](<Screenshot 2023-12-26 at 9.50.32 pm.png>)
5. A box plot that shows the distrubution of the tumor volume for each treatment group
![Alt text](<Screenshot 2023-12-26 at 9.52.03 pm.png>)
6. A regression model of mouse weight vs. the average observed tumor volume for the entire Capomulin regimen
![Alt text](<Screenshot 2023-12-26 at 9.50.14 pm.png>)

## Credits
Special thanks to the following individuals for their contributions to the project:

-Jesse Wright (BCS tutor)

-Kyle Goode (BCS tutor)

-Ask BCS learning assistants
