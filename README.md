# EOSC454_project

This project uses magnetic data inversion to analyze faults and tectonic structures in British Columbia. Studying faults and tectonic structures using magnetic data enhances geophysical exploration techniques. Fault zones often exhibit magnetic anomalies due to rock composition, deformation, and fluid activity variations. By applying geophysical inversion techniques, this study will map subsurface magnetic variations to identify and characterize major fault structures, providing insights into their geological significance and potential environmental impact.

### Motivation
I had a question about energy production methods in countries with poor renewable resources, such as Indonesia and Japan. Indonesia, especially in the capital, has serious pollution issues since it relies on oil and gas to produce energy. In Japan, since the country does not have enough energy resources, it must depend on nuclear energy. The common factor in the two countries is that they both have high potential for geothermal resources. My motivation is to find the possibility of a shift in energy production methods to reduce the environmental impact. The important part of geothermal exploration is understanding the subsurface structure. Since at this point, I did not have enought resource(data) and knowledge in finding a potential spot in Indonesia or Japan, I used the data in Fraser River Fault zone as the place has been studied by many scientist in the past, i though it would be nice to get to understand what condition is needed for the exploration.


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


### Installation Instructions
1. Clone the Repository
git clone https://github.com/794Uguisuheiannkiyou/EOSC454_project.git
cd EOSC454_project
2. Create and activate the conda environment
conda env create -f environment.yml
conda activate eosc454
3. Launch Jupyter Notebook
jupyter notebook  -> open project.ipynb



