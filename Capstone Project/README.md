# Dynamic Pricing for Urban Parking Lots

## Overview
This project implements dynamic pricing models for urban parking lots, using demand, competition, and real-time data features.
We develop three models with increasing complexity:

**Model 1: Baseline Linear Model**
- Price responds linearly to occupancy.

**Model 2: Demand-Based Function Model**
- Uses a demand function with occupancy rate, queue length, traffic level, special day flag, vehicle type
- Demand is normalised and price is bounded.

**Model 3: Competitive Pricing Model** *(optional)*
- Adds location intelligence, using geographic proximity and competitor pricing to adjust rates competitively.

## Tech Stack
- **Libraries & Frameworks**:
  - [pandas](https://pandas.pydata.org/) and  [numpy](https://numpy.org/) for data manipulation
  - [pathway](https://pathway.com/) for real-time data streaming and simulation of the demand and pricing pipeline
  - [bokeh](https://bokeh.org/) for interactive data visualisation
 
## Architecture Flow
1. **Data Preparation & Ingestion**

-> The dataset contains time-stamped occupancy, queue, traffic, vehicle type, special day, and location.
   
-> Ingested using Pathway for real-time streaming simulation.

3. **Pricing Algorithm**

-> Dynamic pricing logic for each model
   - for Model 1, we use: Price_t+1 = Price_t + α · (Occupancy/Capacity)
   - for Model 2, we use: Price_t = BasePrice · (1 + λ · NormalizedDemand); and also normalise the demand value through an example function (Demand = α· (Occupancy/Capacity) + β·QueueLength − γ·Traffic + δ·IsSpecialDay + ε·VehicleTypeWeight)
   - for Model 3, we modified Model 2 by calculating the distance between lots and adjusting the prices accordingly
  
-> Integration with simulation to evaluate strategy performance.

4. **Visualisation using Bokeh**

-> Created interactive time-series plots.
   
-> Comparison graphs across all three models.

## How to run this notebook
1. Open the notebook in Google Colab.
2. Install required packages (Pathway, Bokeh, Pandas).
3. Run the Pathway streaming pipeline.
4. Once enough data is streamed, pause the pipeline.
5. Continue executing the notebook to apply pricing models and visualise results.
