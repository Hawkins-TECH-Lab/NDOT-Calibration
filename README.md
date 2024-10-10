# Traffic Volume Prediction and Calibration Using Big Data Sources

This repository accompanies the paper: *Enhancing Traffic Volume Prediction by Integrating StreetLight Data, Road Attributes, and EPA Smart Location Database*. 

The objective of this study is to verify and enhance the accuracy of StreetLight Data (StL) traffic volumes by calibrating them against traditional traffic volume data from the City of Lincoln (CoL). Additionally, this study integrates road attributes and the EPA Smart Location Database (EPA-SLD) to improve traffic volume prediction accuracy.

## Overview

For Location-Based Services (LBS) data to achieve its purpose, it is crucial to rigorously assess and improve the accuracy of the data. This paper addresses the challenge by developing traffic prediction models and integrating the following data sources:

- **StreetLight Data (StL)**: A traffic volume dataset used to measure vehicle, pedestrian, and bicycle volumes.
- **City of Lincoln (CoL) Traffic Data**: Traditional traffic volume data used for calibration.
- **Road Attributes**: Factors such as lane count, speed, median type, shoulder width, speed limits, and road flow type.
- **EPA Smart Location Database (EPA-SLD)**: Provides insights into housing density, land use diversity, neighborhood design, transit service, and more.

By integrating these data sources, the study aims to refine traffic predictions and contribute to the expanding body of research on the use of Big Data in transportation modeling and policy development.

## Contents

This repository does not include all raw data due to data privacy constraints. However, it provides processed datasets and code for analysis.

### Included Files:
- **Vehicle, Pedestrian, and Bicycle Networks**: Spatially joined with road attributes from the NDOT geodatabase and EPA-SLD shapefiles.
- **Jupyter Notebooks**:
  - `process_pedestrian_bike_intersections.ipynb`: Processes pedestrian and bike data at the intersection level and prepares it for analysis.
  - `process_vehicle_links.ipynb`: Processes vehicle data at the link level and prepares it for analysis.
  - `rf_model_pedestrian_bike.ipynb`: Random forest model analysis for pedestrian and bicycle data.
  - `vehicle_modeling.ipynb`: Statistical and random forest modeling for vehicle data.
  - `compare_train_predict.ipynb`: Compares training and prediction datasets for further analysis.

## Contributing

Contributions to enhance the code or analysis are welcome. Feel free to submit a pull request or open an issue if you have suggestions for improvement.
