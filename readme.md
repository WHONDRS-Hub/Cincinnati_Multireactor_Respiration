# University of Cincinnati Repository

This repository is for data and scripts for processing multireactor data associated with University of Cincinnati (RS) project. The folders are as follows:

  - **Data**
    - [RS_INC_Raw_DO_By_Min_ReadyForBoye_2024-08-28.csv](https://github.com/WHONDRS-Hub/Cincinnati_Multireactor_Respiration/blob/main/Data/RS_INC_Raw_DO_By_Min_ReadyForBoye_2024-08-28.csv): Raw DO data for each site with time and methods deviations
        - There are alphanumeric codes in the Methods_Deviation column within [RS_INC_Raw_DO_By_Min_ReadyForBoye_2024-08-28.csv]. These codes indicate a deviation in the methods and are as defined as follows:
          - RATE_004 indicates that the theoretical saturated point included as a zero minute starting point for incubations.
          - RATE_006 indicates that the sample was put on during the same minute or the minute before the first picture of the sample was taken
    - [RS_Drying_Masses_ReadyForBoye_on_2024-08-28.csv](https://github.com/WHONDRS-Hub/Cincinnati_Multireactor_Respiration/blob/main/Data/RS_Drying_Masses_ReadyForBoye_on_2024-08-28.csv): Dry sediment mass and mass of water used in incubation used to convert rates to per mass basis
    - [RS_Sediment_Incubations_Respiration_Rates_Original_Script_2024-11-12.csv](https://github.com/WHONDRS-Hub/Cincinnati_Multireactor_Respiration/blob/main/Data/RS_Sediment_Incubations_Respiration_Rates_Original_Script_2024-11-12.csv): Respiration rates fit to data using rules set for other ECA incubations (information in methods code)
    - **Plots**
      - [Linear_Fits](https://github.com/WHONDRS-Hub/Cincinnati_Multireactor_Respiration/tree/main/Data/Plots/Linear_Fits): Images of linear regressions fit to DO data. Four plots per sample that correspond to rules in script that remove data points.
        - **Archive**
          - Plots for other data fits (non linear, less stringent linear regression rules)  
    - **Archive**
      -  [RS_INC_Raw_DO_By_Min_HMR.csv](https://github.com/WHONDRS-Hub/Cincinnati_Multireactor_Respiration/blob/main/Data/RS_INC_Raw_DO_By_Min_HMR.csv): Raw DO in format needed for hmr R library
      -  [Combined_Fits_RS_Sediment_Incubations_Respiration_Rates_2024-11-05.csv](https://github.com/WHONDRS-Hub/Cincinnati_Multireactor_Respiration/blob/main/Data/Combined_Fits_RS_Sediment_Incubations_Respiration_Rates_2024-11-05.csv): Combined linear and non-linear fits (no data points removed)
      -  [HMR-RS_INC_Raw_DO_By_Min_HMR.csv](https://github.com/WHONDRS-Hub/Cincinnati_Multireactor_Respiration/blob/main/Data/HMR%20-%20RS_INC_Raw_DO_By_Min_HMR.csv): output from HMR R library
  - **Scripts**
    - [Multireactor_Rate_Processing](https://github.com/WHONDRS-Hub/Cincinnati_Multireactor_Respiration/blob/main/Scripts/Multireactor_Rate_Processing.Rmd): Calculates and exports respiration rates for original ECA fit (chosen for your data), less rules in ECA fit, and non-linear fit (a*exp(b*t).
    - [HMR_Script](https://github.com/WHONDRS-Hub/Cincinnati_Multireactor_Respiration/blob/main/Scripts/HMR_Script.R): script that uses HMR library in R to choose linear/non-linear fit for each data point (not used)


