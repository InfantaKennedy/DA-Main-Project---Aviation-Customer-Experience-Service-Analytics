# ✈️ Aviation Customer Experience & Service Analytics
## 📌 Project Description
A data analytics project focused on analyzing airline customer reviews to understand customer satisfaction, service performance, recommendation patterns, and trends in airline customer experience.
The analysis uses Python for data cleaning, transformation, and exploratory data analysis, followed by Power BI for dashboard development and business insights. 

Analysis Period: 2021–2025
## 📊 Dataset
Original Dataset: Airline Travel Reviews Data (Skytrax)

Original Dataset Size: 64,740 rows × 19 columns

🔗 **Original Source:**  [Mendeley Data – Skytrax Airline Review Data](https://data.mendeley.com/datasets/vgjk58vf8h/1)

DOI: 10.17632/vgjk58vf8h.1

 

Dataset Used for Analysis: 21,984 rows × 19 columns

Analysis Period: 2021–2025

Format: CSV

📥 **Raw Source:** 
https://github.com/InfantaKennedy/DA-Main-Project---Aviation-Customer-Experience-Service-Analytics/blob/main/Skytrax%20Airline%20Review%20Data(2021-2025)%20-%20Raw%20File.csv


The analysis focuses on reviews from 2021–2025. The aircraft column is excluded during preprocessing due to substantial missing and inconsistent values.

### Dataset Attribution

> Airline Travel Reviews Data (Skytrax), Mendeley Data, DOI: `10.17632/vgjk58vf8h.1

## Dependencies

The following tools and libraries are required to run or reproduce this project:

- Python 3.x
- Google Colab / Jupyter Notebook
- Microsoft Power BI Desktop
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Excel / CSV
- Windows 10 or later

## Installing

1. Clone or download this repository.

2. Open the Python notebook in:
   - Google Colab, or
   - Jupyter Notebook

3. Install the required Python libraries if they are not already available:
pip install pandas numpy matplotlib seaborn

4. Place the dataset in the appropriate project folder or upload it to Google Colab.

5. Open the Power BI .pbix file using Power BI Desktop to explore the interactive dashboard.

 **Dataset Attribution:**

Airline Travel Reviews Data (Skytrax), Mendeley Data, DOI: 10.17632/vgjk58vf8h.1.

## ▶️ Executing program

### 🐍 Python Analysis
1. Open the project notebook.
2. Import the required Python libraries.
3. Load the Skytrax Airline Review dataset.
4. Perform data cleaning and preprocessing.
5. Conduct exploratory data analysis.
6. Create statistical summaries and visualizations.
7. Generate insights from the analysis.
8. Export the cleaned dataset for Power BI.
   
### 📊 Power BI Dashboard
1. Open the cleaned CSV file in Power BI Desktop.
2. Load the cleaned dataset.
3. Verify the data types and records.
4. Create the required DAX measures.
5. Build the dashboard visualizations.
6. Use the available slicers to interact with the dashboard.
### The dashboard contains:
- KPI Cards
- Overall Rating Distribution
- Customer Recommendation
- Top 10 Airlines by Review Volume
- Average Overall Rating by Seat Type
- Average Overall Rating by Traveller Type
- Customer Satisfaction Trend
- Service Performance by Area
- Service Drivers vs Overall Rating
- Service Performance by Seat Type
- Recommendation Rate by Seat Type
- Key Insights and Recommendations

## 🔍 Help
Common Issues
- Ensure the dataset path is correct before loading the file.
- Check that date columns are converted to the correct datetime format.
- Verify that numerical rating columns are stored as numeric values.
- Missing values are retained as NaN/NaT where applicable.
- If Power BI displays CSV import errors, verify the CSV delimiter, encoding, and quotation settings.
- Make sure the Power BI source contains the final cleaned dataset with 21,984 records.
For Power BI analysis, the overall customer rating is measured on a 1–10 scale, while individual service ratings are measured on a 1–5 scale.

## 👤 Authors

Infanta Kennedy 

Data Analytics Project

## Skills demonstrated:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL
- Power BI
- DAX
- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Business Insights
  
## 📝 Version History
Version 1.0
  - Completed data cleaning and preprocessing
  - Completed exploratory data analysis
  - Created Python visualizations
  - Developed interactive Power BI dashboard
  - Added DAX measures and KPIs
  - Added insights and recommendations
  - Finalized project documentation

## 📄 License
This project is intended for educational and portfolio purposes.
The original dataset is attributed to the Airline Travel Reviews Data (Skytrax) available through Mendeley Data.
Please refer to the original dataset source for its licensing, attribution, and usage terms.

## 🙏 Acknowledgments
- Skytrax Airline Review Dataset for providing the customer review data.
- Mendeley Data for hosting the original dataset.
- Python and its data analytics libraries for data cleaning, analysis, and visualization.
- Microsoft Power BI for interactive dashboard development.
- Entri Elevate and Illinois Tech for the Data Analytics learning program and project guidance.

## 🎯 Project Outcome
The project transformed raw airline customer review data into meaningful insights using Python and Power BI.
The analysis identified important patterns in customer satisfaction, service performance, recommendation behaviour, and passenger segments. The final interactive dashboard provides a data-driven view of airline customer experience and highlights key areas for service improvement.
