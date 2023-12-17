# ReneWind

# Business Context
As the demand for electrical energy increases so does the carbondioxide emissions and other global warming emissions. These emissions have negative impacts on the health of people due to polluted air and water that people may ingest. In the United States of America, up to 29% (according a 2017 publication of the Union of Concerned Scientists) of the global warming is attributed to the electricity sector. This adverse effect has necessitated the shift to clean energy sources such as wind energy.

Wind power is a clean and renewable energy source. In order to promote its use, the U.S Department of Energy has developed a guide for operational efficiency following cutting edge research and developments on predictive maintenance and wind infrastructure lifecycle enhancement.

To ensure that the engines and other components of the wind energy generators are working optimally and effectively during their service lives, predictive maintenance policy must be implemented to predict future breakdowns, critical component damage and in turn control the lifecycle costs when the failures or component damage can be correctly predicted and the appropriate measures taken thereby forestalling breakdowns and increasing customer satisfaction.

These generators are fitted with sensors that are able to collect readings of different parameters related to some physical quantities and health status of wind turbines such as the temperature, humidity, wind speed, gearbox, weight of blades, vibration measures etc.

# Objective
"ReneWind" is interested in enhancing its processes involved in wind energe generation by employing machine learning. Using smart sensors, ReneWind has been collecting data relating to generator failures of the wind turbines. To build the machine learning model, ReneWind has provided a crypted version of the data collected from sensors on the wind turbines. Due to ReneWind intellectual property policy the data was crypted. Data has 40 predictors, 20000 observations in the training set and 5000 in the test set.

The objective is to build several classification models, tune them and find the best model that can correctly identify failures in order respond appropriately to potential failures before they can happen and ultimately control lifecycle costs on the wind turbines for the company, protect its investments and increase customer satisfaction. The nature of predictions made by the classification model will translate as follows:

True positives (TP) are failures correctly predicted by the model. These will result in repairing costs.
False negatives (FN) are real failures where there is no detection by the model. These will result in replacement costs.
False positives (FP) are detections where there is no failure. These will result in inspection costs.
It is given that the cost of repairing a generator is much less than the cost of replacing it, and the cost of inspection is less than the cost of repair.

“1” in the target variables should be considered as “failure” and “0” represents “No failure”.

