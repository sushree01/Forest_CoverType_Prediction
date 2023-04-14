# Forest_Cover_Prediction

Predicting forest cover type from cartographic variables only (no remotely sensed data). The actual forest cover type for a given observation (30 x 30 meter cell) was determined from US Forest Service (USFS) Region 2 Resource Information System (RIS) data. Independent variables were derived from data originally obtained from US Geological Survey (USGS) and USFS data. Data is in raw form (not scaled) and contains binary (0 or 1) columns of data for qualitative independent variables (wilderness areas and soil types).

This study area includes four wilderness areas located in the Roosevelt National Forest of northern Colorado. These areas represent forests with minimal human-caused disturbances, so that existing forest cover types are more a result of ecological processes rather than forest management practices.


| **Data Attributes**                                                                                     |
|---------------------------------------------------------------------------------------------------------|
| Elevation: quantitative meters Elevation in meters                                                      |
| Aspect: quantitative azimuth Aspect in degrees azimuth                                                  |
| Slope: quantitative degrees Slope in degrees                                                            |
| Horizontal_Distance_To_Hydrology: quantitative meters Horz Dist to nearest surface water features       |
| Vertical_Distance_To_Hydrology: quantitative meters Vert Dist to nearest surface water features         |
| Horizontal_Distance_To_Roadways: quantitative meters Horz Dist to nearest roadway                       |
| Hillshade_9am: quantitative 0 to 255 index Hillshade index at 9am, summer solstice                      |
| Hillshade_Noon: quantitative 0 to 255 index Hillshade index at noon, summer soltice                     |
| Hillshade_3pm: quantitative 0 to 255 index Hillshade index at 3pm, summer solstice                      |
| Horizontal_Distance_To_Fire_Points: quantitative meters Horz Dist to nearest wildfire ignition points   |
| Wilderness_Area: (4 binary columns) qualitative 0 (absence) or 1 (presence) Wilderness area designation |
| Soil_Type: (40 binary columns) qualitative 0 (absence) or 1 (presence) Soil Type designation            |
| Cover_Type: (7 types) integer 1 to 7 Forest Cover Type designation                                      |

Code Designations:
|   | Wilderness Areas                |
|---|---------------------------------|
| 1 | Rawah Wilderness Area           |
| 2 | Neota Wilderness Area           |
| 3 | Comanche Peak Wilderness Area   |
| 4 | Cache la Poudre Wilderness Area |

|   | Soil Cover Types     |
|---|----------------------|
| 1 | Spruce/Fir           |
| 2 | Lodgepole Pine       |
| 3 | Ponderosa Pine       |
| 4 | Cottonwood/Willow    |
| 5 | Aspen                |
| 6 | Douglas-fir          |
| 7 | Krummholz            |
