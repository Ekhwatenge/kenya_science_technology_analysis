# Kenya Science and Technology Intellectual Property Analysis (2019-2022)
# Overview
This project analyzes science and technology indicators for Kenya, focusing on charges related to the use of intellectual property between 2019 and 2022. This analysis aims to identify trends, generate summary statistics, and visualize the data to offer insights into the country's progress in the science and technology sector.

The analysis is performed using R and presented in an R Markdown report. It covers data cleaning, preprocessing, trend analysis, and summary statistics. The results are intended to inform policymakers, researchers, and stakeholders in Kenya's science and technology sectors and guide evidence-based decision-making.

# Project Structure
Data: Raw data is stored in CSV format and is included in the repository.
R Markdown Report: The main analysis is documented in an R Markdown file (kenya_science_technology_analysis.Rmd), which can be rendered into an HTML or PDF report.
Outputs: Cleaned data, summary statistics, and visualizations are saved as CSV and image files, respectively.
# Files and Directories
science_and_technology_ken.csv - The raw dataset containing indicators for Kenya's science and technology sector.
cleaned_science_and_technology_ken.csv - The cleaned dataset after data preprocessing.
summary_statistics_ken.csv - The output containing summary statistics of key indicators.
kenya_science_technology_analysis.Rmd - The R Markdown file containing the analysis code and narrative.
README.md - This readme file explaining the project structure and details.
outputs/ - Directory containing plots and figures generated from the analysis.

# Analysis
The analysis consists of the following steps:
Data Cleaning: Remove irrelevant rows, rename columns, and convert data types for numerical analysis.
Summary Statistics: Calculation of mean, median, minimum, and maximum values for each indicator.
Trend Visualization: Graphical representation of trends in the indicators over time using line plots.
Saving Results: Cleaned data and summary statistics are saved as CSV files for further use.

# How to Run the Analysis
To run this analysis, ensure you have R installed and the necessary packages. Follow these steps:

Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/yourusername/kenya-science-technology-analysis.git
Install the required R packages:

r
Copy code
install.packages(c("tidyverse", "ggplot2", "dplyr"))
Open the R Markdown file in RStudio or your preferred R environment:

r
Copy code
rmarkdown::render("kenya_science_technology_analysis.Rmd")
The rendered report will be generated in HTML or PDF format, displaying the analysis results.

# Requirements
R (Version 4.0 or later)
R Packages: tidyverse, ggplot2, dplyr, rmarkdown
License
This project is licensed under the MIT License. See the LICENSE file for more details.

# Author
Elvira Khwatenge

