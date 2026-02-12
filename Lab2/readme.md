## Dataset Overview

The dataset `vehicles.csv` contains 1,500 vehicle records with the following features:

- `make`: Manufacturer of the vehicle
- `model`: Vehicle model
- `year`: Year of manufacture
- `mileage`: Total miles driven
- `price`: Selling price of the vehicle
- `color`: Vehicle color
- `fuel_type`: Type of fuel used
- `transmission`: Transmission type (Automatic/Manual)

Each row represents a single vehicle listing with its specifications and price.

## Machine Learning Problem

This is a **regression task** where the goal is to predict the `price` of a vehicle based on its features.  
Key predictive features include `year`, `mileage`, `make`, and `model`, while categorical features such as `color`, `fuel_type`, and `transmission` can be encoded to enhance model performance. The objective is to build a model that accurately estimates vehicle prices for new, unseen listings.
