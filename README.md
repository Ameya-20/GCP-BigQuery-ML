## Project Synopsis

The project encompasses these main stages:

1. Web analytics data processing and preparation
2. Feature engineering to establish an article engagement metric
3. Training a recommendation algorithm using cloud-based ML tools
4. Applying the model to generate content suggestions

## Repository Contents

- `create_table.sql`: SQL code for preparing and transforming raw analytics data
- `train.sql`: SQL code for building the recommendation algorithm
- `predict.sql`: SQL code for producing recommendations with the trained model
- `bqml_ga360.ipynb`: Jupyter notebook detailing the complete process with explanations

## Key Aspects

- Uses session duration as an indicator of article interest
- Implements data scaling and normalization methods
- Leverages cloud-based matrix factorization capabilities
- Demonstrates large-scale data handling in a cloud environment

## Quick Start Guide

1. Confirm access to a cloud-based dataset containing Google Analytics information
2. Execute the SQL scripts in this sequence:
   - `create_table.sql`
   - `train.sql`
   - `predict.sql`

