# University of Cincinnati Repository

This repository is for data and scripts for processing multireactor data associated with University of Cincinnati (RS) project. The folders are as follows:\

  - **Data**
    - [RS_INC_Raw_DO_By_Min_ReadyForBoye_2024-08-28.csv](https://github.com/WHONDRS-Hub/Cincinnati_Multireactor_Respiration/blob/main/Data/RS_INC_Raw_DO_By_Min_ReadyForBoye_2024-08-28.csv): Raw DO data for each site with time and methods deviations
    - [RS_INC_Raw_DO_By_Min_HMR.csv](https://github.com/WHONDRS-Hub/Cincinnati_Multireactor_Respiration/blob/main/Data/RS_INC_Raw_DO_By_Min_HMR.csv): Raw DO in format needed for hmr R library
    - [RS_Drying_Masses_ReadyForBoye_on_2024-08-28.csv](https://github.com/WHONDRS-Hub/Cincinnati_Multireactor_Respiration/blob/main/Data/RS_Drying_Masses_ReadyForBoye_on_2024-08-28.csv): Dry sediment mass and mass fo water used in incubation used to convert rates to per mass basis
    - [Combined_Fits_RS_Sediment_Incubations_Respiration_Rates_2024-11-05.csv](https://github.com/WHONDRS-Hub/Cincinnati_Multireactor_Respiration/blob/main/Data/Combined_Fits_RS_Sediment_Incubations_Respiration_Rates_2024-11-05.csv): Combined linera and non-linear fits (no data points removed)
    - [RS_INC_Raw_DO_By_Min_HMR.csv](https://github.com/WHONDRS-Hub/Cincinnati_Multireactor_Respiration/blob/main/Data/HMR%20-%20RS_INC_Raw_DO_By_Min_HMR.csv): output from HMR R library
  
  - **Scripts**
    - [Multireactor_Rate_Processing](https://github.com/WHONDRS-Hub/Cincinnati_Multireactor_Respiration/blob/main/Scripts/Multireactor_Rate_Processing.Rmd): Comparing rules set for initial ECA analysis, changed to fit Cincinnati data. Also compares non-linear fit (a*exp(b*t)
    - [HMR_Script](https://github.com/WHONDRS-Hub/Cincinnati_Multireactor_Respiration/blob/main/Scripts/HMR_Script.R): script that uses HMR library in R to choose linear/non-linear fit for each data point


