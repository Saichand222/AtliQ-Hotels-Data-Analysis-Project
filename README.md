AtliQ Hotels Grand Data Analysis

This project focuses on analyzing hotel booking data for AtliQ Hotels using Python.
The goal of this project is to explore booking trends, analyze hotel performance, and derive insights from multiple datasets related to hotel operations.

The analysis includes data exploration, booking trends, occupancy insights, and property performance using Python data analysis libraries.

Project Structure

. data/: Contains the hotel datasets used for analysis.
. notebooks/: Jupyter Notebook used for performing data analysis.
. scripts/: Python scripts used for data processing and analysis.
. requirements.txt: Lists the required Python libraries for the project.
. README.md: Project documentation and setup instructions.


Datasets

This project uses the following datasets:

. dim_date.csv
. dim_hotels.csv
. dim_rooms.csv
. fact_aggregated_bookings.csv
. fact_bookings.csv

These datasets contain information about hotel properties, room types, booking details, and aggregated booking statistics.



Tools and Technologies Used

. Python
. Pandas
. NumPy
. Jupyter Notebook
. Data Visualization Libraries (Matplotlib / Seaborn)


Analysis Performed

The project includes the following analysis tasks:

. Data import and exploration
. Understanding hotel property data
. Analyzing booking trends
. Identifying unique property IDs
. Calculating total bookings per property
. Detecting days when bookings exceed hotel capacity
. Exploring aggregated booking datasets


Setup Instructions

1. Clone the repository

bash
git clone https://github.com/yourusername/atliq-hotels-data-analysis.git
cd atliq-hotels-data-analysis

2. Install dependencies

commandline
pip install -r requirements.txt


3. Run the Jupyter Notebook

commandline
jupyter notebook


4. Open the notebook file and run the analysis cells step by step.

Project Objective

The main objective of this project is to perform data analysis on hotel booking datasets to generate insights that can help improve hotel business performance and decision-making.



Author

This project was created as part of a data analysis learning project using Python and real-world datasets.
