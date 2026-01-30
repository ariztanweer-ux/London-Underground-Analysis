# London-Underground-Analysis
Analysis of London Underground passenger usage by borough (2001–2025) with per-capita insights, trends, and visualizations using Python and Colab.
London Underground Analysis (2001–2025)

This project analyzes London Underground usage across boroughs over the period 2001–2025. Using historical passenger data and population statistics, the analysis explores trends, per-capita usage, and insights for future commuting patterns and infrastructure planning.



# Project Overview

The London Underground is a complex, heavily used transit network. This project focuses on understanding how different boroughs contribute to per-capita Tube usage, how travel patterns have shifted over time (especially post-pandemic), and which areas are likely to see growth in the future. Key outcomes include:
	•	Identifying boroughs with the highest per-capita usage.
	•	Understanding the effects of hybrid work and modal shifts.
	•	Highlighting potential areas for infrastructure expansion or improved connectivity.



# Data Sources
	•	Tube passenger data: Annual entries and exits at each station (1997–2025, London stations subset).
	•	Population data: Borough-level population statistics from official UK datasets.

The datasets have been cleaned, merged, and converted into a long format suitable for analysis. The final dataset includes per-capita passenger numbers for each borough-year combination.

# Project Structure:
	•	London_Underground_Analysis/ – Main project folder / GitHub repository
	•	cleaned_borough_data.csv – Final cleaned dataset with merged Tube passengers and population data
	•	London_Underground_Analysis.ipynb – Colab notebook with full data cleaning, analysis, and visualizations
	•	README.md – Project explanation and documentation


  # Analysis Steps
	1.	Data Loading: Loaded population CSV and Tube passenger ODS datasets.
	2.	Data Cleaning:
	•	Standardized column names, removed extra characters and spaces.
	•	Filtered only London stations and boroughs.
	•	Converted wide data to long format for aggregation.
	•	Converted passenger numbers to numeric, handled missing values.
	3.	Data Aggregation:
	•	Aggregated passengers per borough-year.
	•	Aggregated population per borough-year.
	•	Merged datasets to calculate passengers per 1000 residents.
	4.	Exploratory Analysis:
	•	Quick EDA, missing value checks, summary statistics.
	5.	Visualization & Insights:
	•	Trends in per-capita usage across boroughs (2001–2025).
	•	Insights on central dominance, inner London growth, outer borough stability, regeneration zones, and post-pandemic commuting changes.
	6.	Future Trends:
	•	Forecasts and strategic insights for borough-level Tube demand.
	•	Identified areas with potential for infrastructure or service expansion.

⸻

# Key Observations
	•	The City of London dominates per-capita Tube usage due to a tiny resident population and massive workforce.
	•	Inner London boroughs show steady growth, resilient to hybrid work trends.
	•	Outer boroughs remain stable, with cars and National Rail still primary.
	•	Regeneration zones like Stratford and Docklands are growing but per-capita usage remains low.
	•	Long-term travel patterns are shifting to flexible hours, off-peak usage, and alternative transit modes.

  # How to Use
	1.	Clone the repository: git clone <repository_url>
    2.	Open the notebook in Google Colab:
	•	notebooks/London_Underground_Analysis.ipynb
	3.	Ensure data/cleaned_borough_data.csv is in the correct folder.
	4.	Run the notebook to reproduce analysis, visualizations, and insights.

  # License

This project is for educational and research purposes. Data sources are cited in the notebook.
  
