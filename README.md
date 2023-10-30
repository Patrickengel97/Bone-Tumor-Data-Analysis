# Data Analysis Project - Bone Tumor Data

This project analyzes data related to bone tumors in different patients. The dataset used in this project is the "Bone Tumor" dataset from the Memorial Sloan Kettering Cancer Center (MSKCC).

## About the Bone Tumor Dataset

The "Bone Tumor" dataset includes the following data fields:

- **Patient ID**: A unique identifier for each patient.
- **Sex**: The patient's sex.
- **Age**: The patient's age at the time of diagnosis.
- **Grade**: The grade of the tumor, which is a measure of how aggressive the tumor is.
- **Histological type**: The type of tumor, such as osteosarcoma or Ewing sarcoma.
- **MSKCC type**: The MSKCC type of the tumor, which is a more specific classification of the tumor.
- **Site of primary STS**: The location of the tumor in the bone.
- **Status (NED, AWD, D)**: The patient's status, which can be NED (no evidence of disease), AWD (alive with disease), or D (dead).
- **Treatment**: The treatment that the patient received, such as surgery, radiation therapy, or chemotherapy.

You can access the original dataset from [Kaggle](https://www.kaggle.com/datasets/antimoni/bone-tumor?resource=download).

## Project Phases

This project is divided into three phases, each aimed at analyzing and gaining insights from the Bone Tumor dataset:

- **Phase 1: Data Download and MongoDB**: Downloading the dataset and storing it in a MongoDB database.
- **Phase 2: Data Extraction and SQLite**: Extracting data from MongoDB, cleaning it, and storing it in an SQLite database.
- **Phase 3: Data Analysis and Visualization**: Analyzing the data, calculating statistics, and creating visualizations to support problem diagnosis.

For more detailed information about each phase and the code used in this project, please refer to the respective sections below.

## Phase 1 Details

### Data Download and MongoDB

- Download the .csv file.
- Write the data to a MongoDB collection running on Atlas.
- Write all the data to a local text file as valid JSON data.
- Validate that the data has been written to MongoDB correctly.
- Provide information about the data to the user, including details on the download process and data source.

## Phase 2 Details

### Data Extraction and SQLite

- Use knowledge of JSON, SQLite databases, and security to run a data modeling and cleaning process.
- Extract necessary information from the retrieved JSON data and write it to a SQLite database.
- Read rough/raw data from MongoDB downloads or a local JSON file.
- Focus on extracting only the fields relevant to the planned data analysis task.
- Wipe out and re-build the SQLite database each time the program runs, allowing adjustments to parameters and mapping tables.
- Validate individual data values are of the correct type before writing to SQLite.
- Implement error handling procedures for records that do not contain all possible fields.

## Phase 3 Details

### Data Analysis and Visualization

- Extract relevant data from the SQLite database.
- Load the data into a Pandas DataFrame and display some of the data.
- Use appropriate methods to get a summary of the DataFrame and identify missing values.
- Perform at least three different types of data analysis tasks on the dataset.
- Create at least three different types of visualizations to support data analysis.

## Additional Files
- [Bone_Tumor.db](Bone_Tumor.db)
- [Analysis Report for Bone Tumors](https://github.com/Patrickengel97/Bone-Tumor-Data-Analysis/blob/main/Analysis%20Report%20for%20Bone%20Tumors.pdf)

Please access the code and documentation in this repository for more information on each phase of the project.
