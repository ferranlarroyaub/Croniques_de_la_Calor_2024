# Cròniques de la Calor (Heat Chronicles). Summer 2024

This repository contains the necessary Jupyter Notebooks to filter, process, and analyze the data collected during the Summer 2024 campaign of the Heat Chronicles project (see [REF] for details on the experimental protocol and data acquisition procedures). In summary, the campaign consisted of approximately 50 citizen science “thermal walks” involving groups of 6–12 participants (local residents and co-researchers) from 14 non-academic partner organizations across five distinct neighborhoods or municipalities in the Barcelona metropolitan area. These areas were selected for their particular vulnerability to climate change and the urban heat island effect. A total of 439 participants took part. Custom walking routes were designed to record high-resolution, geolocated meteorological data (e.g., air temperature, relative humidity) using low-cost Meteotracker sensors (https://meteotracker.com/). After filtering and processing, the campaign produced a dataset of over 300,000 microclimatic data points. During each walk, participants stopped at predefined locations to complete standardized surveys reporting their Thermal Sensation Votes (TSV) and Thermal Comfort Votes (TCV), resulting in 1,867 paired self-reported entries. Sociodemographic information was also collected to contextualize responses. This integrated dataset combines objective environmental measurements with subjective thermal perceptions, enabling point-by-point analysis of the thermal experience across urban fabric. It provides a novel, multidimensional resource for investigating heat exposure, thermal inequality, and the experiential dimensions of climate vulnerability. The data are intended to support evidence-based decision-making in urban planning, public health, and climate adaptation.

## Repository structure
The repository is organized into two main sections
- **Data processing**:
   
   1. Data_processing_trajectories.ipynb --> Functions and workflows for filtering and processing raw sensor data from the walking trajectories.
   2. Data_processing_stops.ipynb --> Functions for computing average values and basic statistics for each stop along the walking routes.


- **Data analysis**:

   1. Data_analysis_votes_all.ipynb --> Statistical analysis of the responses to the heat perceptions, including histograms, bar-plots and correlation-maps
   2. Data_analysis_votes_gender.ipynb --> Statistical analysis of the responses to the heat perceptions depending on the gender, including histograms and bar-plots
   3. Data_analysis_votes_age.ipynb -->  Statistical analysis of the responses to the heat perceptions depending on the age, including histograms and bar-plots
   4. Data_analysis_votes_other_sociodem.ipynb -->  Statistical analysis of the responses to the heat perceptions depending on the neighbourhood kwnowledge, time spent in public space and category of the public splace, including histograms and bar-plots and correlation heat-maps between different sociodemographic responses.
   5. Data_analysis_votes_places.ipynb -->  Statistics of the 5 places in which the thermal walks took place. It includes general statistics and correlation with different socio-demographic responses and socio-economic traits of the neighbourhoods/cities.
  

