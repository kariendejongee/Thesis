The pre process shape.ipynb needs to be run first, data input for this script is:
- Hurricane_Ian_scenarios/Hurricane_Ian_Shifted_70/impacts/Impacts_building_footprints_Hurricane_Ian_Shifted_70.gpkg'
- Hurricane_Ian_scenarios/Hurricane_Ian/impacts/Impacts_building_footprints_Hurricane_Ian.gpkg'
- current_risk_no_measures/Impacts/Impacts_building_footprints_current_risk_no_measures.gpkg"
—> these files result in:
shape_charleston.gpkg
The final result for the pre procces data file is: damage_shape.csv

The input for pre process data.ipynb is:
- online census data
- damage_shape.csv

final output file for the model is: census_data_incl.csv
