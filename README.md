# RhodeIsland
# RhodeIsland
Overview
This project is part of a Python and Data Analysis class Final Project that investigates racial disparities in traffic stops in Rhode Island. The dataset used for this analysis includes traffic stops made by law enforcement between January 1, 2013, and September 30, 2013, provided by the Rhode Island Department of Transportation (RIDOT).

The goal of this project is to examine whether individuals from different racial groups are treated differently during traffic stops and the outcomes of these stops.

Goals of the Project:

Investigate racial disparities in traffic stops.
Determine whether certain racial groups are stopped more frequently than others.
Analyze the outcomes of traffic stops, including citations, warnings, and arrests.

Data Source:
The data was obtained from the Rhode Island Department of Transportation (RIDOT). The dataset includes details such as:

Race or ethnicity of the driver
Reason for the stop
Outcome of the stop (citation, warning, or arrest)


Key Details in the Data:
Over 153,000 traffic stops in a 9-month period.
Racial information of the stopped drivers.
Outcomes of the traffic stops.


Project Structure:

Data Cleaning: Removed incomplete or inaccurate entries to maintain accuracy.
Exploratory Data Analysis (EDA): Examined the distribution of traffic stops and their outcomes across racial groups.
Visualization: Generated charts and tables to display outcomes (citations, warnings, arrests) by race.
Statistical Analysis: Calculated probabilities and disparities to assess potential biases.

Findings:

Differential Outcomes Based on Race: The analysis found that different racial groups experienced different outcomes after traffic stops. Black and Hispanic drivers were more likely to be arrested or receive warnings compared to White and Asian drivers.
Inequality in Traffic Stop Frequency: Black and Hispanic drivers had a higher likelihood of being arrested during traffic stops compared to White and Asian drivers, highlighting potential racial bias.


Visualizations:

Figure 3 & 4: Outcomes by racial group (citations, warnings, and arrests).
Figure 5: Arrest rates by racial group, showing disparities.

Technologies Used:

Python: For data processing and analysis.
Pandas: For data cleaning and manipulation.
Matplotlib/Seaborn: For data visualization.
Jupyter Notebook: For executing the analysis and visualizing results.

How to Run the Project:
1. create emty folder and open the gitbash command line
2.clone the repository to local machine using this command:
git clone https://github.com/hasnasalah/RhodeIsland.git
3.creat a virtual envirenment:
  windows:
     python -m venv env
     .\env\Scripts\activate
  macs or linux:
    python3 -m venv env
    source env/bin/activate
4. upload the requirements:
  pip install -r requirements.txt
5. run the project:
jupyter notebook analysis.ipynb







