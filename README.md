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
- Visualize findings using interactive dashboards to showcase cases filed by year, race, and other variables.

## Key Features

### Interactive Dashboards

This project includes several interactive dashboards that allow users to explore the crime data in depth:

- **Cases Filed by Year**: View the total number of cases filed over the years.
- **Cases Filed by Race**: Analyze how arrests and cases vary based on the race of the arrestees.
- **Total Cases Filed**: A quick overview of the total number of cases filed over the dataset's timeframe.
- **Crime Type Breakdown**: Explore the types of offenses committed and their trends.
- **Arrestee Demographics**: Analyze trends based on the demographics of arrested individuals (e.g., age, gender, race).

These dashboards are built using **Excel**'s built-in features like PivotTables, PivotCharts, and Slicers to make the data exploration interactive.

### How to Interact with Dashboards

1. Open the dataset in **Microsoft Excel**.
2. Navigate to the dashboard sheet (usually named something like "Dashboard" or "Summary").
3. Use the **Slicers** or **PivotTable filters** to explore the data by year, race, charge type, etc.
4. Click on various chart elements (e.g., bars or pie segments) to drill down into more specific data.
5. You can update these dashboards by refreshing the data or by modifying the PivotTables as new information becomes available.

## Technologies Used

- **Microsoft Excel** for data cleaning, exploration, and analysis.
- **Excel Dashboards** for interactive visualizations.

## How to Use

1. **Download the dataset** from [Kaggle](https://www.kaggle.com/datasets/mattop/arrests-in-the-city-of-chicago-2014-2023).
2. Open the dataset in **Microsoft Excel**.
3. Navigate to the dashboard sheet in Excel to start interacting with the data.
4. Use the provided slicers and filters to explore crime trends by year, race, offense, etc.
5. Optionally, use Jupyter Notebooks or Python scripts to perform advanced analysis if needed.

## Data Sources

- [Chicago Crime Data on Kaggle](https://www.kaggle.com/datasets/mattop/arrests-in-the-city-of-chicago-2014-2023)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
