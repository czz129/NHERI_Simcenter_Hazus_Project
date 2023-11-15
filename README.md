# NHERI_Simcenter_Hazus_Project

## Project Description

## Contributors
- Zizhuo (Tina) Chen
- Adam Zsarnóczay

## Installation Instructions
This project utilizes datasets from the HAZUS Database. To get started, you do not need to install any additional software or datasets. Simply use the notebook developed for this project.

## Notebooks
Here is a table listing all the notebooks along with a one-line description for each:

| Notebook Title                                                | Notebook Description                                                          |
|---------------------------------------------------------------|-------------------------------------------------------------------------------|
| BuildingType [BuildingType]                   | Focuses on data loading, cleaning, simulation, and sampling for building types.|
| CA_WA_OR_hzBldgCountOccupB_T_table[CA_WA_OR_hzBldgCountOccupB_T_table]  | Processes building count and occupancy data for CA, WA, and OR.               |
| county_dash[county_dash]    | Creates dashboards for county-level data with interactive features.           |
| Documentation[Documentation]| Serves as a documentation resource with explanations and instructions with tables in the Processed data        |
| Hazua_CA_data_sum[Hazua_CA_data_sum]| Centers on summarizing and analyzing data specific to California.             |
| Hazuz_NY_sum[Hazuz_NY_sum] | Focuses on data summary and analysis for New York.                           |
| Master_sum[Master_sum] | Provides a master summary of various datasets for overarching analysis.       |


| Notebook Title | Notebook Description |
|----------------|----------------------|
| [BuildingType](#buildingtype) | Focuses on data loading, cleaning, simulation, and sampling for building types. |
| [CA_WA_OR_hzBldgCountOccupB_T_table](#ca_wa_or_hzbldgcountoccupb_t_table) | Processes building count and occupancy data for CA, WA, and OR. |
| [county_dash](#county_dash) | Creates dashboards for county-level data with interactive features. |
| [Documentation](#documentation) | Serves as a documentation resource with explanations and instructions with tables in the Processed data |
| [Hazua_CA_data_sum](#hazua_ca_data_sum) | Centers on summarizing and analyzing data specific to California. |
| [Hazuz_NY_sum](#hazuz_ny_sum) | Focuses on data summary and analysis for New York. |
| [Master_sum](#master_sum) | Provides a master summary of various datasets for overarching analysis. |

#### 1. BuildingType
<a name="buildingtype"></a>
- **Title**: BuildingType
- **Description**: Focuses on data loading, cleaning, simulation, and sampling for building types. It processes state, FIPS code, and county information, combining data from various tables like BuildingCount, Demographics, and TIGERCensusBlock. It categorizes building rises for material assignment.
- **Key Code Elements**: Package installations, Google Drive mounting, state and county variables, CSV file reading, GeoDataFrame creation, functions for filtering tables, and building material generation.


#### 2. CA_WA_OR_hzBldgCountOccupB_T_table
<a name="ca_wa_or_hzbldgcountoccupb_t_table"></a>
- **Title**: CA_WA_OR_hzBldgCountOccupB_T_table
- **Description**: This notebook focuses on processing building count and occupancy data for California, Washington, and Oregon. It includes data manipulation and merging techniques, emphasizing the handling of specific building occupancy types and counts.
- **Key Code Elements**: Reading and processing of CSV files, filtering and merging data based on specific criteria, handling of building count and occupancy types, and data export.


#### 3. county_dash
- **Title**: county_dash
- **Description**: Dedicated to creating dashboards for county-level data. It includes data loading, processing, and visualization. The notebook emphasizes interactive features for better data understanding and representation.
- **Key Code Elements**: Data loading, manipulation, and visualization, interactive dashboard creation, functions for data processing, and graphical representation of county data.
<a name="county_dash"></a>

#### 4. Documentation
- **Title**: Documentation
- **Description**: Serves as a documentation resource, providing detailed explanations and instructions for various data processing tasks. It includes examples and guidelines for users to follow.
- **Key Code Elements**: Markdown cells with detailed explanations, code snippets for demonstration, guidance on data handling techniques, and example-based learning.

<a name="documentation"></a>

#### 5. Hazua_CA_data_sum

- **Title**: Hazua_CA_data_sum
- **Description**: This notebook is centered around summarizing and analyzing data specific to California. It includes various data aggregation techniques and focuses on deriving meaningful insights from the summarized data.
- **Key Code Elements**: Data aggregation methods, analysis of California-specific data, use of statistical techniques for data summarization, and insights extraction.
![Emeryville Footprint ](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/assets/89886448/da8d54c5-5057-4ca6-85f0-9e6b255dbb30)
![Emeryville Hazus Building Block Score](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/assets/89886448/e8c2da89-d581-4cc4-8d6a-7b7468c370da)
![Emeryville Hazus Building Block Difference Score](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/assets/89886448/c06e18ce-6201-45f3-ae98-47aeda70f60b)
<a name="hazua_ca_data_sum"></a>

#### 6. Hazuz_NY_sum
<a name="hazuz_ny_sum"></a>
- **Title**: Hazuz_NY_sum
- **Description**: Focuses on data summary and analysis for New York. It involves complex data processing steps, aiming to provide a comprehensive overview of various data points related to New York.
- **Key Code Elements**: Advanced data processing techniques, summary of New York-specific data, detailed analysis and interpretation of results, and data visualization methods.
![Park Slope Footprint](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/assets/89886448/0c795546-3b9e-4ae7-a14a-a7e1b5240015)
![Park Slope Hazus Building Block Score](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/assets/89886448/34565bf4-3690-403b-9f9b-a6c57682072e)
![Park Slope Hazus Building Block Difference Score](https://github.com/czz129/NHERI_Simcenter_Hazus_Project/assets/89886448/e5241d24-db99-4860-844a-4e5b526f3ecd)

#### 7. Master_sum
<a name="master_sum"></a>
- **Title**: Master_sum
- **Description**: Aimed at providing a master summary of various datasets. It integrates data from multiple sources, offering a holistic view and aiding in overarching data analysis tasks.
- **Key Code Elements**: Integration of multiple datasets, comprehensive data analysis techniques, summarization of findings, and methods for handling large-scale data.

---



Acknowledgments
This project makes use of data from the HAZUS Database. We acknowledge the creators and maintainers of this database for their valuable contributions to the field.

License
[]

