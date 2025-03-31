# EOSC454_project

This project uses magnetic data inversion to analyze faults and tectonic structures in British Columbia. Studying faults and tectonic structures using magnetic data enhances geophysical exploration techniques. Assessing geological stability, predicting seismic activity, and guiding infrastructure planning in seismically active regions is crucial. Fault zones often exhibit magnetic anomalies due to rock composition, deformation, and fluid activity variations. By applying geophysical inversion techniques, this study will map subsurface magnetic variations to identify and characterize major fault structures, providing insights into their geological significance and potential environmental impact.

### Methods:
1. Process magnetic anomaly data to remove regional trends and highlight structural features.
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
Stretch Goals:
• Correlate magnetic anomalies with earthquake activity.
• Integrate seismic data for a multi-method approach.
Reference: https://link.springer.com/article/10.1007/s11600-023-01184- 4?utm_source=chatgpt.com

### Installation Instructions
1. Clone the Repository
git clone https://github.com/794Uguisuheiannkiyou/EOSC454_project.git
cd EOSC454_project
2. Create and activate the conda environment
conda env create -f environment.yml
conda activate eosc454
3.Launch Jupyter Notebook
jupyter notebook  -> open project.ipynb



