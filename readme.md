# Long-term tracking - Analysis of Drone behavior
This contains code needed to reproduce the figures in the paper:

Neubauer, Louisa, Jacob D Davidson, Ben Wild, David M Dormagen, Iain D Couzin, and Michael L Smith. “Honey Bee Drones Are Synchronously Hyperactive inside the Nest.”

Main analysis files descriptions:
- **'Drones - Figures for paper-v3.ipynb', 'Histograms + Center-periphery + Video.ipynb','Activation threshold model.ipynb'**:  These contain all the plots and results in the paper, and can be run with the included data
- **Data usage example - updated.ipynb**:  Contains simple, short example for reading in data

Other files:
- **weatherdata**: folder containing weather data used in the analysis
- **datafunctions.py, definitions_2019.py, displayfunctions.py, all_cohorts_2019.csv, summary_experiments_2019.csv**:  Contain functions and definitions used in the analysis
- **'Data processing - 1 - metrics and dataframes.ipynb', Data processing - 0 - database query.ipynb**:  Codes used to process data. 

The full dataset, including x-y trajectories and behavioral metrics calculated at different timescales (per-hour,per-5 minute, per-1 minute), is available at Zenodo:  http://doi.org/10.5281/zenodo.7298798

See also the associated repository that lists experimental details at https://github.com/jacobdavidson/bees_lifetimetracking_2019data