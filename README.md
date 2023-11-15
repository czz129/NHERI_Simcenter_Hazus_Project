# NHERI_Simcenter_Hazus_Project

## Project Description

## Contributors
- Zizhuo (Tina) Chen
- Adam Zsarnóczay

Installation Instructions
This project utilizes datasets from the HAZUS Database. To get started, you do not need to install any additional software or datasets. Simply use the notebook developed for this project.

## Notebooks
Here is a table listing all the notebooks along with a one-line description for each:

| Notebook Title                                                | Notebook Description                                                          |
|---------------------------------------------------------------|-------------------------------------------------------------------------------|
| BuildingType                   | Focuses on data loading, cleaning, simulation, and sampling for building types.|
| CA_WA_OR_hzBldgCountOccupB_T_table                       | Processes building count and occupancy data for CA, WA, and OR.               |
| county_dash                                         | Creates dashboards for county-level data with interactive features.           |
| Documentation           | Serves as a documentation resource with explanations and instructions with tables in the Processed data        |
| Hazua_CA_data_sum                                         | Centers on summarizing and analyzing data specific to California.             |
| Hazuz_NY_sum                                          | Focuses on data summary and analysis for New York.                           |
| Master_sum                                          | Provides a master summary of various datasets for overarching analysis.       |

Note: Some notebooks do not have clearly defined titles or the titles were extracted from the first markdown cell, which might not always be the actual title of the notebook.

#### 1. BuildingType
- **Title**: BuildingType
- **Description**: Focuses on data loading, cleaning, simulation, and sampling for building types. It processes state, FIPS code, and county information, combining data from various tables like BuildingCount, Demographics, and TIGERCensusBlock. It categorizes building rises for material assignment.
- **Key Code Elements**: Package installations, Google Drive mounting, state and county variables, CSV file reading, GeoDataFrame creation, functions for filtering tables, and building material generation.

#### 2. CA_WA_OR_hzBldgCountOccupB_T_table
- **Title**: CA_WA_OR_hzBldgCountOccupB_T_table
- **Description**: This notebook focuses on processing building count and occupancy data for California, Washington, and Oregon. It includes data manipulation and merging techniques, emphasizing the handling of specific building occupancy types and counts.
- **Key Code Elements**: Reading and processing of CSV files, filtering and merging data based on specific criteria, handling of building count and occupancy types, and data export.

#### 3. county_dash
- **Title**: county_dash
- **Description**: Dedicated to creating dashboards for county-level data. It includes data loading, processing, and visualization. The notebook emphasizes interactive features for better data understanding and representation.
- **Key Code Elements**: Data loading, manipulation, and visualization, interactive dashboard creation, functions for data processing, and graphical representation of county data.

#### 4. Documentation
- **Title**: Documentation
- **Description**: Serves as a documentation resource, providing detailed explanations and instructions for various data processing tasks. It includes examples and guidelines for users to follow.
- **Key Code Elements**: Markdown cells with detailed explanations, code snippets for demonstration, guidance on data handling techniques, and example-based learning.

#### 5. Hazua_CA_data_sum
- **Title**: Hazua_CA_data_sum
- **Description**: This notebook is centered around summarizing and analyzing data specific to California. It includes various data aggregation techniques and focuses on deriving meaningful insights from the summarized data.
- **Key Code Elements**: Data aggregation methods, analysis of California-specific data, use of statistical techniques for data summarization, and insights extraction.

#### 6. Hazuz_NY_sum
- **Title**: Hazuz_NY_sum
- **Description**: Focuses on data summary and analysis for New York. It involves complex data processing steps, aiming to provide a comprehensive overview of various data points related to New York.
- **Key Code Elements**: Advanced data processing techniques, summary of New York-specific data, detailed analysis and interpretation of results, and data visualization methods.

#### 7. Master_sum
- **Title**: Master_sum
- **Description**: Aimed at providing a master summary of various datasets. It integrates data from multiple sources, offering a holistic view and aiding in overarching data analysis tasks.
- **Key Code Elements**: Integration of multiple datasets, comprehensive data analysis techniques, summarization of findings, and methods for handling large-scale data.

---

Each notebook has a unique focus and set of key code elements, tailored to specific data processing and analysis tasks. If you require more detailed information on any specific notebook, please let me know!


Acknowledgements
This project makes use of data from the HAZUS Database. We acknowledge the creators and maintainers of this database for their valuable contributions to the field.

License
[Specify the license under which this project is released, if applicable.]

