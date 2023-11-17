# NHERI_Simcenter_Hazus_Project

## Project Description


## Contributors
- Adam Zsarnóczay (Principal Investigator)
- Zizhuo (Tina) Chen

## Installation Instructions
This project utilizes datasets from the HAZUS Database. To get started, you do not need to install any additional software or datasets. Simply use the notebook developed for this project.

## DataSet
| Dataset Title | Dataset Description | Link|
|----------------|----------------------|----|
|Raw_Data| Contains unprocessed data directly exported from the Hazus Database at the county level| [Link](https://drive.google.com/drive/folders/1E8kSf4Ru7Pgp_YkrlloN5_vsGBRLhSJb?usp=drive_link)|
|Processed_Data| Contains combined data based on tables from each state at the county level. For more information, please refer to the documentation notebook| [Link](https://drive.google.com/drive/folders/1caRGqXaTtMj-hUMndJvwOZuV2Dvo38WN?usp=sharing)|
|Simulation_Probability_Indicator_File| Contains probability of the construction material based on characteristics of the building region.| [Link](https://drive.google.com/drive/folders/1oGeqZuAJc6_InvAYyM90GiOklu--OjHV?usp=drive_link)|
## Notebooks
Here is a table listing all the notebooks along with a one-line description for each:

| Notebook Title | Notebook Description |
|----------------|----------------------|
| [BuildingType](#buildingtype) | Focuses on data loading, cleaning, simulation, and sampling for building types. |
| [CA_WA_OR_hzBldgCountOccupB_T_table](#ca_wa_or_hzbldgcountoccupb_t_table) | Processes building count and occupancy data for CA, WA, and OR. |
| [Documentation](#documentation) | Serves as a documentation resource with explanations and instructions with tables in the Processed data |
| [Hazua_CA_data_sum](#hazua_ca_data_sum) | Centers on summarizing and analyzing data specific to California. |
| [Hazuz_NY_sum](#hazuz_ny_sum) | Focuses on data summary and analysis for New York. |
| [Master_sum](#master_sum) | Provides a summation of datasets after being exported from the HAZUS Database. |

<a name="buildingtype"></a>
#### BuildingType

- **Title**: [BuildingType](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/edit/main/README.md#:~:text=t-,BuildingType,-(1).ipynb)
- **Description**: Focuses on data loading, cleaning, simulation, and sampling for building construction types across the entire US. It processes state, FIPS code, and county information, combining data from various tables like BuildingCount, Demographics, and TIGERCensusBlock.

<a name="ca_wa_or_hzbldgcountoccupb_t_table"></a>
#### CA_WA_OR_hzBldgCountOccupB_T_table

- **Title**: [CA_WA_OR_hzBldgCountOccupB_T_table](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/edit/main/README.md#:~:text=BuildingType%20(1).ipynb-,CA_WA_OR_hzBldgCountOccupB_T_table,-.ipynb)
- **Description**: This notebook focuses on processing building count and occupancy data for California, Washington, and Oregon. It includes data manipulation and merging techniques, emphasizing the handling of specific building occupancy types and counts.

#### county_dash
- **Title**: [county_dash](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/edit/main/README.md#:~:text=README.md-,county_dash,-.ipynb)
- **Description**: Dedicated to creating dashboards for county-level data. It includes data loading, processing, and visualization. The notebook emphasizes interactive features for better data understanding and representation.
<a name="county_dash"></a>

#### Documentation
- **Title**: [Documentation](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/edit/main/README.md#:~:text=CA_WA_OR_hzBldgCountOccupB_T_table.ipynb-,Documentation,-.ipynb)
- **Description**: Serves as a documentation resource, providing detailed explanations and instructions for various data processing tasks. It includes examples and guidelines for users to follow.
<a name="documentation"></a>

#### Hazua_CA_data_sum

- **Title**: [Hazua_CA_data_sum](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/edit/main/README.md#:~:text=Documentation.ipynb-,Hazua_CA_data_sum,-.ipynb)
- **Description**: This notebook is centered around summarizing and analyzing data specific to California. It includes various data aggregation techniques and focuses on deriving meaningful insights from the summarized data.
- Examples of Geospatial Graphs:
![Emeryville Footprint ](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/assets/89886448/da8d54c5-5057-4ca6-85f0-9e6b255dbb30)
![Emeryville Hazus Building Block Score](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/assets/89886448/e8c2da89-d581-4cc4-8d6a-7b7468c370da)
![Emeryville Hazus Building Block Difference Score](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/assets/89886448/c06e18ce-6201-45f3-ae98-47aeda70f60b)
<a name="hazua_ca_data_sum"></a>

#### Hazuz_NY_sum
<a name="hazuz_ny_sum"></a>
- **Title**: [Hazuz_NY_sum](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/edit/main/README.md#:~:text=Hazua_CA_data_sum.ipynb-,Hazuz_NY_sum,-.ipynb)
- **Description**: Focuses on data summary and analysis for New York. It involves complex data processing steps, aiming to provide a comprehensive overview of building counts related to New York.
- - Examples of Geospatial Graphs:
![Park Slope Footprint](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/assets/89886448/0c795546-3b9e-4ae7-a14a-a7e1b5240015)
![Park Slope Hazus Building Block Score](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/assets/89886448/34565bf4-3690-403b-9f9b-a6c57682072e)
![Park Slope Hazus Building Block Difference Score](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/assets/89886448/e5241d24-db99-4860-844a-4e5b526f3ecd)

#### Master_sum
<a name="master_sum"></a>
- **Title**: [Master_sum](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/edit/main/README.md#:~:text=LICENSE-,Master_sum,-.ipynb)
- **Description**: Aimed at providing a master summary of various datasets after being exported from HAZUS at the county level. It integrates data from multiple sources, offering a holistic view and aiding in overarching data analysis tasks.

---



Acknowledgments
This project makes use of data from the HAZUS Database. We acknowledge the creators and maintainers of this database for their valuable contributions to the field.


