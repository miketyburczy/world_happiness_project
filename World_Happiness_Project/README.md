# World_Happiness_Project
Project 1 for Rutgers Bootcamp

Contributors: Garrett Gomez-Spillane
              Harry Bonsu
              Tejas Patel
              Mike Tyburczy
              David Thompson

# Raw Data
The raw data folder contains the inital data files we obtained through our search for datasets that would work with our analysis. The files in raw data folder were read into jupyter notbeooks created stored in the "Inital Clean up Raw Data" folder

# Inital Clean up Raw Data
The Inital Clean up Raw Data folder contains the jupter notebooks our group created to run each of the raw data file. Within these notebooks you will find code using pandas library to observe each dataset and procure the relevant values we wanted to use in our main Jupyter Notebook notebook.
    * Please note, that each notebook will send a new copy of each data frame to the folder "clean data."

# Clean Data
This folder contains the data files that have been cleaned and staged for a merge inside our main Jupyter Notebook "consolidated_data_df." 

# Consolidate_data_df
This is our main Jupyter Notebook. The top portion of the notebook was used to read in each file stored in the "clean data" folder. Each file was called individually to determin were the merge would occur and what values needed to be renamed, formatted or dropped. We kept the individual data frame calls commmented out incase someone would like to see the dataframes before the merge.

The second part of our main Jupyter Notebook contains the visualizations from our analysis. This section calls functions defined from other jupyter notebooks to create the visualizations. These notebooks can be found on the same level as our main notebook.

    ** Please note, that to create the data containing the regression analysis table, this dataframe was created from an external jupyter notebook that ran the regression. We were unable to get the regression function found in "Garrett_notebook.ipynb" to append the values within the function to display in the main Jupyter notebook. Therefore, it was exported to a csv file and that dataset was added into the "clean data" folder and then read into the main Jupyter Notebook for visualization. The dataframe was created using the same function, just on an external working jupyter notebook.

# Images
Finally, the folder title "Images" contains the screen shots of the data frames and graphs for use in our presentation.

