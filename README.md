# Data-cleaning-Customer-churn-data-analysis
This project focuses on cleaning and preparing a customer churn dataset using Python and the pandas library in Google Colab. The aim is to convert raw, unstructured data into a clean, reliable dataset ready for analysis, visualization, and predictive modeling.
The project reflects a real-world data cleaning workflow commonly used by data analysts before performing churn analysis, dashboard reporting, and machine learning tasks.
## Tools and Technologies Used
This project was completed entirely in Google Colab using Python and the pandas library. The openpyxl engine was used for handling Excel files. Google Drive was used for file storage and exporting cleaned datasets.
## Dataset Overview
The dataset used in this project is from the Lloyds Bank Virtual Experience programme on the Forage platform. It simulates a real-world customer churn business scenario.
The dataset consists of multiple Excel worksheets representing different aspects of customer behavior, including:
customer_demographics
customer_service
transaction_history
online_activity
churn_status
Each worksheet was cleaned separately to ensure accuracy, consistency, and data integrity before further analysis.
## Data Cleaning Process
The following structured data cleaning steps were applied to every worksheet in the dataset:
1. Load the dataset into pandas using multi-sheet Excel handling
2. Perform basic inspection using .info() and .head()
3. Remove duplicated records
4. Correct and standardise data types (especially date and numerical fields)
5. Handle missing values appropriately based on business meaning
6. Standardise categorical values (for example: gender, marital status, churn labels)
7. Check categorical fields for consistency and unexpected values
8. Perform feature engineering for analysis (such as recency, frequency, and derived indicators)
9. Save the fully cleaned dataset into new Excel output files 
## Files in This Repository
- [ Customer_churn_data.ipynb]( Customer_churn_data.ipynb)
- [Customer_Churn_Data_Large-2.xlsx]( Customer_Churn_Data_Large-2.xlsx)
- [Customer_churn_clean_data.xlsx](Customer_churn_clean_data.xlsx)
## Output Files
The final output of this project is a cleaned Excel dataset stored in Google Drive. This dataset is ready for use in exploratory data analysis, customer behavior analysis, churn prediction modeling, and business intelligence dashboards.
## How to Run This Project
To run this project, you need both the raw Excel dataset and the pandas cleaning notebook.
First, download or clone this GitHub repository. It contains:
- [Customer_churn_data.ipynb](Customer_churn_data.ipynb)
- [Customer_Churn_Data_Large-2.xlsx]( Customer_Churn_Data_Large-2.xlsx)
Next, upload the raw Excel dataset to your Google Drive, or directly into Google Colab. If using Google Drive, mount it using:
`from google.colab import drive
drive.mount("/content/drive")`
Update the file path in the notebook to match your Drive location:
`file_path = "/content/drive/MyDrive/Customer_Churn_Data_Large-2.xlsx"`
Run the notebook cells in order to execute the full data cleaning process. The cleaned Excel files will be automatically saved to your Google Drive.
If you prefer not to use Google Drive, you can upload the raw Excel file directly into Colab and update the file path accordingly. After the script finishes, you can download the cleaned Excel file directly to your computer.
## Key Learning Outcomes
This project strengthened practical skills in real-world data cleaning, working with multi-sheet Excel files using pandas, handling missing values and duplicates, standardizing categorical variables, converting date formats, and managing files efficiently in Google Colab.
# Author
This project was completed as part of my data analytics learning journey, with a focus on building strong data preparation skills for real business applications.

