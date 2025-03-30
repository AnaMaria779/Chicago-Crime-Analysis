# Chicago Crime Analysis

## Project Overview

This project analyzes crime data from the city of Chicago spanning the years 2014 to 2023. The data is sourced from Kaggle and contains information on arrests in Chicago, including types of offenses, the location of crimes, and the demographic details of the individuals arrested. The goal of this analysis is to uncover patterns, trends, and insights that may help with understanding crime distribution and arrest patterns in the city.

The dataset can be found here: [Chicago Crime Data on Kaggle](https://www.kaggle.com/datasets/mattop/arrests-in-the-city-of-chicago-2014-2023)

## Dataset Overview

The dataset consists of the following columns:

- **ID**: Unique identifier for each record.
- **Date**: Date and time of the arrest.
- **Arrest Type**: The type of arrest (e.g., on-site, warrant).
- **Offense**: The crime or offense committed (e.g., theft, assault).
- **Location**: Location of the incident (can be specified by district, neighborhood, etc.).
- **Arrestee Age**: Age of the individual arrested.
- **Arrestee Gender**: Gender of the individual arrested.
- **Arrestee Race**: Race of the individual arrested.
- **Arresting Agency**: The agency responsible for the arrest (e.g., Chicago Police Department).
- **Charge**: Charge made against the arrested individual.

## Project Objectives

- Analyze crime trends in Chicago over the past decade.
- Explore relationships between crime types, locations, and demographics.
- Identify areas with the highest crime rates.
- Explore temporal patterns in crimes (e.g., time of year, day of the week, etc.).
- Visualize findings using charts, graphs, and other data visualization tools.

## Technologies Used

- **Microsoft Excel** for data cleaning, exploration, and analysis.
- **Python** for advanced analysis
- **Data Visualization Libraries** 

## File Structure

- **`data/`**: Directory containing raw and processed datasets.
  - `chicago_crime_data.xlsx`: The main dataset for crime and arrest information.
- **`notebooks/`**: Directory for Jupyter Notebooks or analysis files.
  - `crime_analysis.ipynb`: Jupyter Notebook containing analysis code and visualizations.
- **`README.md`**: This file, providing an overview of the project.

## How to Use

1. **Download the dataset** from [Kaggle](https://www.kaggle.com/datasets/mattop/arrests-in-the-city-of-chicago-2014-2023).
2. Open the dataset in **Microsoft Excel** to begin your analysis, or if you prefer Python-based analysis, import the dataset using `pandas` in Jupyter Notebook.
3. Explore the data and apply the analysis techniques mentioned in the project objectives to gain insights into crime patterns.

## Data Sources

- [Chicago Crime Data on Kaggle](https://www.kaggle.com/datasets/mattop/arrests-in-the-city-of-chicago-2014-2023)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
