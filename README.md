# Soil Analysis and Crop Recommendation Project

Overview

This project is designed to analyze soil data and recommend suitable crops based on soil properties such as fertility, moisture, and pH levels. It uses Python to process the data, generate insights, and visualize the results. The final output is a professionally formatted PDF report containing various charts and recommendations.

Features

Data Simulation: Generates synthetic soil data for demonstration purposes.

Crop Recommendation: Provides crop recommendations based on soil properties.

Data Visualization:

Bar Chart: Soil fertility levels.

Scatter Plot: Relationship between pH, moisture, and crop recommendations.

Pie Chart: Distribution of crop recommendations.

Histogram: Distribution of moisture levels.

Heatmap: Correlation between soil properties.

PDF Report: Consolidates all visualizations into a single PDF file.

Requirements

Libraries

pandas: For data manipulation and analysis.

numpy: For numerical operations.

matplotlib: For creating visualizations.

seaborn: For advanced data visualization.

matplotlib.backends.backend_pdf (PdfPages): For saving visualizations in PDF format.

Install these libraries using:

pip install pandas numpy matplotlib seaborn

Dataset

Synthetic Data: The project generates a dataset with the following columns:

Soil_ID: Unique identifier for each soil sample.

Fertility_Level: Fertility percentage (range: 50-100).

Moisture_Level: Moisture percentage (range: 20-80).

pH_Level: Soil pH value (range: 5.5-8.0).

Code Explanation

1. Import Libraries

Essential libraries for data analysis and visualization.

2. Generate Soil Data

Creates synthetic soil data for analysis using numpy and stores it in a pandas DataFrame.

3. Crop Recommendation Function

Defines logic to recommend crops based on pH and moisture levels.

4. Data Visualization

Bar Chart: Highlights fertility levels of soil samples.

Scatter Plot: Visualizes pH and moisture levels with crop recommendations.

Pie Chart: Shows the proportion of each recommended crop.

Histogram: Displays the distribution of soil moisture levels.

Heatmap: Correlation between fertility, moisture, and pH.

5. PDF Report Generation

Compiles all visualizations into a single PDF for easy sharing.

How to Run

Clone or download the project files.

Ensure Python and required libraries are installed.

Execute the script in your IDE or Jupyter Notebook.

Locate the generated Soil_Analysis_Report.pdf in your working directory.

Output

The PDF report includes:

Soil fertility trends.

Crop recommendations based on pH and moisture levels.

Distribution and correlation insights of soil properties.

Applications

Farm management and decision-making.

Precision agriculture solutions.

Academic and research purposes in soil science.

Enhancements

Replace synthetic data with real-world soil data.

Integrate with APIs for weather or soil sensor data.

Add a machine learning model for advanced crop prediction.

Author

Developed by Darshana Pawar. For questions or suggestions, feel free to reach out at darshanapawar811@gmail.com

