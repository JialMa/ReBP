# ReBP

## Project Profile
The datasets uploaded in the ReBP project are some of the raw data collected from the experiments and the pre-processing results, which are intended to provide support for subsequent signal processing, feature extraction and modeling studies.

## Data Description
The data file format for this project is `.mat` and each `.mat` file contains the following four types of data:

- **rawdata**  
  Preliminary processed millimeter wave radar signal data.
  
- **wavedata**  
  Millimeter-wave radar signals after adaptive filtering processing for subsequent feature extraction and analysis.
  
- **ppgdata**  
  Synchronized acquisition of PPG signal data.
  
- **name**  
  String type identifying the file name, encoded to contain the blood pressure reference value:
  - `S` followed by the Systolic Blood Pressure (SBP) value.
  - `D` followed by Diastolic Blood Pressure (DBP) value.
## Attention
- There may be small noise or drift phenomenon in the data set, please pre-process appropriately according to the needs when using.
- The collected data are for research and study only, and are prohibited for commercial use.
