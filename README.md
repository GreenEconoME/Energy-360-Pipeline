# Energy-360-Pipeline

- Pulls timeseries kW data from Energy 360 using their API.
- Time of use kWh is calculated by integrating the kW data
- Creates the following for each monitored load and the aggregated campus load 
    - Daily kWh
    - Monthly kWh
    - Monthly cost calculated using the associated LADWP rates
    - Highest kW demand for each time of use
    
View the pipeline and plotly graphs <a href = https://nbviewer.org/github/GreenEconoME/Energy-360-Pipeline/blob/main/Energy%20360%20Pipeline.ipynb target = "_blank">here.</a>