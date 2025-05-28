# Solar Panel Performance Prediction for Predictive Maintenance

## Team Members
* Babatunde James ([D-DEVELOPER1](https://github.com/D-DEVELOPER1))
* Muyiwa Obadara ([mobadara](https://github.com/mobadara)
  
## Project Goal
To develop a Machine Learning model that predicts performance degradation and potential failures in solar panels using historical and real-time sensor data, enabling predictive maintenance and optimal energy output.

## Challenge Provider
This challenge is brought to you by **Zelestra** and **AWS**.

## Dataset Description
The dataset contains various features related to solar panel operation and environmental conditions. The key columns include:

* `id`: Unique identification of the row.
* `temperature`: Ambient air temperature (C).
* `irradiance`: Solar energy received per unit area (W/m²).
* `humidity`: Moisture content in air.
* `panel_age`: Age of the solar panel in years.
* `maintenance_count`: Number of previous maintenance activities.
* `soiling_ratio`: Reduction in efficiency due to dust/debris (0.0-1.0).
* `voltage`: Voltage output (V).
* `current`: Current output (A).
* `module_temperature`: Temperature of the panel surface (C).
* `cloud_coverage`: Sky coverage by clouds (percentage).
* `wind_speed`: Wind speed (m/s).
* `pressure`: Atmospheric pressure (hPa).
* `string_id`: Identifier for a group of panels.
* `error_code`: Error codes logged from panel diagnostics.
* `installation_type`: Type of mounting setup.
* `efficiency`: **Target variable** - Energy output efficiency of the panel.

## Objective
The primary objective is to build a regression model to accurately predict the `efficiency` of the solar panels. This will enable the prediction of performance degradation and provide insights into potential failures.

## Project Structure (Tentative)
