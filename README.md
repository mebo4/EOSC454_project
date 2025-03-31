# EOSC454_project

This project uses magnetic data inversion to analyze faults and tectonic structures in British Columbia. Studying faults and tectonic structures using magnetic data enhances geophysical exploration techniques. Fault zones often exhibit magnetic anomalies due to rock composition, deformation, and fluid activity variations. By applying geophysical inversion techniques, this study will map subsurface magnetic variations to identify and characterize major fault structures, providing insights into their geological significance and potential environmental impact.

### Motivation
I had a question about energy production methods in countries with limited renewable resources, such as Indonesia and Japan. In Indonesia, especially in the capital, pollution is a serious issue due to the country’s reliance on oil and gas for energy production. On the other hand, Japan lacks sufficient domestic energy resources and therefore depends heavily on nuclear energy. A common factor between the two countries is their high potential for geothermal energy. My motivation is to explore the possibility of shifting energy production methods to reduce environmental impact.
Understanding the subsurface structure is an important aspect of geothermal exploration. Since I lack the necessary data and expertise to identify potential geothermal sites in Indonesia or Japan, I used data from the Fraser River Fault Zone instead. Scientists have studied this region extensively, and I thought it would be a good opportunity to understand the geological conditions required for successful geothermal exploration.


### Methods:
1. Process magnetic anomaly data to remove regional trends and highlight structural features. (I am at this point right now)
2. Forward Model the Magnetic Data
3. Use SimPEG to perform magnetic inversion, estimating subsurface fault geometry.
4. Compare results with published geological maps and seismic data (if available).



### Software:
SimPEG for inversion modeling.
Python for data processing and visualization.
Data Sets:
Airborne magnetic survey data from Natural Resources Canada (NRCAN). Study Region: A Fault system in British Columbia, such as the Rocky Mountain Trench or the Fraser River Fault Zone.


### Goals:
• Acquire and process airborne magnetic data for a selected fault system.

• Perform magnetic inversion to map subsurface fault structures.

### Components
• Environment.yml : shows the required packages to run the code

• Data file: gsc_s_bc_alb_2b.csv stores magnetic and altitude data at each latitude and longitude.

• project.ipynb: the main code for this project


### Installation Instructions
1. Clone the Repository
git clone https://github.com/794Uguisuheiannkiyou/EOSC454_project.git
cd EOSC454_project
2. Create and activate the conda environment
conda env create -f environment.yml

conda activate eosc454
3. Launch Jupyter Notebook
jupyter notebook  -> open project.ipynb



