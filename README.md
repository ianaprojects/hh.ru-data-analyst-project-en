# Research on Entry-Level Data Analyst Jobs in Russia on hh.ru: Skills, Salary Trends, and Job Geography
## [Link to Jupyter Notebook](https://github.com/ianaprojects/hh.ru-data-analyst-project-en/blob/main/hh_project_script_en.ipynb)
## Project Description
This project analyzes job openings for entry-level and junior data analyst positions using data from the popular Russian job platform hh.ru. 
The goal of this project is to analyze data analyst job openings with a focus on entry-level and junior positions. Using data from the popular Russian job platform hh.ru, the project seeks to gather insights into the skills required and the salary levels associated with junior data analyst roles.


The project includes the following steps:

1. **Data Collection**: Using the `requests` library and API queries, data on job vacancies is gathered from hh.ru.
2. **Data Preprocessing**: The collected data is cleaned, filtered, and transformed using the `pandas` library to ensure accuracy and facilitate analysis.
3. **Data Analysis**: With the help of `pandas`, `matplotlib.pyplot`, and other tools, the data is analyzed to investigate popular skills, salary trends, job distribution by city, and other relevant aspects.
4. **Visualization of Results**: Graphs and visualizations are created using `matplotlib.pyplot` and `folium` libraries to visually represent the data and discover patterns.

Through exploratory data analysis, the project aims to answer the following questions:
* What skills are most commonly required in job descriptions for entry-level data analysts?
* Are there geographic differences in the availability of entry-level data analyst jobs?
* What is the salary range for junior data analysts, and how does it vary across cities?

The project's findings will help provide a better understanding of the job market for entry-level data analysts, assessing the required skills, geographic availability, and salary expectations. These insights may also be valuable to others interested in the field of data analytics and seeking to learn more about entry-level data analyst job opportunities.

## Prerequisites

To run the project, you will need to install the following Python libraries:
* requests
* BeautifulSoup
* numpy
* pandas
* matplotlib
* folium

Additionally, you'll need Jupyter Notebook. You can install it by following the instructions on the official [Jupyter](https://jupyter.org/install) website.

Once all dependencies are installed and Jupyter Notebook is set up, you can run the `hh_project_script.ipynb` file to execute the project.

## Project Methodology
This project is fully implemented in Python using Jupyter Notebook for convenient code execution and data visualization.

The following Python libraries were used to achieve the project's goals:
* `requests`: A library for sending HTTP requests to the [API](dev.hh.ru) to retrieve data in JSON format.
* `time`: A library for managing time and delays.
* `BeautifulSoup`: A library for extracting data from HTML and XML files, used for parsing information.
* `numpy`: A library for performing computations using arrays and matrices, providing numerous mathematical functions.
* `pandas`: A library for data manipulation that enables the creation and manipulation of DataFrames for data analysis and representation.
* `matplotlib.pyplot`: A library for creating graphs and visualizing data.
* `folium`: A library for creating interactive maps and visualizing geographic data.

Additionally, the `matplotlib.ticker` module was used to customize tick formats and labels on the graphs.

These libraries and modules ensure efficient data processing and analysis within the project, along with the creation of high-quality visualizations.

## Project Structure
1. `hh_project_script.ipynb`: A Jupyter Notebook file containing the main project code.
2. `hh_project_russian_cities_towns_geo.xlsx`: A file with geolocation data of Russian cities, used in the project.
3. `hh_project_raw.xlsx`: A file with raw vacancy data, generated during code execution.
4. `hh_project_cleaned.xlsx`: A file with cleaned vacancy data, generated during code execution.

## Disclaimer
This project represents personal work by an aspiring data analyst and was created for personal learning and to assess the job market. The project results reflect my own conclusions and may not accurately represent the broader labor market.
