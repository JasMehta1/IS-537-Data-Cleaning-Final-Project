# IS-537-Data-Cleaning-Final-Project

#Data Cleaning and Profiling Project
This project aims to assess and clean a dataset containing course information, followed by profiling and data exploration. The cleaned dataset has been derived from raw course data obtained through web scraping and other data extraction processes. This README provides an overview of the project structure, its contents, and how to use the provided files.

merged_cleaned_final.csv: The final, cleaned dataset containing courses with standardized formatting and removed duplicates. This is the primary dataset used for analysis after data cleaning.

# Data_Profiling/
This directory includes the output of data profiling, which provides detailed insights into the dataset's structure, including statistics on missing values, data types, and distribution of values.

.DS_Store: A system file used by macOS to store folder attributes (can be ignored).

uiuc_cleaned_merged_profile.html: A profile of the cleaned dataset, showcasing detailed statistics and information about the data's structure.

uiuc_unclean_merged_profile.html: A profile of the original uncleaned dataset, used for comparison to the cleaned dataset.

# Extracted_Files/
This folder contains the raw and intermediate datasets extracted from multiple sources before cleaning.

.DS_Store: A system file used by macOS to store folder attributes (can be ignored).

1_filtered_gpa_sp_fa_after_2017.csv: A filtered version of the course data that only includes GPA data after 2017.

2_merged_uiuc_courses_gpa.csv: A merged dataset of UIUC courses that includes GPA data.

courses_processed-2.csv: Another processed version of the course data after cleaning steps.

# Jupyter-Notebooks/
This folder contains Jupyter notebooks used for data extraction, cleaning, and profiling.

.DS_Store: A system file used by macOS to store folder attributes (can be ignored).

1-Course_Scrapper.ipynb: The notebook used for web scraping data from the UIUC course catalog.

2-Data_Extraction_Cleaning.ipynb: The notebook used for cleaning and transforming the extracted course data.

2_Data_Profiling.ipynb: The notebook used for profiling the cleaned and uncleaned datasets, providing insights into their structure.

.DS_Store
These are system files created by macOS to store folder attributes. They can be safely ignored and are not part of the project.

.gitattributes
This file contains settings related to how Git handles various file types in the repository.

README.md
This file, which provides an overview of the project structure and explains the contents of the directories and files.

# Run the Notebooks:

1-Course_Scrapper.ipynb: Use this notebook to scrape data from the UIUC course catalog.

2-Data_Extraction_Cleaning.ipynb: Use this notebook to clean and process the raw data.

2_Data_Profiling.ipynb: Use this notebook to profile and explore both the uncleaned and cleaned datasets.

# Analyze the Data:

The cleaned dataset (merged_cleaned_final.csv) can be used for further analysis, such as trend analysis, academic course offering analysis, and more.

The profiling outputs (uiuc_cleaned_merged_profile.html and uiuc_unclean_merged_profile.html) provide an in-depth look at the data structure.

# Explore the Extracted Files:

The extracted files contain intermediate datasets that were processed before the final cleaned version was generated. These can be useful for comparing the data at different stages of cleaning.

# Conclusion
This project demonstrates a comprehensive data cleaning workflow that involves data extraction, cleaning, profiling, and web scraping. It provides a cleaned and structured dataset for further analysis of course-related data, which can be used for decision-making or academic research.
